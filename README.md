
_____________________________________

# Drawpile - A Collaborative Drawing Program

[![CI status badge](../../actions/workflows/main.yml/badge.svg)](../../actions/workflows/main.yml)[![translation status](https://hosted.weblate.org/widgets/drawpile/-/svg-badge.svg)](https://hosted.weblate.org/engage/drawpile/)


>Drawpile is a drawing program that lets you draw, paint and animate together with others on the same canvas. It runs on Windows, Linux, macOS and Android.

_____________________________________

## _Drawpile Installation_

•Take a look at the [downloads page on drawpile.net](https://drawpile.net/download/) or the [GitHub releases](https://github.com/drawpile/Drawpile/releases).

•Instructions on how to compile Drawpile from source are found here on [this documentation page](https://docs.drawpile.net/help/development/buildingfromsource).

•If you're using Arch Linux, you can get Drawpile [from the AUR](https://aur.archlinux.org/packages/drawpile).

_____________________________________

## _Getting Help, Giving Suggestions & Reporting Bugs..._

•If you're having trouble with something and want to report a bug *or* would like to just suggest a feature, please take a look at the [help page on drawpile.net](https://drawpile.net/help/).

•You may also directly [report issues here on GitHub](https://github.com/drawpile/Drawpile/issues). If you use Discord, you are very Welcome to [join the Drawpile server](https://drawpile.net/discord/). You may also use the [chatroom on libera.chat](https://drawpile.net/irc/). It's easily done through a browser with no need to make an account.

_____________________________________

## _Want to Help Contribute?_

•Pull Requests are Welcome, be it for code or anything else! 

•If you'd like to help Contribute towards the Documentation, you can do so [over in this repository](https://github.com/drawpile/drawpile.github.io).

•If you'd like to help translate Drawpile to any language, take a look at [Drawpile on Weblate](https://hosted.weblate.org/engage/drawpile/), where you can translate languages directly in any browser.

_____________________________________

[![translation status](https://hosted.weblate.org/widgets/drawpile/-/287x66-grey.png)](https://hosted.weblate.org/engage/drawpile/)

_____________________________________

## _Client Dependencies, Libraries, Patches & Signatures..._


>The Drawpile client uses the following shared libraries:

* Qt (all platforms)

* OpenSSL (all platforms)

* KDE Framework Archive (Windows, Linux AppImage, Android)

* libzip (macOS, Linux Flatpak)


•On Windows, these libraries are signed along with the executable package using *free code signing*, thankfully provided by [SignPath.io](https://about.signpath.io/) and a  certificate by [SignPath Foundation](https://signpath.org/). 
[See the code [signing policy on drawpile.net](https://drawpile.net/codesigningpolicy/) for even more details!]

•The dependencies are pinned to known good versions and the source code for is verified against the hashes and signatures provided in their releases from upstream. SHA384 hash checks are also done for each build to ensure integrity of the source code also retrieved from upstream.

•We make some patches to these dependencies when building the application, which you can find in [.github/scripts/patches](.github/scripts/patches). Each patch file contains a description as to what it does.

•You can find build processes, versions, upstream source URL's and hashes for [Qt and OpenSSL here](.github/scripts/build-qt.cmake). Also, for [KDE Framework Archive and libzip here](.github/scripts/build-other.cmake).

____________________________________