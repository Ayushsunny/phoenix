# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.7.0](https://github.com/EdwardMoyse/phoenix/compare/v1.6.1...v1.7.0) (2021-04-21)


### Bug Fixes

* **event-display:** attempt to improve the output of the track extension by removing close hits ([5bdc562](https://github.com/EdwardMoyse/phoenix/commit/5bdc5623a2c4ef01a97143d12d9c396dbc57cfa3))
* **event-display:** fix drawing of hits ([db3ca8b](https://github.com/EdwardMoyse/phoenix/commit/db3ca8b671bf2fa6bdf2831b8b5641cff74cf5a8))
* **event-display:** handle older json hit format again ([edcd567](https://github.com/EdwardMoyse/phoenix/commit/edcd56770fcb865d39592cb3f4d130cd26b3919a))


### Features

* **app:** option for custom import handlers ([99b161e](https://github.com/EdwardMoyse/phoenix/commit/99b161e76109fb2b99031a35ac72fbe31596f44b))
* **app:** support for importing with LHCb loader ([8c6bd89](https://github.com/EdwardMoyse/phoenix/commit/8c6bd89bafcd3f4123365f36f36f49d83f4352d8))





## [1.6.1](https://github.com/HSF/phoenix/compare/v1.6.0...v1.6.1) (2021-04-19)


### Bug Fixes

* **app:** update three.js for phoenix-ui-components ([6f5af5e](https://github.com/HSF/phoenix/commit/6f5af5edd5450d7143bd94de00c2186bd3b8d87e))
* **event-display:** animation event with clipping because of maximum callstack reached ([e5d6639](https://github.com/HSF/phoenix/commit/e5d6639ca5698162160d4d64545916087dd5f066))





# [1.6.0](https://github.com/HSF/phoenix/compare/v1.5.0...v1.6.0) (2021-04-18)


### Bug Fixes

* **app:** add sphericalToCartesian method ([bbea6b0](https://github.com/HSF/phoenix/commit/bbea6b03023cc56b5572684ec3cfaeb8cf3f0e7f))
* **app:** consistent input styling and fix share icon ([2e3455d](https://github.com/HSF/phoenix/commit/2e3455dd58c2c6f6bd0018651073a52f46716de4))
* **app:** event selection should show current event ([a65d8ac](https://github.com/HSF/phoenix/commit/a65d8ac2feebf140181f20a81098b6174212ae32))
* **app:** improve icons svg code ([d944837](https://github.com/HSF/phoenix/commit/d944837b0ba1c97ef8441599b6447b7ffbd56aec))
* **app:** revert added URL options and UI components package.json ([96f0649](https://github.com/HSF/phoenix/commit/96f06498b58a87e2fa035e94bb76b05f13aaaa75))
* **app:** update the ATLAS default configuration ([eadbd59](https://github.com/HSF/phoenix/commit/eadbd59bb674af2d23cf0fc32b56c3483c12953b))
* **event-display:** add back in geometrical limits for clusters ([0b95e5b](https://github.com/HSF/phoenix/commit/0b95e5b9263442df35f0af6f88694e7e5ee90e90))
* **event-display:** add eta and phi cuts for tracks ([f8a0080](https://github.com/HSF/phoenix/commit/f8a0080b3ddd8ca79ff49ae1aa1faab66b6b4e56))
* **event-display:** add missing docs ([c9781e5](https://github.com/HSF/phoenix/commit/c9781e5c0f876ea752a07178f072d82c45f50846))
* **event-display:** add missing documentation ([236bdf4](https://github.com/HSF/phoenix/commit/236bdf48b49ad0538461ac636bcbf130ef4349f9))
* **event-display:** calocluster eta position was wrong. ([66cbbc0](https://github.com/HSF/phoenix/commit/66cbbc03b5592775ee1971b0f181aaf5319636f3))
* **event-display:** cleanup JixeXML loader ([6a834e8](https://github.com/HSF/phoenix/commit/6a834e8bb3ebfbb67110e3f2e5459fc88c11d6e8))
* **event-display:** prettier fixes ([7528ee0](https://github.com/HSF/phoenix/commit/7528ee0c372c23418795866a3e041bbbb5e48d26))
* **event-display:** run prettier (again) ([f279898](https://github.com/HSF/phoenix/commit/f279898dd34fe2e79774611397e1860f761f0b54))
* **event-display:** update default configuration ([b21cd72](https://github.com/HSF/phoenix/commit/b21cd7291ecacafa3764e16fcbf0ed75d783027f))
* **event-display:** use BufferGeometry for CMS objects with new three.js update ([b8e88b8](https://github.com/HSF/phoenix/commit/b8e88b8f88ba543fdbe43c95edf9955efd570780))


### Features

* **app:** add calibration event for ATLAS ([8e6ffcb](https://github.com/HSF/phoenix/commit/8e6ffcb23c424d0e702a2c9eb0595be9fe33a20d))
* **app:** bind clipping state with UI menu ([40bbba0](https://github.com/HSF/phoenix/commit/40bbba07311d6c23b59d5d5409d190c2721bc395))
* **app:** complete dialog for share link and embed ([50c2584](https://github.com/HSF/phoenix/commit/50c2584107d132e8f7161c28ce4d88479e30c4ed))
* **app:** create component for shareable link constructor ([181dfa8](https://github.com/HSF/phoenix/commit/181dfa8b0d05888f89a27f4640466f9b57c06568))
* **app:** don't show hits in collection info ([c550a41](https://github.com/HSF/phoenix/commit/c550a41860c97a223527ecc2da4e66fb644a0844))
* **app:** fix link creation and improve link constructor ([2cedfec](https://github.com/HSF/phoenix/commit/2cedfeceb99b2d105bd603b8290b15fcfe5cdf0e))
* **app:** setup link share form ([b10bb7a](https://github.com/HSF/phoenix/commit/b10bb7aa14e373191bea6508d723c79c42c3f2b3))
* **event-display:** ability to remove geometry in Phoenix menu ([7d90d72](https://github.com/HSF/phoenix/commit/7d90d72e4c17776855946cc3a4d80149242c4a4f))
* **event-display:** ability to scale CaloClusters ([ff666e2](https://github.com/HSF/phoenix/commit/ff666e2c8455dbf0316e220f008bf45bccb22228))
* **event-display:** add ability to scale clusters in just one direction ([5a562ab](https://github.com/HSF/phoenix/commit/5a562ab6d7d8a228d5c69ea5454a597372810e48)), closes [#257](https://github.com/HSF/phoenix/issues/257)
* **event-display:** add coordinate helper ([57e438f](https://github.com/HSF/phoenix/commit/57e438fd8ba22e525595a72425d9000c82988dc1))
* **event-display:** add guidelines and simplify some coordinate transformations ([56f94f0](https://github.com/HSF/phoenix/commit/56f94f043b5bdf5e521c05e0bc058186c78270ad))
* **event-display:** Add missing energy ([6ef17d0](https://github.com/HSF/phoenix/commit/6ef17d07d8101da845b7efa0eb6698d99490bcd8))
* **event-display:** add opacity and wireframe for CaloClusters ([85d4a14](https://github.com/HSF/phoenix/commit/85d4a14ab1afc4518684128619824f46eda3aa9d))
* **event-display:** add support for HitLines ([455f536](https://github.com/HSF/phoenix/commit/455f536a201a3bd228ac2c97bec3f45b3e769620))
* **event-display:** add types for dat.GUI ([7632a18](https://github.com/HSF/phoenix/commit/7632a180c79d2cb04fc1ec82a580bc166ab9ed4a))
* **event-display:** create an active observable variable ([854e543](https://github.com/HSF/phoenix/commit/854e5439a1ebeba80940989a716338f1542984db))
* **event-display:** improve grid lines ([ca3cc2f](https://github.com/HSF/phoenix/commit/ca3cc2fa98c2bfc6f43bc6a459d7da273e6afc5a))
* **event-display:** improve handling of UI menus in UI manager ([b7a324a](https://github.com/HSF/phoenix/commit/b7a324a6643a2e191483d9925ea467afb933def8))
* **event-display:** introduce new URL options and improve handling them ([f7cd6b4](https://github.com/HSF/phoenix/commit/f7cd6b4b6059db82900bc9a0245d8365a5917e8b))
* **event-display:** JiveXML : add support for more hit types ([bbcdf0c](https://github.com/HSF/phoenix/commit/bbcdf0c3ae090b693fa5fa3cf02c78fe2c50bf16))
* **event-display:** keep state of event data folder on event switch ([b52282f](https://github.com/HSF/phoenix/commit/b52282ff038d081ed752ab6c85d08bcc7145c822))
* **event-display:** make Phoenix available in browser without a namespace ([5389282](https://github.com/HSF/phoenix/commit/5389282be8018191426da02140cd29dcdbf2b726))
* **event-display:** move opacity and wireframing to collection level ([6486982](https://github.com/HSF/phoenix/commit/6486982fbfdca3a8e51d05afd14804e86bb9fb14))
* **event-display:** Remove LineHits and use hits to extend tracks ([30b5160](https://github.com/HSF/phoenix/commit/30b5160ce9db8cbe800b3393271224a014b0aecf))
* **event-display:** restructure phoenix-event-display ([2e16371](https://github.com/HSF/phoenix/commit/2e163718ce32dd0713100f632127ac0a2cca8238))
* **event-display:** separate dat.GUI UI menu ([29093a2](https://github.com/HSF/phoenix/commit/29093a22737e3c9771dc4b5ca52569962b994771))
* **event-display:** separate Phoenix menu UI from UI manager ([5743adc](https://github.com/HSF/phoenix/commit/5743adcd4b6f3fb16dac3be6211450f2f04b94d3))
* **event-display:** split dat.GUI menu options ([45a0123](https://github.com/HSF/phoenix/commit/45a0123892092c9397a80b5c99bb9d5c156aa0b1))
* **event-display:** start splitting UI manager ([56ff275](https://github.com/HSF/phoenix/commit/56ff275013772e958818c3100165587aa244173f))
* **event-display:** use run and event number and file name for config json ([03a1de4](https://github.com/HSF/phoenix/commit/03a1de4056c8e9acb29307b2efb906ac7e782201))
* upgrade all packages except three.js ([8e2eff4](https://github.com/HSF/phoenix/commit/8e2eff4b58e02f19cefd3e02e7edf92a81474783))
* upgrade three.js except for CMSObjects ([0b2dd8a](https://github.com/HSF/phoenix/commit/0b2dd8a8860ed49feb16a247b52aa0b21452a251))






# [1.5.0](https://github.com/HSF/phoenix/compare/v1.4.1...v1.5.0) (2021-03-24)


### Bug Fixes

* **app:** clean index.html ([ebb2324](https://github.com/HSF/phoenix/commit/ebb2324fc32625ed55492817036542a55d3f5481))
* **event-display:** catch VR request session error ([d2874b8](https://github.com/HSF/phoenix/commit/d2874b8aed6f0647f5ccb11bfade1f9c1bc1f29c))
* **event-display:** fix jsroot loading root file ([8cbcaa5](https://github.com/HSF/phoenix/commit/8cbcaa5d2e4ba89940d65d217e302e7500305641))
* **event-display:** handle tracks with no positions ([3b1991c](https://github.com/HSF/phoenix/commit/3b1991c9789607beb69374bf963b8d49eea310b6))
* **event-display:** improve renderer init ([a8f8353](https://github.com/HSF/phoenix/commit/a8f83533970cfa9129ba015b5903eb7c832d7b94))
* **event-display:** remove optimize controls function ([266af04](https://github.com/HSF/phoenix/commit/266af044e8d719732bb2dc197ec8a7b3cadc00cd))
* **event-display:** remove redundant import ([359d353](https://github.com/HSF/phoenix/commit/359d3533d275f7871cc794a6c2ff13753618f9fa))
* **event-display:** use per physics object color and not collection color ([ac0c4f1](https://github.com/HSF/phoenix/commit/ac0c4f149c36568b5f172d24656c7d754df7b635))
* remove JSROOT source files from repo ([7bcd7ba](https://github.com/HSF/phoenix/commit/7bcd7bad7bca398242697828ae3189927ff37e89))


### Features

* **app:** ability to import ig archive in CMS ([9540af5](https://github.com/HSF/phoenix/commit/9540af5d08ab2867e6ef0496a1bd1e3215e91af7))
* **app:** add ability to import zip with both jivexml and json ([5d62da8](https://github.com/HSF/phoenix/commit/5d62da8aed3621adfff3f8a712e27ff6978efb22))
* **app:** Add more realistic geometry for ATLAS ([d207bad](https://github.com/HSF/phoenix/commit/d207bad4f72f9ae5e423c61fa7dc56eebc99c3b7))
* **app:** allow loading compressed jivexml (multiple files) ([d4f3cc7](https://github.com/HSF/phoenix/commit/d4f3cc7a7a5f8e5f2f7e94ce0cc99165debd9952))
* **app:** allow loading compressed json event data (multiple files) ([360fb20](https://github.com/HSF/phoenix/commit/360fb20d75f793131cf22471cf6a2db959f5c1f0))
* **app:** dont process zip through json or jivexml import ([17b4e85](https://github.com/HSF/phoenix/commit/17b4e8587ac7743b9c556c73fa3a48862e9ad4ef))
* **app:** dynamically define supported event formats for io import ([1449cbe](https://github.com/HSF/phoenix/commit/1449cbedec631f4c0d69ad35129c64a949e493e4))
* **app:** make event data io options configurable ([989ac0e](https://github.com/HSF/phoenix/commit/989ac0ec0a50b9130fc01613735eb1f3c4b226e4))
* add missed files in .dockerignore ([11af19c](https://github.com/HSF/phoenix/commit/11af19ce8c4612db3944bc35ff44b984aefeed67))
* update Dockerfile to reduce size ([8d81af2](https://github.com/HSF/phoenix/commit/8d81af2a0124a2913bb224333f821150dc23a5c0))
* **event-display:** resize canvas with window resize ([5ea04f1](https://github.com/HSF/phoenix/commit/5ea04f174b5adbe54af0aa4663466c5b6291c0a2))
* **event-display:** update to use CDN for JSROOT ([2fa310f](https://github.com/HSF/phoenix/commit/2fa310fc0171bd19e0ec1b75322eba6b532e5bfe))
* **event-display:** use latest version of JSROOT ([fbd584e](https://github.com/HSF/phoenix/commit/fbd584edb3dbfd436cdbe18a876c59ec05e43aa4))






## [1.4.1](https://github.com/HSF/phoenix/compare/v1.4.0...v1.4.1) (2021-02-26)

**Note:** Version bump only for package root





# [1.4.0](https://github.com/HSF/phoenix/compare/v1.3.0...v1.4.0) (2021-02-16)


### Bug Fixes

* **event-display:** disable keyboard controls when typing ([4f80bd6](https://github.com/HSF/phoenix/commit/4f80bd6c972f2e1291bc62015870ac9b08c077ef))
* **event-display:** improve object selection from uuid and label input ([3475836](https://github.com/HSF/phoenix/commit/3475836eacca1485f6dddab8dc049bbb605a5e27))
* **event-display:** persist toggle state of phoenix menu node children ([e96136b](https://github.com/HSF/phoenix/commit/e96136b8bade393d336a74c607db18d19d139e96))
* **event-display:** remove rollup config and fix globalThis usage ([e6f69a0](https://github.com/HSF/phoenix/commit/e6f69a0e47856dc38409eaea3030595fa5c3065d))


### Features

* **app:** ability to add label ([cccd3ed](https://github.com/HSF/phoenix/commit/cccd3ed22583dd9061e09a1c8cf455ee60db7a22))
* **app:** add label icon and form ([a65a83e](https://github.com/HSF/phoenix/commit/a65a83ece414ae86e5ed66bbb1f97a97a0bd09e7))
* **app:** put overlay widgets in a container ([2bd20a8](https://github.com/HSF/phoenix/commit/2bd20a8da319f92460baa873e35e0af2829f3cd7))
* **event-display:** ability to add 3D label text ([c9d4880](https://github.com/HSF/phoenix/commit/c9d4880c2ef97ee07f16a30ef17c80279c853de3))
* **event-display:** add labels configuration to dat.GUI menu ([d677089](https://github.com/HSF/phoenix/commit/d677089d49a5fedee4b23bcc690690decef5f8a2))
* **event-display:** add labels to UI configuration ([d90e3a6](https://github.com/HSF/phoenix/commit/d90e3a6435e869138417f2bff705f4fde4825d5a))
* **event-display:** add size and color options for labels ([3ce675f](https://github.com/HSF/phoenix/commit/3ce675f3da5db67a40f32be7f011c393a98055c2))
* **event-display:** better handling of labels object ([e10a68d](https://github.com/HSF/phoenix/commit/e10a68d91cb18e82debd470a2dff643b41031d85))
* **event-display:** complete setup with webpack for browser ([3f6367f](https://github.com/HSF/phoenix/commit/3f6367fa52cdb0b116b93428b03a97e4b816f094))
* **event-display:** complete support to save and load labels ([2219a3e](https://github.com/HSF/phoenix/commit/2219a3e60ef8bda46e4f1c6d1fa219a21e96451a))
* **event-display:** create a url options manager for url options ([fe0b2e6](https://github.com/HSF/phoenix/commit/fe0b2e66ff5485821620d53870a394d52cc1a460))
* **event-display:** create generic function for getting object position ([8d7b160](https://github.com/HSF/phoenix/commit/8d7b160b1e70df425f4626a5d3c89320d4571de4))
* **event-display:** delete label on empty value and change add label icon ([3756330](https://github.com/HSF/phoenix/commit/3756330d06c459662a0e99d447e5984ebea87e27))
* **event-display:** make label always look at camera ([0837334](https://github.com/HSF/phoenix/commit/08373349a7c5a47c10ec22a58bd6337823f02214))
* **event-display:** set up add label to object functions ([db261a6](https://github.com/HSF/phoenix/commit/db261a6fe5b770f912bef080f1ceec6374a81d08))
* **event-display:** setup webpack for browser bundle ([dc05ed9](https://github.com/HSF/phoenix/commit/dc05ed9cad08d99f2a2e8c27b97257a8d3ff11f1))
* **event-display:** support to hide widgets through URL ([cb2ec40](https://github.com/HSF/phoenix/commit/cb2ec4096b7cba0c1516d14b6f32e294673818a6))
* **event-display:** use optional chaining for hide widgets url option ([c991e54](https://github.com/HSF/phoenix/commit/c991e54dc4dbeb7a85228217317cda08835e5c16))
* **event-display:** Use types for phoenix menu configuration ([79e6d7c](https://github.com/HSF/phoenix/commit/79e6d7c17e4a78f9a571c0eba98eacf76906c029))
* **event-display:** working labels object ([60269f7](https://github.com/HSF/phoenix/commit/60269f78eb0c384bd628680c93ae94919b2d08d9))
* set up docker ([de312d9](https://github.com/HSF/phoenix/commit/de312d97e66d27e863ff4fbbb90f2b3897edffb7))
* Update Angular and all packages to latest ([f4c2e31](https://github.com/HSF/phoenix/commit/f4c2e31207e890436a6387e2e34ef31e3d0c48a6))





# [1.3.0](https://github.com/HSF/phoenix/compare/v1.2.0...v1.3.0) (2021-01-16)


### Bug Fixes

* **app:** fix PR status update ([64acd74](https://github.com/HSF/phoenix/commit/64acd748759024f8f908b6d9c4053119ad98a510))
* **app:** fix tugboat setup ([4398014](https://github.com/HSF/phoenix/commit/439801453a64d27fb432f8a85a7a4058fe768993))
* **app:** improve IO code ([a09be14](https://github.com/HSF/phoenix/commit/a09be1491f1357bd3c5925d6f6bba7d101dd6e94))
* **app:** make import words consistent ([08e771d](https://github.com/HSF/phoenix/commit/08e771d4bb76873ed6931f8aee485925c7f34889))
* **app:** minor test improvements ([8a0d5cf](https://github.com/HSF/phoenix/commit/8a0d5cf26ad06302ae7d6879863aad8dcd17e0ba))
* **app:** PR deployment status description update ([0e1210e](https://github.com/HSF/phoenix/commit/0e1210ecfdfa7c639528d5c9f4fa7bffcfb3d356))
* **app:** surge fixes ([613bfce](https://github.com/HSF/phoenix/commit/613bfce2734510504408f03b841ad4bbefff04c8))
* **app:** upgrade to ngx-slider ([6c9b928](https://github.com/HSF/phoenix/commit/6c9b9282fbb1832105dbbd1b54255b9f542ce859))
* **event-display:** assign the right name to geometry ([b7e8da0](https://github.com/HSF/phoenix/commit/b7e8da002548255b0c996ebc91a06918b5819281))
* **event-display:** code improvements ([f94c0e4](https://github.com/HSF/phoenix/commit/f94c0e40384ee95f22ba1a92938cf124a6d89a31))
* **event-display:** fix parsing of GLTF geometry ([dc5d489](https://github.com/HSF/phoenix/commit/dc5d489fd2b2730b9d235851c09baf86d88325d3))
* **event-display:** improve code for hiding tube tracks ([e9f1bc9](https://github.com/HSF/phoenix/commit/e9f1bc9ef454791e567cf83c886f055c4215423c))
* **event-display:** minor script fix ([5139c6e](https://github.com/HSF/phoenix/commit/5139c6e9e9a5a3029cf1e4a6b454c0f4d8cfb42a))
* **event-display:** remove color from obj file userdata ([8ba94e7](https://github.com/HSF/phoenix/commit/8ba94e76955b9d65688ee5aaabb6d4f2d0e854f2))
* **event-display:** revert jasmine spec files ([dc140dd](https://github.com/HSF/phoenix/commit/dc140ddf33b083577782f55f4c2a8187c9501d44))
* **event-display:** try fixing CMSLoader tests ([789da8b](https://github.com/HSF/phoenix/commit/789da8b352620d485e80271283f2a133cf7d3323))


### Features

* **app:** add link command to tugboat config ([d85a0a4](https://github.com/HSF/phoenix/commit/d85a0a414e49eafd404210e87ae1316e19073676))
* **app:** add tugboat config ([67d4c23](https://github.com/HSF/phoenix/commit/67d4c232225db1b7b07cab8ceae5d034e5a3bd12))
* **app:** check if surge available for deployment of PR ([9b4839d](https://github.com/HSF/phoenix/commit/9b4839d791112ff54c5a28a8b77d93240ada81b6))
* **app:** complete initial surge deployment set up ([3cb36a2](https://github.com/HSF/phoenix/commit/3cb36a280ccdbe3f2b1ff0e116fa50ecaadc9649))
* **app:** restyle IO options ([1542808](https://github.com/HSF/phoenix/commit/15428081d748d8e8f548c6d76ef46358d28c82be))
* **app:** set up PR deployment with surge ([520c644](https://github.com/HSF/phoenix/commit/520c6442663f9a8b0047e064d2c8f224d92300a6))
* **app:** support for importing ROOT geometry ([89adb25](https://github.com/HSF/phoenix/commit/89adb258182bf27a22748ddd14a3880de9a89af3))
* **event-display:** display size on selection ([6943f79](https://github.com/HSF/phoenix/commit/6943f792b2eb037dd4ab19b9dc806d75820b2249))
* **event-display:** hide tube tracks on zoom ([7d606b2](https://github.com/HSF/phoenix/commit/7d606b29214e9f080266ad13502fa1092605a00f))






# [1.2.0](https://github.com/9inpachi/phoenix/compare/v1.1.0...v1.2.0) (2020-12-06)


### Bug Fixes

* **app:** add missing icons to assets ([7256013](https://github.com/9inpachi/phoenix/commit/7256013e712f8d3fa62b7cbf54fb7bd42e25d725))
* **app:** change max value for energy cuts ([e9d2b17](https://github.com/9inpachi/phoenix/commit/e9d2b172b6f695ca3a0f9ee27aef3521d975de54))
* **app:** fix geometry demo code ([4ffbd9b](https://github.com/9inpachi/phoenix/commit/4ffbd9b0af6fb5d2500ee2b1612a723677221079))
* **app:** fix tests ([fa110c2](https://github.com/9inpachi/phoenix/commit/fa110c2f839985d2eab9540cd6138c68596d27ff))
* **app:** fix TrackML geometry ([640a6e3](https://github.com/9inpachi/phoenix/commit/640a6e3dea0029b5d484f1b1570018d1b2ef4108))
* **app:** loading state after everything else loads ([edef465](https://github.com/9inpachi/phoenix/commit/edef46591ba8951c2306d133d947e1351bf56746)), closes [#187](https://github.com/9inpachi/phoenix/issues/187)
* **app:** make ngOnInit async and await geom load ([298c075](https://github.com/9inpachi/phoenix/commit/298c07585b9b97bdc937be9eec08f60ee1d049bd)), closes [#187](https://github.com/9inpachi/phoenix/issues/187)
* **app:** make VR icon disabled not hidden ([8712753](https://github.com/9inpachi/phoenix/commit/87127539d62197d6414e76e9bb5a39512c422452))
* **app:** minor fixes for ss mode ([ac829ae](https://github.com/9inpachi/phoenix/commit/ac829ae1c70c780583d729ef6b871e4bf78a2b33))
* **app:** minor test fix ([73e2bf4](https://github.com/9inpachi/phoenix/commit/73e2bf437c4f72f962843a97e3a8d3abaaf2ca3a))
* **app:** renable trackML ([4016564](https://github.com/9inpachi/phoenix/commit/40165643555f7789c825c6ba1c9bc1aaf9afb6f4))
* **app:** revert phoenix-ui-components package.json ([640155b](https://github.com/9inpachi/phoenix/commit/640155b2c0b1164e7b2b5e1f033e61c846fee42d))
* **app:** use optional chaining for fullscreen in SS mode ([6234655](https://github.com/9inpachi/phoenix/commit/6234655c3a5030088991787e91ddb67d9201bcf8))
* **event-display:** add Edward's controller set up ([a6a1c19](https://github.com/9inpachi/phoenix/commit/a6a1c19d696aff6e6c239fef76dcd3c24f4897a1))
* **event-display:** changes to animation loop for VR ([37df19f](https://github.com/9inpachi/phoenix/commit/37df19f17b0f6d37229e95dacf295e388dcefbd1))
* **event-display:** finally fix VR completely ([4764196](https://github.com/9inpachi/phoenix/commit/4764196e4b64ee3a7d4ff0654373b893018e6e53))
* **event-display:** fix applying multiple cuts at the same time ([8f3e8e1](https://github.com/9inpachi/phoenix/commit/8f3e8e18f42c3f6092e7e89e73da4414e648879f))
* **event-display:** fix applying state for range slider ([c36a222](https://github.com/9inpachi/phoenix/commit/c36a222779a278f9aba6c774f3793e8fc44e0490))
* **event-display:** fix loading and add default view to experiments ([ab8feb4](https://github.com/9inpachi/phoenix/commit/ab8feb45ecd0fba4ae2eb32deb528763f166b5d3))
* **event-display:** initialize cuts with correct values ([e297c98](https://github.com/9inpachi/phoenix/commit/e297c984ecca0a8e0d1ac84389f8c3160b443bec))
* **event-display:** make it possible to flat shade ([dcf6cec](https://github.com/9inpachi/phoenix/commit/dcf6cec2556c4fb880682ac1a3559bfd44050822))
* **event-display:** optimal animation loop set up ([da3ead5](https://github.com/9inpachi/phoenix/commit/da3ead53b2b36e67a7d5604db5428b60ce93bffa))
* **event-display:** optimal render for effects manager ([1975d70](https://github.com/9inpachi/phoenix/commit/1975d701763acfe770a08ca9eba92bf46ae9e035))
* **event-display:** reset clipping on init ([029d526](https://github.com/9inpachi/phoenix/commit/029d526d9ae0bc6933fb6bc07e48efe6dcba2667))
* **event-display:** stop animation loop on home ([c39ecd3](https://github.com/9inpachi/phoenix/commit/c39ecd3d57744e5ad117de6cd0aafc2c81b5c58d))
* **event-display:** update configuration in tests ([18f8db2](https://github.com/9inpachi/phoenix/commit/18f8db2e7d9cf5ccbcf1111112d4fec0449fa087))


### Features

* **app:** add tests for screenshot mode toggle ([18f27c5](https://github.com/9inpachi/phoenix/commit/18f27c59457f1f149879bf300ccc25b57f949a0f))
* **app:** add toggle for screenshot mode ([22a1ec8](https://github.com/9inpachi/phoenix/commit/22a1ec8903ac80d72f564eca29e49d15cbd411ce))
* **app:** adding default configuration for ATLAS ([9b765c5](https://github.com/9inpachi/phoenix/commit/9b765c51dca9ef12c39ba79956b34e75320ddc12))
* **app:** component for toggling antialiasing ([5545d80](https://github.com/9inpachi/phoenix/commit/5545d80ea67a4d803c8c7839accd76f06b2a2fe8))
* **app:** enter fullscreen in screenshot mode ([70f139f](https://github.com/9inpachi/phoenix/commit/70f139fd23f5430b95aeb4741ff03b040cd40358))
* **app:** Get GeometryDemo working again ([8f91dbd](https://github.com/9inpachi/phoenix/commit/8f91dbd16dcb3648fd66db20051a911d4abf0835))
* **app:** hide overlays screenshot mode ([4fd0197](https://github.com/9inpachi/phoenix/commit/4fd0197a700240a1b40828b288e6bbb7d1b4d72f))
* **app:** make loader generic ([ff10477](https://github.com/9inpachi/phoenix/commit/ff10477b40fae8554813b283a644c6aeb421f88a))
* **app:** rename antialias toggle to performance and add icon ([5b3cbae](https://github.com/9inpachi/phoenix/commit/5b3cbae8171b5f2d0006de5991be0c32f97af4e4))
* **app:** set up performance mode with selection ([947f6bf](https://github.com/9inpachi/phoenix/commit/947f6bf2f4da25528de3ab3eeb44c579c084d9a6))
* **app:** support to start or deploy phoenix with a single event ([09003a2](https://github.com/9inpachi/phoenix/commit/09003a281337b98c32ac8f5542d6debebedd64b5))
* **app:** use event display loader in Angular component ([25b2a9d](https://github.com/9inpachi/phoenix/commit/25b2a9df57b48b0b372358f5350648e3b1b7e846))
* **event-display:** ability to add geometry to a menu folder ([30b0383](https://github.com/9inpachi/phoenix/commit/30b0383664419581a76457ab11189aa559fd911b))
* **event-display:** ability to initialize event display without init ([69d3f75](https://github.com/9inpachi/phoenix/commit/69d3f75360575c2202701e0ef28b1bdf0dec5e8a))
* **event-display:** add ability to add parametrised geometry ([04dc545](https://github.com/9inpachi/phoenix/commit/04dc545b3a65d990215ea0980b93ec01d8347a7c))
* **event-display:** add and set up loading manager ([5f0f942](https://github.com/9inpachi/phoenix/commit/5f0f9422156344c5e162cf882872ae9708d6c0bb))
* **event-display:** handle loading better ([9474565](https://github.com/9inpachi/phoenix/commit/9474565a2bc9b3764cb0970df14ed79a1d943a03))
* **event-display:** make loading functions return Promise for async await ([4262a1b](https://github.com/9inpachi/phoenix/commit/4262a1b42a8960e5e81df6bef304388e9d4ac26e))
* **event-display:** support for toggling antialiasing ([48130b2](https://github.com/9inpachi/phoenix/commit/48130b2c53a1c0a8d105f1e81ecf4f0146eb3763))
* **event-display:** use object to simplify configuration ([4b10452](https://github.com/9inpachi/phoenix/commit/4b10452a80aed8e67ddac5d550cc9fd15383bad3))





# [1.1.0](https://github.com/9inpachi/phoenix/compare/v1.0.2...v1.1.0) (2020-11-07)


### Bug Fixes

* **app:** accidentally committed modification to start script ([3a7564f](https://github.com/9inpachi/phoenix/commit/3a7564fea1656fe78f8fcf64e2d2d8f55cdacb0d))
* **app:** accidentally committed modification to start script ([720b991](https://github.com/9inpachi/phoenix/commit/720b991886220c8d9b86f4a3f2b7d7c36f8033d0))
* **app:** cut filter failed if value return was zero ([0a26fea](https://github.com/9inpachi/phoenix/commit/0a26fea050358e0444f6f257b74e9616ce2d0a91))
* **app:** cut should be pT, not mom ([73b7c27](https://github.com/9inpachi/phoenix/commit/73b7c2709bf829516d94e4cf7e90c96b0016fdaf))
* **app:** fix attribute pipe ([0980379](https://github.com/9inpachi/phoenix/commit/09803798a1e5bef8a02e004a63a671d666d0a56a))
* **app:** fix tests ([f87c587](https://github.com/9inpachi/phoenix/commit/f87c5876f5a7a83ef3f0a1cb71ff345b492f4263))
* **app:** fix tests ([fd5c475](https://github.com/9inpachi/phoenix/commit/fd5c4757c575a7c7a3980bd9a12e010e325fa683))
* **app:** fix tests 2 and add assets to phoenix-ui ([3527eb4](https://github.com/9inpachi/phoenix/commit/3527eb4dd91f79a016f3557b6b8b976f52d30307))
* **app:** Formatted correctly ([82aab70](https://github.com/9inpachi/phoenix/commit/82aab70624113b295d0922391c68dbf46eb89501))
* **app:** ignore ng libraries in lerna bootstrap ([eb699c1](https://github.com/9inpachi/phoenix/commit/eb699c1844221577c397764f11495a43a676dd61))
* **app:** pT should always be positive ([3918159](https://github.com/9inpachi/phoenix/commit/3918159781673071085f163ec33f5d346f6e255b))
* **app:** rename phoenix-ui to phoenix-ui-components ([bec982c](https://github.com/9inpachi/phoenix/commit/bec982c5b2361f8b5be99960d9239d6347a2ab86))
* **app:** style encapsulation for components ([e247c33](https://github.com/9inpachi/phoenix/commit/e247c3310a7be95c9d5b15492419dc54a6f11a89))
* **event-display:** add optional chaining to CMS event info (fixes tests) ([5283e9a](https://github.com/9inpachi/phoenix/commit/5283e9a5b52b79409f0aba6db1dbf144946d9d0c))
* **event-display:** fix geometry too big in overlay view ([c7a35db](https://github.com/9inpachi/phoenix/commit/c7a35db8ebbab1922a921425d1c8e9d643c88677))
* **event-display:** fix URL event not working with hash routes ([9eb21f5](https://github.com/9inpachi/phoenix/commit/9eb21f51bd5d21f14d3919def8347d94e4b8c30f))
* **event-display:** Formatted correctly ([b46c49f](https://github.com/9inpachi/phoenix/commit/b46c49f5358f0dc096de0e6698860c0bee132395))
* **event-display:** use optional chaining in CMS loader ([cfb1b6a](https://github.com/9inpachi/phoenix/commit/cfb1b6a9d49a1b812a6e7d569756a4e65899f5b7))
* **phoenix-app:** isolate styles to components ([75f8799](https://github.com/9inpachi/phoenix/commit/75f87997cb7b615dc23d91bf601a737595b945ba))
* **VR:** Fix bugged scene in VR mode ([9efd9ca](https://github.com/9inpachi/phoenix/commit/9efd9ca6cf814109a8901ce0d80eec90fc765c72))


### Features

* **app:** Add a deploy:atlas script. Use hashed routes. ([6716791](https://github.com/9inpachi/phoenix/commit/6716791035da1ec8d5dfc238462dd0476514b3ce))
* **app:** Add a deploy:atlas script. Use hashed routes. ([cf7e1fb](https://github.com/9inpachi/phoenix/commit/cf7e1fbce43f33a86697935136ea6d875b32ee36))
* **app:** change the ATLAS default event ([7953215](https://github.com/9inpachi/phoenix/commit/795321549ebe037e8550a043f746bc3c8cf6b4d6))
* **app:** create phoenix-ui module and fix tests ([aec60ae](https://github.com/9inpachi/phoenix/commit/aec60ae4805a4b7a6acaa02d2490fbda6e70ba82))
* **app:** generalised deploy script ([69962b8](https://github.com/9inpachi/phoenix/commit/69962b803aa964d3fa6ef1bf73f26d87ca1cf985))
* **app:** generalised deploy script ([790107a](https://github.com/9inpachi/phoenix/commit/790107a8a39c2bf10eefca26bee4f9460ab3a0e4))
* **app:** load event from URL query params ([25ea715](https://github.com/9inpachi/phoenix/commit/25ea715ff763f784e838f94f5fff9d87cced21b7))
* **app:** Make the experiment info panel draggable (HSF/phoenix[#157](https://github.com/9inpachi/phoenix/issues/157)) ([ef13974](https://github.com/9inpachi/phoenix/commit/ef139744e3b6b97712472d47873b1d04990b65ae))
* **app:** Option to load config from URL in ATLAS ([1906976](https://github.com/9inpachi/phoenix/commit/1906976f763dcb6d7748037e3f9cf4dd5796b230))
* **app:** refine phoenix-ui and fix test ([2b78c6c](https://github.com/9inpachi/phoenix/commit/2b78c6c51ab9df07b8bfdafad2be61bd5e26992d))
* **app:** Set the ATLAS defaultView ([e2dcfaf](https://github.com/9inpachi/phoenix/commit/e2dcfaf0e5cde1b93597b5a18e063e1733d1a3b0))
* **app:** setting up phoenix components library ([5e98485](https://github.com/9inpachi/phoenix/commit/5e984850db8f073367185eda8f7d78c2823ecfb7))
* **app:** theming support for phoenix-ui-components ([aebf6ed](https://github.com/9inpachi/phoenix/commit/aebf6ed707d8605ba51ad40fa9085925160e7ce7))
* **app:** working phoenix-ui module ([9b4336d](https://github.com/9inpachi/phoenix/commit/9b4336dd6d5453c53b8651a23f12e2f668dd2ae3))
* **app:** yet another MAJOR refactoring ([1261358](https://github.com/9inpachi/phoenix/commit/1261358df183cf8fe83ccd0f8866a558a0d30221))
* **event-display:** add defaultView to configuration ([612205c](https://github.com/9inpachi/phoenix/commit/612205cbeba7ffcec532ab0907b81cbed079b8c0))
* **event-display:** implicitly load event data from URL ([9e3dc20](https://github.com/9inpachi/phoenix/commit/9e3dc20748559a38289a9cf42da40bd85c72a492))
* **event-display:** state manager for managing event display state for save and load ([7d1ca22](https://github.com/9inpachi/phoenix/commit/7d1ca22f5e9bfa430297597b1d4da116eaf075a2))
* **phoenix-app:** setting up library ([31921ba](https://github.com/9inpachi/phoenix/commit/31921ba48158b6defab43b54f827c8950703bb85))






## <small>1.0.2 (2020-10-05)</small>

* Complete deployment set up ([399ac77](https://github.com/9inpachi/phoenix/commit/399ac77))
* Fix lerna prerelease command and add release grad command ([3e671ae](https://github.com/9inpachi/phoenix/commit/3e671ae))






## 1.0.1 (2020-10-05)


### Reverts

* Revert "Not sure what happened here - but re-adding OBJ files." ([8efd512](https://github.com/9inpachi/phoenix/commit/8efd5121d43cd9e2aeb4366f39cda8a684434f46))
* Revert "Adding unit tests to Playground VR component" ([69ed9f0](https://github.com/9inpachi/phoenix/commit/69ed9f0366d9d73e64d7b31556fcff0df32edd87))
* Revert "Updating Angular version" ([259fd76](https://github.com/9inpachi/phoenix/commit/259fd7656f7d52d2ef9d0e0c492935e0590ae030))
