---
title: Some Growing Pains
---

If you are a beta tester, this post might be of interest to you. First, let me start off with the good news. Over the past few weeks we've been getting reports of segfault errors when trying to launch Vocal, but I believe that problem was fixed last night.

Unfortunately, that fix led us to discover another bug, and this one is pretty critical. Due to a single overlooked comma in the source code, album art wasn't getting saved correctly in the database. If you start to notice either that your album art is suddenly missing, or you are unable to add a new podcast feed, please do the following steps:

1. Open Vocal, click on the gear menu, and select export subscriptions. Save the backup file somewhere where you will be able to find it.

2. Open terminal and enter the following commands (or remove the folders using a file browser if you feel confident in navigating to hidden directories inside your home folder). **Please copy and paste these**, as entering them incorrectly could lead to potential data lose.

<code class="terminal"><pre>
rm -rf ~/.config/vocal
rm -rf ~/.local/share/vocal
</pre></code>

3. Open Vocal again. Everything should be reset. Select the import option and choose the file you exported in step one.

We apologize for the inconvenience. We absolutely hate ever having to tell users to delete their configs, unfortunately this bug was at the database level and just too important to leave alone.

As always, if you find any other issues, please report them at [our Launchpad page](https://bugs.launchpad.net/vocal).
