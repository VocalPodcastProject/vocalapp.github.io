---
title: Feature Freeze, Translations Freeze In Effect
---

![]({{ site.baseurl}}/images/posts/2014-11-24-snowcone-pixar.png)

"Snowcone?" (Pixar)

Vocal is fast approaching its first stable release, and an important step on the path to 1.0 is the feature and translations freeze. This freeze gives translators time to translate the text inside Vocal into multiple languages with a guarantee that the text won't change before the release. It also marks the end of new features, meaning all development will be focused on fixing bugs and making the experience as stable as possible. Only in situations where new features absolutely must be added or strings must be altered will we do so.

This freeze comes on the tail end of adding MPRIS2 support, which means that Vocal can be controlled by the sound menu. MPRIS2 support was the most-requested feature from commentors at OMG! Ubuntu! when the site ran an article about our beta release, so I'm very happy to have this working for the 1.0 release. It still needs some polish, but it is functional. Not only does it allow for sound menu support in elementary OS, but it also allows for deeper system integration on any desktop environment that controls media via dbus and the MPRIS2 specification. Here's a picture of it in action:

![]({{ site.baseurl}}/images/posts/2014-11-24-sound-menu.png)

As always, please report any bugs you come across over at [our Launchpad page](https://bugs.launchpad.net/vocal). Fixing bugs is our focus from now up until the stable release! Stay tuned!