---
description: Required steps to update add-ons for Thunderbird Supernova 115.
---

# Update for Thunderbird Supernova

This section covers the required update steps for add-ons which are already compatible with Thunderbird 102 and need to be made compatible with Thunderbird Beta.

## Changes in WebExtension APIs

Our WebExtension APIs are meant to be stable, but we are adding new features and since this is a very young technology this might also require backward incompatible changes. All WebExtension API changes are listed in our API documentation:

* [Thunderbird 106](https://webextension-api.thunderbird.net/en/latest/changes/beta106.html)
* [Thunderbird 107](https://webextension-api.thunderbird.net/en/latest/changes/beta107.html)
* [Thunderbird 111](https://webextension-api.thunderbird.net/en/latest/changes/beta111.html)
* [Thunderbird 113 Manifest v2](https://webextension-api.thunderbird.net/en/latest/changes/beta113.html) and [Thunderbird 113 Manifest v3](https://webextension-api.thunderbird.net/en/latest-mv3/changes/beta113.html)
* [Thunderbird 115 Manifest v2](https://webextension-api.thunderbird.net/en/latest/changes/beta115.html) and [Thunderbird 115 Manifest v3](https://webextension-api.thunderbird.net/en/latest-mv3/changes/beta115.html)

## Changes in Thunderbird Core

MailExtensions can still run legacy code inside [Experiments](../../mailextensions/#experiment-apis). Such legacy code has to be adjusted to changes made in Thunderbird Core. All known changes are listed in the following document:

* [Changes in Thunderbird 103-115](adapt-to-changes-in-thunderbird-103-115.md)

If you have encountered a change which is not yet listed there, please [contact us](../../community.md), so we can update the list.



## Changes in Shared Experiments

If you are using any of the shared Experiments, you probably do not have to update them on your own. Check if an updated version is already available:

* [Shared Experiments on DTN](../../mailextensions/#sharing-experiment-apis)
* [Wrapper Experiments available in the ADS repository](https://github.com/thundernest/addon-developer-support/tree/master/wrapper-apis)
