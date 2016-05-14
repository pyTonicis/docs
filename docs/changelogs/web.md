![SeAT](http://i.imgur.com/aPPOxSK.png)

# web change logs
Generated with: `git log --oneline --decorate`

### 1.0.25
```
168bb3e (tag: 1.0.25) Version Bump
aee17af Add ability to force a minimum API access mask.
5101767 Start adding search functionality
b8ac4fb Remove accountid as it is not useful data
8604036 Fix eveseat/seat#81 by validating for numeric instead of integers
e1cd641 Fix eveseat/seat#78 by adding a link to view one mail only
60727e4 Warn if the default admin contact is still set. Ref eveseat/seat#77
a5d1f8f Fix eveseat/seat#65 by setting the key_id in the model
9884772 fix reinforcement time using API stateTimeStamp (#24)
```

### 1.0.24
```
c20194b (tag: 1.0.24) Version Bump
eac101f CS Fixes
f6e3186 Small refactoring and CS fixes
9997914 Adding Corporation Wallet Ledger (#23)
```
### 1.0.23
```
954c178 (tag: 1.0.23) Version Bump
498b868 Fix eveseat/seat#70 by ignoring the current users email in the constraint
8422602 Fix eveseat/seat#57 by adding missing language strings
```
### 1.0.22
```
cc8019a (tag: 1.0.22) Version Bump
0f02f88 Fix eveseat/seat#59 by adding a unique validation constraint
c69fa2f Add button to easily re-enable keys
```
### 1.0.21
```
70783d8 (tag: 1.0.21) Version Bump
c9188b7 Fix eveseat/seat#60 by using `firstOrNew` instead of create
98b9679 Fix eveseat/seat#51 by always showing the pagination
```
### 1.0.20
```
e2056a1 (tag: 1.0.20) Version Bump
92986b7 Remove pcntl requirement
ad5f515 Merge pull request #21 from warlof/french
```
### 1.0.19
```
f212c78 (tag: 1.0.19) Version Bump
d5376f9 Update Copyright
39c8243 Subclass the bouncers
afb0be5 Add a People Groups feature
17c4f3e Set queue status update time via configuration
5d30ff0 Fix eveseat/seat#48 by adding data-order attributes
530c268 Add a check for loaded modules and php version
c84baaa Merge pull request #18 from warlof/ticket38
e4e1fd0 Merge pull request #20 from warlof/ticket43
94e470d (origin/pr/18) Fix wishlist #38 eveseat/seat#38
21a3bb3 (origin/pr/20) Fix issue eveseat/seat issues#43 - Update calc formula - Adding ceil in order to get round item unit (ccp like)
274409b Use league/csv to parse CSV's instead of the homebrew
741755d Remove unnecessary re-fetch of model data
b7ff1a2 Fix eveseat/seat#39 by changing ownership of an existing key.
8fcc13e Remove footer. Datatables will count the keys
b357826 Code formatting fixes
d5f58de Merge pull request #19 from Cynabal/master
7a78e2f Merge pull request #17 from warlof/french
9d2ab0f (origin/pr/19) Update seat.php
86da25f (origin/pr/17) New translation according to v1.0.18
```
### 1.0.18
```
69239bf (tag: 1.0.18) Version Bump
33470ce Allow packages to hook into corporation menus
24c9f1d Only attempt to read package menus if they are defined
3b7ecad Allow packages to hook into character menus
bac4a6e Add Datatables to starbase summary
```
### 1.0.17
```
ec9d5c8 (tag: 1.0.17) Version Bump
aaaac36 Fix eveseat/seat#29
6de7e1e Add Datatables for tables.
```
### 1.0.16
```
075784c (tag: 1.0.16) Version Bump
b688c4f Add planet type icons
54ccdec Add corporation Pocos view
```
### 1.0.15
```
bbede7b (tag: 1.0.15) Version Bump
63f308a Load starbase modules via Ajax calls
c0f48df Display page render time
```
### 1.0.14
```
3f8587c (tag: 1.0.14) Version Bump
14d87b4 Merge pull request #13 from warlof/ticket5
d412b7e Excluse Towers themselves from module views
98a8e19 Use a macro for progressbar generation
c0e9ce3 Remove unused variables
22932b4 Refactor Starbase views mostly for performance reasons
0cefaac fix issue #5 about labels display on neutral and negative standing
```
### 1.0.13
```
936e8b8 (tag: 1.0.13) Fix a assets check, add missing string and Version Bump
```
### 1.0.12
```
7bdbf10 (tag: 1.0.12) Version Bump
6c365ad Specify versions with ~
3f604e2 Merge pull request #11 from warlof/french
c1f4657 add new translations according to recent commits (for 1.0.12)
ed485b3 Move strontium usage to its own string for easier translation
64a6f86 Take into account bonusses silo/coupling array capacities
488fd3b Merge pull request #8 from warlof/unknown-item
cd66a8a Add Starbase details views
f9dc521 fix issue #9
9f74d1c Add more details about starbases
7e67371 First pass at adding starbase views
9496188 Merge pull request #6 from warlof/french
2491e69 Translate SeAT in french according to 1.0.11
f5fa4e3 Show timestampts and paginate wallet info
c6b4311 Fix eveseat/seat#15
```
### 1.0.11
```
ca67d0a (tag: 1.0.11) Version Bump
78da260 Add ability to view corporation bookmarks
eda1260 Add ability to view character bookmarks
8e1285e Add ability to view character channels
```
### 1.0.10
```
5aebf1e (tag: 1.0.10) Allow French to be chosen and Version Bump
dae1719 Merge pull request #5 from warlof/french
6e827ae Translate SeAT in french according to 1.0.9
```
### 1.0.9
```
9e4cd79 (tag: 1.0.9) Add account info check and Version Bump
bfaabe2 Merge pull request #4 from freedenizen/master
d802b98 add updated_at timestamps to Character and Corporation Sheet summary
```
### 1.0.8
```
0ece0ce (tag: 1.0.8) Version Bump
616067c Check if we have data before attempting to display
99c14a3 Fix eveseat/seat#10
```
### 1.0.7
```
660b6fa (tag: 1.0.7) Version Bump
b65aa7e Remove URI scheme
639b3fb Add missing language definition for view
```
### 1.0.6
```
2042098 (tag: 1.0.6) Version Bump
83a7ea8 Add Afrikaans language support
0039045 Add ability to select a preferred language
30a71e6 Update langauge strings
2956a15 Resolve contract issuerID's to names
36ea925 Apply number() to a few values
40e5c24 Add ability to view profile login/logout history
a8e93d7 Add for user password resets
81682c4 Add recipient info into the mail timeline
cc141c8 Add id-to-name helper
6999007 Add X-CSRF Token for ajax calls
6915fec Add the mail timeline view
5ade565 Add ability to view character email
```
### 1.0.5
```
df6ddae (tag: 1.0.5) Version Bump
14bc397 Add ability to set an admin contact
5e6498b Add links to external services
f819124 Show output of jobs
070c232 Show eveapi errors status
80775e2 Allows superusers to transfer keys to other owners
```
### 1.0.4
```
4aab9b8 (tag: 1.0.4) Version Bump
```
### 1.0.3
```
bc8e6eb (tag: 1.0.3) Start something for a dashboard
0238e32 Update README.md
73d415d Add optional Google Two-Factor TOTP support.
84723ff Merge pull request #3 from Cynabal/patch-1
2d98ead Update add.blade.php
```
### 1.0.2
```
7fcac57 (tag: 1.0.2) Version Bump
020c885 Add notifications version
f9fdaf6 Dont force packages to set a permission
5d1bb8c Add email notifications setting and new email templates
4bade0d Auto update copyright year
9eba303 Add WebUI to manage schedules
```
### 1.0.1
```
4598815 (tag: 1.0.1) Version Bump
2c683ba Dont force a package to have a sub-menu
6c13e32 Resolve menu routes in the sidebar view.
e8f3237 Add api version display
0f6d4ec First pass in allowing packages to add menu items
fe117ce Add hasRole() method
be056a9 Fix #2
```
### 1.0.0
```
e885f07 (tag: 1.0.0) Style fixes and version Bump
fddc5ba Add SeAT Settings Page with registration toggle
30b2b9c Add more settings options
bb6e8ed Add ability to change SeAT theme.
8dbb713 Read skin ccs filename from settings()
67d823c Read some values from settings
91872a1 Remove unused HTML and fix brand route
3ec66f3 Reduce icon size and add corp icons
e78c62f Add more complete corp security views
13f6c9d Add ability to view corp member tracking
```
### 1.0-pre-alpha
```
6332cd7 (tag: 1.0-pre-alpha) Update README
a48340a Login using names instead of emails
2dfdc27 Add ability to view corp wallet transactions
06c4741 Add ability to view corp wallet journals
97547a7 Add ability to view corp standings
1a825e0 Add ability to view corp market orders
bab5d6a Add ability to view corp killmails
26923cc Add ability to view corporation industry jobs
fc43803 Add ability to view corporation contracts
a386881 Add ability to view corp contacts
110b142 Add ability to view corporation assets
2b9dd85 Add ability to view corp summary
0bf5bdc First work on corporation views.
5114d4f Resolve a trait method conflict
5eaffdc Add ability to mass import keys via CSV files
17feb08 Add ability to view character standings
797c9f0 Add ability to view character research info
771ee34 Add ability to view character PI
0fcb7de Add ability to view character market orders
a6b7ac6 Add ability to view character industry
c020c36 Small UI refactor to make it cleaner
0d5e18a Add character contract view
f36e34b Add ability to view character killmails
45e8dd5 Link to character details
08d1d48 Add character contacts view
dc3a396 Add character calendar view
085368f Add character notifications view
04ca0ee Add filter rules.
ccc5ad2 Add Character Assets View
c748d29 Add table-responsive
9aaa7ae Add Character Mail View
f046272 Add Character Wallet Transaction View
1ae69e0 Add Character Wallet Journal View
814a95d Rename method from EveRepository
5d9cfc1 Add Implants, Jump Fatigue and Clone info
ac83d39 Minor formatting changes
3631b89 Re-arrange character details layout
e23a153 Add more character sheet info and shuffle a few things around
c414bb2 Create a base view for character detail views
d3fc448 Add Character Skills view
51caf72 Add Security logging and viewing abilities
7debd56 Start the Character Viewer
5bfbed0 Small responsive fixes
4cf03ed Add All Characters View
51ccf46 Add hasAny()
12e05de Split permissions into categories
50a68ab Add a view into the Job Queue as well as some management
0da342b Add live queue status updates
b9df4c4 Fix cases where keys with missing info would throw errors
9faffab Remove usage of the Redirect Facade
2250508 Add ability to manually start a job update
3e34b3e Add key detail viewer and introduce the keybouncer
85bf567 Add ability ti list and delete API keys
2fe3d76 Add lazy image loading support
ee21c49 Style fixes
1de991a Add ability to add new Api Keys
358ba7f Make sidebar permissions aware
41190e6 Introduce the Bouncer and hes Clipboard 🚪
c2edc6b Use auth() helper instead of Auth Facade
2a864dc Fix some inconsistency with edit/updater user lang
e473bba Swap input for has to read better
5e65509 Allow for users to be quick added
89ca4e1 Allow for the account status to be filled
05e6019 Resize grid to match other configuration views
fdeb2cc Rename menu entry to match page title
7a03e34 Complete the impersonation feature
6195979 Add ability to delete users
0675ef9 Cleanup when a user is deleted
4c58659 Allow for users to be modified
a3f1882 Add a basic summary of user roles and affiliations
f03f872 Localize flash messages on perm/role changes
679b020 Fix typo in affiliation form request validator
2e656a8 First iteration of Acl methods and web structuring.
e8c4343 Highlight submenu items based on URL match
b6cd2b9 Have the sidebar honor the Locale
1f91ef0 Add view composer to build the sidebar menu
3425769 Add a User view composer
3e72326 Restructure Service Provider
4aa96f5 Fix duplicate 'reset' translation key
1160deb Use class property
22c7747 Add password reset functionality
9377f67 Add README
f16a71d Start web interface
3f15794 Initial commit
```