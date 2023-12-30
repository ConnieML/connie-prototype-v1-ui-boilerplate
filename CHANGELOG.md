# Changelog

## [1.61.109](https://github.com/brave/brave-browser/releases/tag/v1.61.109)

 - Fixed crash when closing tabs on macOS in certain cases. ([#34909](https://github.com/brave/brave-browser/issues/34909))
 - Upgraded Chromium to 120.0.6099.144. ([#34988](https://github.com/brave/brave-browser/issues/34988)) ([Changelog for 120.0.6099.144](https://chromium.googlesource.com/chromium/src/+log/120.0.6099.115..120.0.6099.144?pretty=fuller&n=1000))

## [1.61.106](https://github.com/brave/brave-browser/releases/tag/v1.61.106)

 - Fixed Brave Ads crash on Windows x86. ([#34854](https://github.com/brave/brave-browser/issues/34854))

## [1.61.104](https://github.com/brave/brave-browser/releases/tag/v1.61.104)

### Web3

 - Fixed "Signature verification error" being incorrectly displayed in Brave Wallet with the signTransaction method. ([#34842](https://github.com/brave/brave-browser/issues/34842))

### General

 - Fixed crash when accessing "Extensions" from Private window hamburger menu. ([#34811](https://github.com/brave/brave-browser/issues/34811))
 - Upgraded Chromium to 120.0.6099.115. ([#34856](https://github.com/brave/brave-browser/issues/34856)) ([Changelog for 120.0.6099.115](https://chromium.googlesource.com/chromium/src/+log/120.0.6099.71..120.0.6099.115?pretty=fuller&n=1000))

## [1.61.101](https://github.com/brave/brave-browser/releases/tag/v1.61.101)

 - Upgraded Chromium to 120.0.6099.71. ([#34740](https://github.com/brave/brave-browser/issues/34740)) ([Changelog for 120.0.6099.71](https://chromium.googlesource.com/chromium/src/+log/120.0.6099.62..120.0.6099.71?pretty=fuller&n=1000))

## [1.61.100](https://github.com/brave/brave-browser/releases/tag/v1.61.100)

### Web3

 - Added Brave Rewards custodial balance line item into Brave Wallet. ([#31713](https://github.com/brave/brave-browser/issues/31713))
 - Updated Brave Wallet panel navigation to be persistent on open/close of panel. ([#33677](https://github.com/brave/brave-browser/issues/33677))
 - Updated NFT name to wrap on "Send" panel screen when necessary. ([#33442](https://github.com/brave/brave-browser/issues/33442))
 - Removed horizontal scroll bar on "Edit gas" screen. ([#33373](https://github.com/brave/brave-browser/issues/33373))
 - Fixed incorrect error message when trying to import accounts from a locked Ledger device. ([#21016](https://github.com/brave/brave-browser/issues/21016))
 - Fixed persistent "Sign Transaction" panel even after transaction is cancelled. ([#34668](https://github.com/brave/brave-browser/issues/34668))
 - Fixed Brave Wallet menu display on small screens. ([#33877](https://github.com/brave/brave-browser/issues/33877))

### Rewards

 - Implemented new design for account provider selection screen. ([#33258](https://github.com/brave/brave-browser/issues/33258))

### General

 - Added search, sort, and editing features to the Bookmarks side panel. ([#34021](https://github.com/brave/brave-browser/issues/34021))
 - Added a command line switch to disable vertical tabs. ([#33711](https://github.com/brave/brave-browser/issues/33711))
 - Added universal online installer for Windows. ([#32598](https://github.com/brave/brave-browser/issues/32598))
 - Added system default theme mode on Linux. ([#14685](https://github.com/brave/brave-browser/issues/14685))
 - Updated margins for sidebar buttons. ([#34249](https://github.com/brave/brave-browser/issues/34249))
 - Upgraded Chromium to 120.0.6099.62. ([#34723](https://github.com/brave/brave-browser/issues/34723)) ([Changelog for 120.0.6099.62](https://chromium.googlesource.com/chromium/src/+log/119.0.6045.199..120.0.6099.62?pretty=fuller&n=1000))

## [1.60.125](https://github.com/brave/brave-browser/releases/tag/v1.60.125)

 - Added support for quoted scriptlet arguments. ([#34170](https://github.com/brave/brave-browser/issues/34170))
 - Fixed issue where Brave Leo gives incomplete answers in certain cases. ([#34321](https://github.com/brave/brave-browser/issues/34321))
 - Fixed VPN toolbar button state mismatch. ([#33023](https://github.com/brave/brave-browser/issues/33023))
 - Fixed misaligned window buttons on Linux. ([#34201](https://github.com/brave/brave-browser/issues/34201))
 - Fixed "Set as default" not working on Linux when installed via Snap. ([#34053](https://github.com/brave/brave-browser/issues/34053))
 - Upgraded Chromium to 119.0.6045.199. ([#34574](https://github.com/brave/brave-browser/issues/34574)) ([Changelog for 119.0.6045.199](https://chromium.googlesource.com/chromium/src/+log/119.0.6045.163..119.0.6045.199?pretty=fuller&n=1000))

## [1.60.118](https://github.com/brave/brave-browser/releases/tag/v1.60.118)

 - Fixed crash on startup when using Linux Arm64. ([#33596](https://github.com/brave/brave-browser/issues/33596))
 - Upgraded Chromium to 119.0.6045.163. ([#34331](https://github.com/brave/brave-browser/issues/34331)) ([Changelog for 119.0.6045.163](https://chromium.googlesource.com/chromium/src/+log/119.0.6045.124..119.0.6045.163?pretty=fuller&n=1000))

## [1.60.114](https://github.com/brave/brave-browser/releases/tag/v1.60.114)

 - Added a first-party exception list to the correct adblock engine. ([#34081](https://github.com/brave/brave-browser/issues/34081))
 - Upgraded Chromium to 119.0.6045.124. ([#34164](https://github.com/brave/brave-browser/issues/34164)) ([Changelog for 119.0.6045.124](https://chromium.googlesource.com/chromium/src/+log/119.0.6045.105..119.0.6045.124?pretty=fuller&n=1000))

## [1.60.110](https://github.com/brave/brave-browser/releases/tag/v1.60.110)

### Web3

 - Added loading state indicator on "Select token" screen. ([#32641](https://github.com/brave/brave-browser/issues/32641))
 - Implemented Sign-In With Ethereum (SIWE). ([#32078](https://github.com/brave/brave-browser/issues/32078))
 - Implemented Safe Sign for CoW Swaps. ([#33093](https://github.com/brave/brave-browser/issues/33093))
 - Improved performance of "Network" filter dropdown. ([#33004](https://github.com/brave/brave-browser/issues/33004))
 - Fixed Blockie account addresses being cut off in the "Send" panel. ([#33912](https://github.com/brave/brave-browser/issues/33912))
 - Fixed formatting on the "Market" tab of the panel. ([#33331](https://github.com/brave/brave-browser/issues/33331))
 - Fixed incorrect balances and infinite loading for amounts in certain cases. ([#33187](https://github.com/brave/brave-browser/issues/33187))

### General

 - Added Brave Leo - AI for questions and answers leveraging page context and integrated into the sidebar (being rolled out in phases using Griffin starting at 20%). ([#34044](https://github.com/brave/brave-browser/issues/34044))
 - Added support for "#@#+js()" syntax for blanket scriptlet exception. ([#33766](https://github.com/brave/brave-browser/issues/33766))
 - Added title to "Reading List" side panel. ([#32953](https://github.com/brave/brave-browser/issues/32953))
 - Added title to "Bookmarks" side panel. ([#32952](https://github.com/brave/brave-browser/issues/32952))
 - [Security] Fixed WebTorrent redirect issue as reported on HackerOne by xiaoyinl. ([#32856](https://github.com/brave/brave-browser/issues/32856))
 - [Security] Fixed WebTorrent navigation issue as reported on HackerOne by xiaoyinl. ([#32743](https://github.com/brave/brave-browser/issues/32743))
 - [Security] Fixed Tor tab redirect issue as reported on HackerOne by xiaoyinl. ([#32706](https://github.com/brave/brave-browser/issues/32706))
 - Enabled History datatype for Brave Sync. ([#32876](https://github.com/brave/brave-browser/issues/32876))
 - Enabled SKU SDK on Linux. ([#32803](https://github.com/brave/brave-browser/issues/32803))
 - Updated default behavior for vertical tabs display when in fullscreen mode. ([#33136](https://github.com/brave/brave-browser/issues/33136))
 - Updated display frequency for New Tab Page Sponsored Image. ([#33228](https://github.com/brave/brave-browser/issues/33228))
 - Updated New Tab Page Sponsored Image counter to reset every 24 hours. ([#31551](https://github.com/brave/brave-browser/issues/31551))
 - Updated design of Brave News feed cards. ([#33296](https://github.com/brave/brave-browser/issues/33296))
 - Updated Brave News to only download the page's linked alternate feeds when the UI list is opened. ([#33246](https://github.com/brave/brave-browser/issues/33246))
 - Moved brave://settings/socialBlocking to brave://settings/shields. ([#32956](https://github.com/brave/brave-browser/issues/32956))
 - Moved brave://settings/newTab to brave://settings/getStarted. ([#32954](https://github.com/brave/brave-browser/issues/32954))
 - Removed known tracking parameter "_gl" from URLs. ([#33188](https://github.com/brave/brave-browser/issues/33188))
 - Removed known tracking parameter "unicorn_click_id" from URLs. ([#33172](https://github.com/brave/brave-browser/issues/33172))
 - Removed known tracking parameters "at_recipient_id" and "at_recipient_list" from URLs. ([#32488](https://github.com/brave/brave-browser/issues/32488))
 - Fixed flashing tray icon when clicking "Try again" in the VPN panel on Windows. ([#33405](https://github.com/brave/brave-browser/issues/33405))
 - Fixed keyboard shortcuts not working after selecting Speedreader appearance controls. ([#32948](https://github.com/brave/brave-browser/issues/32948))
 - Fixed rendering of Speedreader theme checkmark on Linux. ([#32947](https://github.com/brave/brave-browser/issues/32947))
 - Fixed overlapping vertical lines in the "Tabs" section under brave://settings/appearance. ([#30100](https://github.com/brave/brave-browser/issues/30100))
 - Upgraded Chromium to 119.0.6045.105. ([#34024](https://github.com/brave/brave-browser/issues/34024)) ([Changelog for 119.0.6045.105](https://chromium.googlesource.com/chromium/src/+log/118.0.5993.117..119.0.6045.105?pretty=fuller&n=1000))

## [1.59.124](https://github.com/brave/brave-browser/releases/tag/v1.59.124)

### Web3

 - Fixed "Market" tab displaying incorrect colors for increased/decreased prices. ([#33838](https://github.com/brave/brave-browser/issues/33838))

### General

 - Brave Ad Block Resources Library now updates via Component Updater on a more frequent basis, to always have most recent Ad Block lists. ([#32274](https://github.com/brave/brave-browser/issues/32274))
 - Upgraded Chromium to 118.0.5993.117. ([#33893](https://github.com/brave/brave-browser/issues/33893)) ([Changelog for 118.0.5993.117](https://chromium.googlesource.com/chromium/src/+log/118.0.5993.96..118.0.5993.117?pretty=fuller&n=1000))

## [1.59.122](https://github.com/brave/brave-browser/releases/tag/v1.59.122)

 - Upgraded Chromium to 118.0.5993.96 (macOS only). ([#33752](https://github.com/brave/brave-browser/issues/33752)) ([Changelog for 118.0.5993.96](https://chromium.googlesource.com/chromium/src/+log/118.0.5993.88..118.0.5993.96?pretty=fuller&n=1000))

## [1.59.120](https://github.com/brave/brave-browser/releases/tag/v1.59.120)

### Web3

 - Fixed not being able to authorize hardware wallet connection to complete transactions. ([#33613](https://github.com/brave/brave-browser/issues/33613))

### General

 - Fixed crash when certain theme extensions are installed while vertical tabs are enabled. ([#33598](https://github.com/brave/brave-browser/issues/33598))
 - Fixed crash when accessing "brave://settings" while "brave://flags/#brave-vpn" has been disabled. ([#33581](https://github.com/brave/brave-browser/issues/33581))
 - Fixed crash when accessing "brave://settings" on Guest profiles. ([#32825](https://github.com/brave/brave-browser/issues/32825))
 - Upgraded Chromium to 118.0.5993.88. ([#33694](https://github.com/brave/brave-browser/issues/33694)) ([Changelog for 118.0.5993.88](https://chromium.googlesource.com/chromium/src/+log/118.0.5993.70..118.0.5993.88?pretty=fuller&n=1000))

## [1.59.117](https://github.com/brave/brave-browser/releases/tag/v1.59.117)

### Web3

 - Added Neon EVM preloaded chains. ([#31760](https://github.com/brave/brave-browser/issues/31760))
 - Added method to return "Swap" protocol fees. ([#32464](https://github.com/brave/brave-browser/issues/32464))
 - Added a runtime flag to use staging Ratios service. ([#32043](https://github.com/brave/brave-browser/issues/32043))
 - Enabled Brave Wallet panel V2 by default. ([#32352](https://github.com/brave/brave-browser/issues/32352))
 - Implemented NFT management V2. ([#33095](https://github.com/brave/brave-browser/issues/33095))
 - Updated "Buy" and "Swap" from panel to open in full page view. ([#33353](https://github.com/brave/brave-browser/issues/33353))
 - Updated "Learn more" link in IPFS infobar to open in a new tab. ([#32178](https://github.com/brave/brave-browser/issues/32178))
 - Updated Coinbase On-ramp description. ([#32147](https://github.com/brave/brave-browser/issues/32147))
 - Removed Fantom from preloaded chains. ([#32085](https://github.com/brave/brave-browser/issues/32085))
 - Fixed "Deposit" screen text wrapping in Brave Wallet panel. ([#33425](https://github.com/brave/brave-browser/issues/33425))
 - Fixed NFT images not being shown on the "Deposit" screen. ([#32446](https://github.com/brave/brave-browser/issues/32446))
 - Fixed POAPs not loading successfully. ([#31763](https://github.com/brave/brave-browser/issues/31763))
 - Fixed inability to interact with tooltip text. ([#32015](https://github.com/brave/brave-browser/issues/32015))
 - Fixed alignment of "Asset Group" description on the panel. ([#32504](https://github.com/brave/brave-browser/issues/32504))
 - Fixed the "Portfolio" page to use the correct fiat values for test network assets. ([#31819](https://github.com/brave/brave-browser/issues/31819))

### Rewards

 - Updated "Estimated earnings" to display "Earnings so far". ([#32653](https://github.com/brave/brave-browser/issues/32653))
 - Fixed "Earnings from Ads" on the monthly statement to display a link to the user's custodian dashboard when "Logged Out". ([#31791](https://github.com/brave/brave-browser/issues/31791))

### General

 - Added icons and streamlined the hamburger menu. ([#32089](https://github.com/brave/brave-browser/issues/32089))
 - Added rounded corners to all panels from the navigation bar. ([#32150](https://github.com/brave/brave-browser/issues/32150))
 - Added "Use WireGuard protocol in Brave VPN" setting under brave://settings/system. ([#32002](https://github.com/brave/brave-browser/issues/32002))
 - Added "Make auto-fill available in private windows" setting under brave://settings/autofill. ([#9795](https://github.com/brave/brave-browser/issues/9795))
 - Added Widevine support for Arm64 on Windows. ([#28318](https://github.com/brave/brave-browser/issues/28318))
 - [Security] Updated which origins and URLs trigger debouncing and request-OTR protections as reported on HackerOne by nishimunea. ([#32230](https://github.com/brave/brave-browser/issues/32230))
 - [Security] Block ".onion" domain subresource requests in non-Tor contexts as reported on HackerOne by xiaoyinl. ([#32108](https://github.com/brave/brave-browser/issues/32108))
 - [Security] Fixed crash when loading brave://optimization-guide-internals as reported on HackerOne by jaguilera. ([#31648](https://github.com/brave/brave-browser/issues/31648))
 - Improved password storage backend detection logic on Linux. ([#32314](https://github.com/brave/brave-browser/issues/32314))
 - Updated Brave VPN hamburger menu entries. ([#33027](https://github.com/brave/brave-browser/issues/33027))
 - Updated the Wayback Machine infobar to display a "Don't show again" checkbox. ([#32404](https://github.com/brave/brave-browser/issues/32404))
 - Removed disabled features from DevTools. ([#32187](https://github.com/brave/brave-browser/issues/32187))
 - Fixed crash when adding scriptlet injection filters with too many arguments. ([#32916](https://github.com/brave/brave-browser/issues/32916))
 - Fixed broken flag for "Enable extension network blocking" under brave://flags. ([#32569](https://github.com/brave/brave-browser/issues/32569))
 - Fixed New Tab Page background image(s) being skipped after startup in certain cases. ([#32577](https://github.com/brave/brave-browser/issues/32577))
 - Fixed missing toggle for Brave VPN on the hamburger menu. ([#32703](https://github.com/brave/brave-browser/issues/32703))
 - Fixed incorrect state being displayed for Brave VPN toolbar button in certain cases. ([#32542](https://github.com/brave/brave-browser/issues/32542))
 - Upgraded Chromium to 118.0.5993.70. ([#33556](https://github.com/brave/brave-browser/issues/33556)) ([Changelog for 118.0.5993.70](https://chromium.googlesource.com/chromium/src/+log/117.0.5938.153..118.0.5993.70?pretty=fuller&n=1000))

## [1.58.137](https://github.com/brave/brave-browser/releases/tag/v1.58.137)

 - Upgraded Chromium to 117.0.5938.153. ([#33391](https://github.com/brave/brave-browser/issues/33391)) ([Changelog for 117.0.5938.153](https://chromium.googlesource.com/chromium/src/+log/117.0.5938.140..117.0.5938.153?pretty=fuller&n=1000))

## [1.58.135](https://github.com/brave/brave-browser/releases/tag/v1.58.135)

### General

 - Added Argentina, France, and Germany content feed support for Brave News. ([#33251](https://github.com/brave/brave-browser/issues/33251) & [#32416](https://github.com/brave/brave-browser/issues/32416))
 - Upgraded Chromium to 117.0.5938.140. ([#33282](https://github.com/brave/brave-browser/issues/33282)) ([Changelog for 117.0.5938.140](https://chromium.googlesource.com/chromium/src/+log/117.0.5938.92..117.0.5938.140?pretty=fuller&n=1000))

## [1.58.131](https://github.com/brave/brave-browser/releases/tag/v1.58.131)

 - Upgraded Chromium to 117.0.5938.92. ([#33181](https://github.com/brave/brave-browser/issues/33181)) ([Changelog for 117.0.5938.92](https://chromium.googlesource.com/chromium/src/+log/117.0.5938.88..117.0.5938.92?pretty=fuller&n=1000))

## [1.58.129](https://github.com/brave/brave-browser/releases/tag/v1.58.129)

### General

 - Added brave://flags#brave-global-privacy-control-enabled to opt out of GPC. ([#32231](https://github.com/brave/brave-browser/issues/32231))
 - Updated SKU credential matching logic for Brave VPN. ([#32924](https://github.com/brave/brave-browser/issues/32924))
 - Reverted hidden vertical tab bar when in full screen mode. ([#33106](https://github.com/brave/brave-browser/issues/33106))

## [1.58.127](https://github.com/brave/brave-browser/releases/tag/v1.58.127)

 - Upgraded Chromium to 117.0.5938.88. ([#33052](https://github.com/brave/brave-browser/issues/33052)) ([Changelog for 117.0.5938.88](https://chromium.googlesource.com/chromium/src/+log/117.0.5938.62..117.0.5938.88?pretty=fuller&n=1000))

## [1.58.124](https://github.com/brave/brave-browser/releases/tag/v1.58.124)

### Web3

 - Added IPFS promotional infobar. ([#32010](https://github.com/brave/brave-browser/issues/32010))
 - Added Coinbase as an Onramp provider. ([#32083](https://github.com/brave/brave-browser/issues/32083))
 - Added support for EIP-6963. ([#30595](https://github.com/brave/brave-browser/issues/30595))
 - Added virtualized tokens list to the "Buy" and "Deposit" screens. ([#31675](https://github.com/brave/brave-browser/issues/31675))
 - Added loading skeleton and spinner to the "NFT" page. ([#31485](https://github.com/brave/brave-browser/issues/31485))
 - Added a "More" menu for each asset on the "Portfolio" page. ([#30982](https://github.com/brave/brave-browser/issues/30982))
 - Added filters to the "NFT" tab. ([#31041](https://github.com/brave/brave-browser/issues/31041))
 - Added grouping to the "NFT" tab. ([#31342](https://github.com/brave/brave-browser/issues/31342))
 - Added an empty state to the "Portfolio" page when filters are applied. ([#31147](https://github.com/brave/brave-browser/issues/31147))
 - Added the ability for users to choose which Solana account to choose when connecting to Solana DApps. ([#31109](https://github.com/brave/brave-browser/issues/31109))
 - Added the ability to allow selection of an existing "f1 address" as recipient when sending FEVM tokens. ([#31101](https://github.com/brave/brave-browser/issues/31101))
 - Added segmented controls to the "Asset Details" view. ([#30981](https://github.com/brave/brave-browser/issues/30981))
 - Implemented autofill of CoinGecko ID's when adding custom tokens. ([#31975](https://github.com/brave/brave-browser/issues/31975))
 - Improved performance on the "Buy" screen of Brave Wallet. ([#31685](https://github.com/brave/brave-browser/issues/31685))
 - Improved balance scan performance. ([#30779](https://github.com/brave/brave-browser/issues/30779))
 - Moved IPFS banner to the "NFT" tab. ([#31332](https://github.com/brave/brave-browser/issues/31332))
 - Updated design on the "Wallet Unlock" screen. ([#31603](https://github.com/brave/brave-browser/issues/31603))
 - Updated design on the "Market" page. ([#31611](https://github.com/brave/brave-browser/issues/31611))
 - Updated design on the "Buy" screen. ([#31384](https://github.com/brave/brave-browser/issues/31384))
 - Updated design on the "Account Details" page. ([#31617](https://github.com/brave/brave-browser/issues/31617))
 - Updated design on the "Accounts" tab. ([#31432](https://github.com/brave/brave-browser/issues/31432))
 - Updated design on the "Visible Assets" modal. ([#31389](https://github.com/brave/brave-browser/issues/31389))
 - Updated Stripe logo and description. ([#32226](https://github.com/brave/brave-browser/issues/32226))
 - Updated NFT pinning eligibility text. ([#30550](https://github.com/brave/brave-browser/issues/30550))
 - Merged IPFS DNSLink and IPFS redirect settings into a single setting. ([#31097](https://github.com/brave/brave-browser/issues/31097))
 - Removed "Network" and "Account" groups with zero balance from display on the "Portfolio" page. ([#31680](https://github.com/brave/brave-browser/issues/31680))
 - Fixed Solana DApps to disconnect when permission is revoked. ([#24974](https://github.com/brave/brave-browser/issues/24974))
 - Fixed manually added assets not being added to the deposit list. ([#31889](https://github.com/brave/brave-browser/issues/31889))
 - Fixed wallet panel opening and closing on Magic Eden. ([#31853](https://github.com/brave/brave-browser/issues/31853))
 - Fixed issue where all tokens weren't returned when restarting the browser directly into deposit screen. ([#31669](https://github.com/brave/brave-browser/issues/31669))
 - Fixed "Portfolio" page to retain the state of account list when page is reloaded or UI refreshes. ([#31249](https://github.com/brave/brave-browser/issues/31249))
 - Fixed inability to view NFT details when listed under hidden NFTs. ([#31208](https://github.com/brave/brave-browser/issues/31208))
 - Fixed assets being sorted by global level instead of group level on the "Portfolio" page. ([#31602](https://github.com/brave/brave-browser/issues/31602))
 - Fixed network selector background. ([#31459](https://github.com/brave/brave-browser/issues/31459))
 - Fixed "Portfolio" token list disappearing from view when "Visible assets" modal is displayed. ([#31275](https://github.com/brave/brave-browser/issues/31275))
 - Fixed overlap on the "Token details" menu when the token graph is loading. ([#31263](https://github.com/brave/brave-browser/issues/31263))

### Rewards

 - Added ZebPay as new custodial account provider for Brave Rewards (India only). ([#32036](https://github.com/brave/brave-browser/issues/32036))
 - Implemented “Manage Brave Ads” on the brave://rewards page. ([#30637](https://github.com/brave/brave-browser/issues/30637))

### General

 - Added Speedreader options for themes, fonts, and text size. ([#29075](https://github.com/brave/brave-browser/issues/29075))
 - Added brave://flags/#brave-adblock-scriptlet-debug-logs flag for filter authors. ([#31438](https://github.com/brave/brave-browser/issues/31438))
 - Enabled download protection allow list. ([#26183](https://github.com/brave/brave-browser/issues/26183))
 - Improved vertical tab animation. ([#30897](https://github.com/brave/brave-browser/issues/30897))
 - Improved sidebar slide animation. ([#25382](https://github.com/brave/brave-browser/issues/25382) & [#21992](https://github.com/brave/brave-browser/issues/21992))
 - Updated "lock" icon to "tune" icon in address bar. ([#31642](https://github.com/brave/brave-browser/issues/31642))
 - Updated brave://settings page to load in a new tab when accessed via the settings button in the sidebar. ([#31663](https://github.com/brave/brave-browser/issues/31663))
 - Updated "Learn more" link on the "Lookalike URL" popup. ([#31396](https://github.com/brave/brave-browser/issues/31396))
 - Updated cosmetic filtering to force aggressive blocking on YouTube. ([#30896](https://github.com/brave/brave-browser/issues/30896))
 - Updated brave://flags/#brave-adblock-cookie-list-default to be enabled by default. ([#29986](https://github.com/brave/brave-browser/issues/29986))
 - Removed known tracking parameters "mtm_cid" and "pk_cid" from URLs. ([#31084](https://github.com/brave/brave-browser/issues/31084))
 - Fixed the New Tab Page displaying the same background image in certain cases. ([#32359](https://github.com/brave/brave-browser/issues/32359))
 - Fixed URL query filter regression caused by brave://flags/#brave-domain-block-1pes. ([#32462](https://github.com/brave/brave-browser/issues/32462))
 - Fixed "Expires" property in some Adblock lists is not being read and set properly. ([#31238](https://github.com/brave/brave-browser/issues/31238))
 - Upgraded Chromium to 117.0.5938.62. ([#32945](https://github.com/brave/brave-browser/issues/32945)) ([Changelog for 117.0.5938.62](https://chromium.googlesource.com/chromium/src/+log/116.0.5845.188..117.0.5938.62?pretty=fuller&n=1000))

## [1.57.64](https://github.com/brave/brave-browser/releases/tag/v1.57.64)

 - Upgraded Chromium to 116.0.5845.188. ([#32911](https://github.com/brave/brave-browser/issues/32911)) ([Changelog for 116.0.5845.188](https://chromium.googlesource.com/chromium/src/+log/116.0.5845.180..116.0.5845.188?pretty=fuller&n=1000))

## [1.57.62](https://github.com/brave/brave-browser/releases/tag/v1.57.62)

 - Upgraded Chromium to 116.0.5845.180. ([#32765](https://github.com/brave/brave-browser/issues/32765)) ([Changelog for 116.0.5845.180](https://chromium.googlesource.com/chromium/src/+log/116.0.5845.163..116.0.5845.180?pretty=fuller&n=1000))

## [1.57.57](https://github.com/brave/brave-browser/releases/tag/v1.57.57)

### Web3

 - Fixed broken "Send" on BNB Chain. ([#32291](https://github.com/brave/brave-browser/issues/32291))

### General

 - Added "Fetch VPN State" under brave://skus-internals. ([#32030](https://github.com/brave/brave-browser/issues/32030))
 - [Security] Validated Wayback Machine URL before navigation as reported on HackerOne by xiaoyinl. ([#32395](https://github.com/brave/brave-browser/issues/32395))
 - [Security] Cleared sensitive information from URL before sending to Wayback Machine as reported on HackerOne by xiaoyinl. ([#32385](https://github.com/brave/brave-browser/issues/32385))
 - Fixed delta update files not being code signed on Windows. ([#31977](https://github.com/brave/brave-browser/issues/31977))
 - Upgraded Chromium to 116.0.5845.163. ([#32587](https://github.com/brave/brave-browser/issues/32587)) ([Changelog for 116.0.5845.163](https://chromium.googlesource.com/chromium/src/+log/116.0.5845.114..116.0.5845.163?pretty=fuller&n=1000))

## [1.57.53](https://github.com/brave/brave-browser/releases/tag/v1.57.53)

### Web3

 - Added support for "Swap" on Base. ([#32235](https://github.com/brave/brave-browser/issues/32235))

### General

 - [Security] Fixed browser crash as reported on HackerOne by 0xc4gr1. ([#32425](https://github.com/brave/brave-browser/issues/32425))
 - [Security] Fixed browser crash as reported on HackerOne by neeythann. ([#32449](https://github.com/brave/brave-browser/issues/32449))
 - Fixed missing "Open Guest profile" keyboard shortcut. ([#32268](https://github.com/brave/brave-browser/issues/32268))
 - Fixed issue where Brave would not relaunch via the taskbar icon in certain cases on Windows. ([#32309](https://github.com/brave/brave-browser/issues/32309))
 - Fixed issue where permission dialog was not working when quickly selecting "Allow" or "Block" after changing "Remember my decision" drop down value. ([#32258](https://github.com/brave/brave-browser/issues/32258))
 - Upgraded Chromium to 116.0.5845.114. ([#32451](https://github.com/brave/brave-browser/issues/32451)) ([Changelog for 116.0.5845.114](https://chromium.googlesource.com/chromium/src/+log/116.0.5845.96..116.0.5845.114?pretty=fuller&n=1000))

## [1.57.49](https://github.com/brave/brave-browser/releases/tag/v1.57.49)

 - Fixed startup crash on Windows caused by adding a non-existent or empty custom filter list. ([#32301](https://github.com/brave/brave-browser/issues/32301))

## [1.57.47](https://github.com/brave/brave-browser/releases/tag/v1.57.47)

### Web3

 - Added Stripe Onramp for US users. ([#31397](https://github.com/brave/brave-browser/issues/31397))
 - Added auto discovery of NFTs on all user added networks. ([#30976](https://github.com/brave/brave-browser/issues/30976))
 - Added auto discovery of POAPs. ([#30977](https://github.com/brave/brave-browser/issues/30977))
 - Added "Filters and display settings" modal for the "Portfolio" page. ([#30496](https://github.com/brave/brave-browser/issues/30496))
 - Added "Group by" option to the "Filters and display settings" modal on the "Portfolio" page. ([#30753](https://github.com/brave/brave-browser/issues/30753))
 - Added v2 headers into Brave Wallet. ([#30825](https://github.com/brave/brave-browser/issues/30825) & [#30583](https://github.com/brave/brave-browser/issues/30583))
 - Added caching for NFT metadata responses. ([#29532](https://github.com/brave/brave-browser/issues/29532))
 - Added contract address and tokenId parameters to the "Send" page URL. ([#30547](https://github.com/brave/brave-browser/issues/30547))
 - Added "Help Center" link next to "Privacy Policy" link on the "Swap" page. ([#30372](https://github.com/brave/brave-browser/issues/30372))
 - Implemented optimized Solana token balances fetcher. ([#30584](https://github.com/brave/brave-browser/issues/30584))
 - Improved Brave Wallet panel performance. ([#30772](https://github.com/brave/brave-browser/issues/30772))
 - Updated Brave Wallet to translate FEVM addresses to f410 addresses and allow choosing existing FEVM address as recipient. ([#30403](https://github.com/brave/brave-browser/issues/30403))
 - Updated Brave Wallet to support sending f1 to typed f4 addresses. ([#30401](https://github.com/brave/brave-browser/issues/30401))
 - Removed unnecessary price calls when hiding/unhiding NFTs. ([#30925](https://github.com/brave/brave-browser/issues/30925))
 - Removed scroll from import accounts screen. ([#30939](https://github.com/brave/brave-browser/issues/30939))
 - Fixed inability to sign "Swap" transactions on Solana DApps. ([#32109](https://github.com/brave/brave-browser/issues/32109))
 - Fixed "IPFS" badge being incorrectly displayed in the URL bar on non-IPFS sites. ([#31145](https://github.com/brave/brave-browser/issues/31145))
 - Fixed slow Brave Wallet panel load time. ([#22714](https://github.com/brave/brave-browser/issues/22714))
 - Fixed "Back" button breaking the UI on "Asset Details" page in certain cases. ([#30995](https://github.com/brave/brave-browser/issues/30995))
 - Fixed inability to create ETH account with Brave Wallet. ([#30809](https://github.com/brave/brave-browser/issues/30809))
 - Fixed "Activity" route not being persisted after Brave Wallet is unlocked. ([#31111](https://github.com/brave/brave-browser/issues/31111))
 - Fixed account transactions not being displayed on the activity panel view. ([#30780](https://github.com/brave/brave-browser/issues/30780))
 - Fixed "Activity" tab not auto-updating in certain cases. ([#28800](https://github.com/brave/brave-browser/issues/28800) & [#30450](https://github.com/brave/brave-browser/issues/30450))
 - Fixed "eth_signTransaction" to use the correct network for display. ([#28564](https://github.com/brave/brave-browser/issues/28564))
 - Fixed incorrect token symbol being displayed in "Activity" tab for Swap transactions. ([#30447](https://github.com/brave/brave-browser/issues/30447))

### Rewards

 - Implemented new rewards onboarding UI and flow. ([#30308](https://github.com/brave/brave-browser/issues/30308))
 - Updated "Estimated Earnings" indicator to display a monthly payout range. ([#30351](https://github.com/brave/brave-browser/issues/30351))

### General

 - Added support for "Forget by Default" browsing mode. ([#26465](https://github.com/brave/brave-browser/issues/26465))
 - Added the ability to resize sidebar. ([#30808](https://github.com/brave/brave-browser/issues/30808))
 - Added support for overriding eTLD+1 exceptions from default adblock filter lists. ([#20426](https://github.com/brave/brave-browser/issues/20426))  
 - Added farbled weights to Accept-Language headers' service workers. ([#29372](https://github.com/brave/brave-browser/issues/29372))
 - Added brave://flags/#brave-override-download-danger-level flag to disable download warnings when Safe Browsing is disabled. ([#28917](https://github.com/brave/brave-browser/issues/28917))
 - Added the ability to dismiss the end of support message on both macOS 10.13 and 10.14. ([#32129](https://github.com/brave/brave-browser/issues/32129))
 - Improved text on domain blocking interstitial page. ([#30142](https://github.com/brave/brave-browser/issues/30142))
 - Improved scrolling for vertical tabs by enabling sticky pinned tabs by default. ([#30761](https://github.com/brave/brave-browser/issues/30761))
 - Moved "Improve search suggestions" setting to be under brave://settings/search. ([#30878](https://github.com/brave/brave-browser/issues/30878))
 - Updated VPN toolbar button style. ([#30930](https://github.com/brave/brave-browser/issues/30930))
 - Removed known Hive email trackers "h_sid" and "h_slt" from URLs. ([#30731](https://github.com/brave/brave-browser/issues/30731))
 - Fixed delta updates on Windows. ([#30748](https://github.com/brave/brave-browser/issues/30748))
 - Fixed incorrect VPN button state when credentials are refreshed. ([#30881](https://github.com/brave/brave-browser/issues/30881))
 - Fixed settings sidebar disappearing on narrow screen widths. ([#24352](https://github.com/brave/brave-browser/issues/24352))
 - Fixed restored new tab not displaying the selected extension layout. ([#30890](https://github.com/brave/brave-browser/issues/30890))
 - Fixed uneditable red URLs appearing in the URL bar during autocomplete. ([#28198](https://github.com/brave/brave-browser/issues/28198))
 - Fixed custom filter lists in shields not respecting the "Expires" field. ([#17909](https://github.com/brave/brave-browser/issues/17909))
 - Upgraded Chromium to 116.0.5845.96. ([#32241](https://github.com/brave/brave-browser/issues/32241)) ([Changelog for 116.0.5845.96](https://chromium.googlesource.com/chromium/src/+log/115.0.5790.171..116.0.5845.96?pretty=fuller&n=1000))

## [1.56.20](https://github.com/brave/brave-browser/releases/tag/v1.56.20)

### Web3

 - Fixed missing fee estimate for EIP-1599 transactions on zksync Mainnet. ([#31959](https://github.com/brave/brave-browser/issues/31959))
 - Fixed inability to remove custom networks under brave://settings/wallet/networks. ([#31953](https://github.com/brave/brave-browser/issues/31953))

### General

 - Fixed permissions for "BraveSoftware" folder on macOS. ([#30546](https://github.com/brave/brave-browser/issues/30546))
 - Fixed vertical tab scroll clamping on Linux. ([#31925](https://github.com/brave/brave-browser/issues/31925))
 - Fixed issue where tab content was displayed behind vertical tab after exiting full screen on Linux. ([#30629](https://github.com/brave/brave-browser/issues/30629))
 - Upgraded Chromium to 115.0.5790.171. ([#31682](https://github.com/brave/brave-browser/issues/31682)) ([Changelog for 115.0.5790.171](https://chromium.googlesource.com/chromium/src/+log/115.0.5790.138..115.0.5790.171?pretty=fuller&n=1000))

## [1.56.14](https://github.com/brave/brave-browser/releases/tag/v1.56.14)

 - Upgraded Chromium to 115.0.5790.114. ([#31867](https://github.com/brave/brave-browser/issues/31867)) ([Changelog for 115.0.5790.114](https://chromium.googlesource.com/chromium/src/+log/115.0.5790.102..115.0.5790.114?pretty=fuller&n=1000))

## [1.56.11](https://github.com/brave/brave-browser/releases/tag/v1.56.11)

 - Upgraded Chromium to 115.0.5790.102. ([#31773](https://github.com/brave/brave-browser/issues/31773)) ([Changelog for 115.0.5790.102](https://chromium.googlesource.com/chromium/src/+log/115.0.5790.98..115.0.5790.102?pretty=fuller&n=1000))

## [1.56.9](https://github.com/brave/brave-browser/releases/tag/v1.56.9)

### Web3

 - Added the ability to hide and unhide NFTs. ([#30367](https://github.com/brave/brave-browser/issues/30367))
 - Added the option to hide NFTs on the "Portfolio" page. ([#30345](https://github.com/brave/brave-browser/issues/30345))
 - Added sticky header for asset details screen. ([#30237](https://github.com/brave/brave-browser/issues/30237))
 - Added "Buy", "Send", "Swap", and "More" buttons to narrow view of "Portfolio" screen. ([#30148](https://github.com/brave/brave-browser/issues/30148))
 - Added empty state placeholder for NFTs when no NFTs are added. ([#30105](https://github.com/brave/brave-browser/issues/30105))
 - Added API support to accept "Chain_ID" and "Contract_Address" for ETH calls. ([#29983](https://github.com/brave/brave-browser/issues/29983))
 - Added NFT discovery support for "NonFungibleEdition" and "ProgrammableNonFungible" Solana token types. ([#29400](https://github.com/brave/brave-browser/issues/29400))
 - Added support for Phantom derivation paths for importing Solana hardware accounts. ([#29186](https://github.com/brave/brave-browser/issues/29186))
 - Added the ability to remove auto-discovered tokens. ([#28749](https://github.com/brave/brave-browser/issues/28749))
 - Added auto-discovery for Filecoin assets and accounts. ([#28002](https://github.com/brave/brave-browser/issues/28002))
 - [Security] Removed extra fields from "eth_signTypedData_v4" message as reported on HackerOne by matseq. ([#30354](https://github.com/brave/brave-browser/issues/30354))
 - Enabled Sardine On-ramp purchase option for all wallet users. ([#30333](https://github.com/brave/brave-browser/issues/30333))
 - Implemented updated design for the NFT details screen. ([#30286](https://github.com/brave/brave-browser/issues/30286))
 - Implemented discovery of Solana accounts when restoring a wallet from seed phrase. ([#22969](https://github.com/brave/brave-browser/issues/22969))
 - Moved "Portfolio" customization settings to the "Portfolio" sticky header. ([#30216](https://github.com/brave/brave-browser/issues/30216))
 - Updated UI for "Portfolio" settings. ([#30422](https://github.com/brave/brave-browser/issues/30422))
 - Updated Brave Wallet UI to show pending transactions in descending order. ([#28409](https://github.com/brave/brave-browser/issues/28409))
 - Updated Brave Wallet page scrolling and responsiveness. ([#30103](https://github.com/brave/brave-browser/issues/30103))
 - Updated asset discovery to automatically run when NFT discovery setting is enabled. ([#30141](https://github.com/brave/brave-browser/issues/30141))
 - Updated Brave Wallet side navigation bar. ([#30122](https://github.com/brave/brave-browser/issues/30122))
 - Updated Brave Wallet "Portfolio" graph layout. ([#29996](https://github.com/brave/brave-browser/issues/29996))
 - Updated default Brave Wallet auto lock setting to 10 minutes. ([#26362](https://github.com/brave/brave-browser/issues/26362))
 - Fixed Brave Wallet startup crash which occurred in certain cases. ([#31423](https://github.com/brave/brave-browser/issues/31423))
 - Fixed inability to connect wallet on GMX. ([#31629](https://github.com/brave/brave-browser/issues/31629))
 - Fixed duplicate networks being displayed in pre-loaded networks. ([#31063](https://github.com/brave/brave-browser/issues/31063))
 - Fixed Brave Wallet not returning correct selected address from the request account RPC call. ([#30802](https://github.com/brave/brave-browser/issues/30802))

### Brave Rewards

 - Added rounded corners to the Brave Rewards dropdown panel. ([#28622](https://github.com/brave/brave-browser/issues/28622))
 - Updated the "Verified Creator" blue checkmark icon. ([#28208](https://github.com/brave/brave-browser/issues/28208))
 - Updated Brave Rewards settings under brave://settings/rewards. ([#30302](https://github.com/brave/brave-browser/issues/30302))

### General

 - Added the ability to modify keyboard shortcuts under brave://settings/system/shortcuts. ([#30840](https://github.com/brave/brave-browser/issues/30840))
 - Added support for "Off-The-Record" mode. ([#28750](https://github.com/brave/brave-browser/issues/28750))
 - Added a link to the Safe Browsing support page accessible from the interstitial page and the question mark icon under brave://settings/security. ([#20514](https://github.com/brave/brave-browser/issues/20514))
 - [Security] Added support for Certificate Transparency. ([#22482](https://github.com/brave/brave-browser/issues/22482))
 - Updated Brave VPN connection to be removed when Brave is uninstalled on Windows. ([#30416](https://github.com/brave/brave-browser/issues/30416))
 - Updated sidebar to be displayed on the right by default. ([#30397](https://github.com/brave/brave-browser/issues/30397))
 - Removed unnecessary "Shields settings" label under site specific details page of brave://settings/content. ([#30208](https://github.com/brave/brave-browser/issues/30208))
 - Fixed crash when using side panel extensions. ([#31328](https://github.com/brave/brave-browser/issues/31328))
 - Fixed crash which occurred when opening a Private window from a Windows shortcut when a search extension is installed. ([#30305](https://github.com/brave/brave-browser/issues/30305))
 - Fixed login issue on https://login.live.com. ([#31196](https://github.com/brave/brave-browser/issues/31196))
 - Fixed cosmetic filtering unhiding heuristic. ([#30202](https://github.com/brave/brave-browser/issues/30202))
 - Fixed system theme change interfering with explicitly set Brave theme on Linux. ([#30766](https://github.com/brave/brave-browser/issues/30766))
 - Fixed aggressive vertical tab scrolling. ([#30627](https://github.com/brave/brave-browser/issues/30627))
 - Fixed issue where cosmetic filtering could not resolve relative URLs as first-party. ([#30062](https://github.com/brave/brave-browser/issues/30062))
 - Fixed pinned tabs being created in PWA windows. ([#29576](https://github.com/brave/brave-browser/issues/29576))
 - Fixed intermittent issue where Bookmarks menu items were not displayed in the application menu on macOS. ([#25644](https://github.com/brave/brave-browser/issues/25644))
 - Fixed debounced sites displaying a top-level document blocking interstitial. ([#22437](https://github.com/brave/brave-browser/issues/22437))
 - Upgraded Chromium to 115.0.5790.98. ([#31682](https://github.com/brave/brave-browser/issues/31682)) ([Changelog for 115.0.5790.98](https://chromium.googlesource.com/chromium/src/+log/114.0.5735.198..115.0.5790.98?pretty=fuller&n=1000))

