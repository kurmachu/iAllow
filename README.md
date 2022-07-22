***

<h1 align="center">
<sub>
<img  src="https://raw.githubusercontent.com/kurmachu/iAllow/master/doc/img/icon38%402x.png" height="38" width="38">
</sub>
iAllow Destination
</h1>
<p align="center">
<sup>
      <a href="https://github.com/uBlockOrigin/uBlock-issues/issues/586">the missing uBlock Origin setting</a> — <i>you <b>actually</b></i> decide what enters your browser.
</sup>
<br>
<sub><b>WARNING!</b> This is a jank mod of <a href="https://github.com/gorhill/uBlock">uBlock Origin</a>, and will probably not be actively supported.</sub>
</p>

***

**uBlock Origin but off by default. (also only in english\* and for chrome\*\*)**

iAllow Destination is a joke name for a modified version of uBlock Origin that inverts whitelist behavior to make uBlock Origin off-by-default. This is behavior I personally would like to use, but which the project maintainers do not want. Hence, this fork.

*\*Other languages work but do not have updated text in the dashboard.*

*\*\*This may work on other browser versions, but it is untested and the name is not changed.*

***

* [Documentation](#documentation)
* [Purpose & General Info](#philosophy)
* [Installation](#installation)
* [uBlock Origin's original project repository](https://github.com/gorhill/uBlock)

## Documentation

[Please read uBlock Origin's original readme for documentation.](https://github.com/gorhill/uBlock#documentation) 

## Philosophy

[uBlock Origin's Manifesto](https://github.com/gorhill/uBlock/blob/master/MANIFESTO.md) makes many claims about user control and choice, such as
> The user decides what web content is acceptable or not in their browser.

> Users are best placed to know what is or is not acceptable to them. uBlock's sole purpose is to give users the means to enforce their own choices.

Additionaly, [uBlock Origin's about segment of the readme](https://github.com/gorhill/uBlock#about) claims to be *"For users by users."*

Unfortionatly this is false in practice, and as quoted by the owner of the project:
> uBO is for people who share the view that the net is hostile by default and consequently uBO being disabled everywhere by default is incompatible with this view

Inherently this means that uBlock Origin is not actually for users. At least not *all* users. For the people who fall outside of the range of valid user choises uBlock supports, there's iAllow.

*Oh also you need to be using chrome(\*, see above) and I only changed one page due to lazy please don't take this too seriously.*

## Installation

There are no specific build instructions or prebuilt packages at this time. Please clone the repository and refer to uBlock Origin's [development building instructions](https://github.com/gorhill/uBlock/tree/master/dist#build-instructions-for-developers).

## License

[GPLv3][License].


<!----------------------------------------------------------------------------->

[Malicious Blocklist]: https://gitlab.com/curben/urlhaus-filter#urlhaus-malicious-url-blocklist
[3rd Party Requests]: https://requestpolicycontinued.github.io/#what-are-cross-site-requests
[How To Filters]: https://help.eyeo.com/en/adblockplus/how-to-write-filters
[Deploy Firefox]: https://decentsecurity.com/ublock-for-firefox-deployment/
[Debian Package]: https://packages.debian.org/stable/source/ublock-origin
[Deploy Chrome]: https://decentsecurity.com/ublock-for-google-chrome-deployment/
[Performance]: https://www.debugbear.com/blog/chrome-extension-performance-2021#how-do-ad-blockers-and-privacy-tools-affect-browser-performance
[Peters List]: https://pgl.yoyo.org/adservers/policy.php
[EasyPrivacy]: https://easylist.github.io/#easyprivacy
[Chrome Dev]: https://chrome.google.com/webstore/detail/ublock-origin-dev-build/cgbcahbpdhpcegmbfconppldiemgcoii
[SeaMonkey]: https://www.seamonkey-project.org/
[Pale Moon]: https://www.palemoon.org/
[EasyList]: https://easylist.github.io/#easylist
[Mozilla]: https://addons.mozilla.org/firefox/addon/ublock-origin/
[Crowdin]: https://crowdin.com/project/ublock
[Chrome]: https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm
[Reddit]: https://www.reddit.com/r/uBlockOrigin/
[Theft]: https://twitter.com/LeaVerou/status/518154828166725632
[Opera]: https://addons.opera.com/extensions/details/ublock/
[Edge]: https://microsoftedge.microsoft.com/addons/detail/ublock-origin/odfafepnkmbhccpbejgmiehpchacaeak
[NPM]: https://www.npmjs.com/package/@gorhill/ubo-core

[Manifesto]: MANIFESTO.md
[License]: LICENSE.txt

[Nicole Rolls]: https://github.com/nicole-ashley/uBlock-Edge
[@el1t]: https://github.com/el1t


<!---------------------------------[ Internal ]-------------------------------->

[Popup User Interface]: https://github.com/gorhill/uBlock/wiki/Quick-guide:-popup-user-interface
[Manual Installation]: https://github.com/gorhill/uBlock/tree/master/dist#install
[Extended Syntax]: https://github.com/gorhill/uBlock/wiki/Static-filter-syntax#extended-syntax
[Dynamic Filters]: https://github.com/gorhill/uBlock/wiki/Dynamic-filtering:-quick-guide
[Firefox Legacy]: https://github.com/gorhill/uBlock/blob/master/dist/README.md#firefox-legacy
[Privacy Policy]: https://github.com/gorhill/uBlock/wiki/Privacy-policy
[UBlock Filters]: https://github.com/uBlockOrigin/uAssets/tree/master/filters
[Default Deny]: https://github.com/gorhill/uBlock/wiki/Dynamic-filtering:-default-deny
[Permissions]: https://github.com/gorhill/uBlock/wiki/Permissions
[Commit Rate]: https://github.com/gorhill/uBlock/commits/master
[Deploying]: https://github.com/gorhill/uBlock/wiki/Deploying-uBlock-Origin
[Blocking]: https://github.com/gorhill/uBlock/wiki/Blocking-mode
[Releases]: https://github.com/gorhill/uBlock/releases
[UMatrix]: https://github.com/gorhill/uMatrix
[Issues]: https://github.com/uBlockOrigin/uBlock-issues/issues
[Beta]: https://github.com/gorhill/uBlock/blob/master/dist/README.md#for-beta-version
[Wiki]: https://github.com/gorhill/uBlock/wiki


<!----------------------------------[ Badges ]--------------------------------->

[Badge Localization]: https://d322cqt584bo4o.cloudfront.net/ublock/localized.svg
[Badge Commits]: https://img.shields.io/github/commit-activity/m/gorhill/ublock?label=Commits
[Badge Mozilla]: https://img.shields.io/amo/rating/ublock-origin?label=Firefox
[Badge License]: https://img.shields.io/badge/License-GPLv3-blue.svg
[Badge Chrome]: https://img.shields.io/chrome-web-store/rating/cjpalhdlnbpafiamejdnhcphjbkeiagm?label=Chrome
[Badge Issues]: https://img.shields.io/github/issues/uBlockOrigin/uBlock-issues
[Badge NPM]: https://img.shields.io/npm/v/@gorhill/ubo-core

