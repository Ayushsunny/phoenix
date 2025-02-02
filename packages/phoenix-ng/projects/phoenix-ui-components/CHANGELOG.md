# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.7.0](https://github.com/HSF/phoenix/compare/v1.6.1...v1.7.0) (2021-04-21)


### Features

* **app:** option for custom import handlers ([99b161e](https://github.com/HSF/phoenix/commit/99b161e76109fb2b99031a35ac72fbe31596f44b))
* **app:** support for importing with LHCb loader ([8c6bd89](https://github.com/HSF/phoenix/commit/8c6bd89bafcd3f4123365f36f36f49d83f4352d8))





## [1.6.1](https://github.com/HSF/phoenix/compare/v1.6.0...v1.6.1) (2021-04-19)


### Bug Fixes

* **app:** update three.js for phoenix-ui-components ([6f5af5e](https://github.com/HSF/phoenix/commit/6f5af5edd5450d7143bd94de00c2186bd3b8d87e))
* **event-display:** animation event with clipping because of maximum callstack reached ([e5d6639](https://github.com/HSF/phoenix/commit/e5d6639ca5698162160d4d64545916087dd5f066))






# [1.6.0](https://github.com/HSF/phoenix/compare/v1.5.0...v1.6.0) (2021-04-18)


### Bug Fixes

* **app:** consistent input styling and fix share icon ([2e3455d](https://github.com/HSF/phoenix/commit/2e3455dd58c2c6f6bd0018651073a52f46716de4))
* **app:** event selection should show current event ([a65d8ac](https://github.com/HSF/phoenix/commit/a65d8ac2feebf140181f20a81098b6174212ae32))
* **app:** revert added URL options and UI components package.json ([96f0649](https://github.com/HSF/phoenix/commit/96f06498b58a87e2fa035e94bb76b05f13aaaa75))


### Features

* **app:** bind clipping state with UI menu ([40bbba0](https://github.com/HSF/phoenix/commit/40bbba07311d6c23b59d5d5409d190c2721bc395))
* **app:** complete dialog for share link and embed ([50c2584](https://github.com/HSF/phoenix/commit/50c2584107d132e8f7161c28ce4d88479e30c4ed))
* **app:** create component for shareable link constructor ([181dfa8](https://github.com/HSF/phoenix/commit/181dfa8b0d05888f89a27f4640466f9b57c06568))
* **app:** don't show hits in collection info ([c550a41](https://github.com/HSF/phoenix/commit/c550a41860c97a223527ecc2da4e66fb644a0844))
* **app:** fix link creation and improve link constructor ([2cedfec](https://github.com/HSF/phoenix/commit/2cedfeceb99b2d105bd603b8290b15fcfe5cdf0e))
* **app:** setup link share form ([b10bb7a](https://github.com/HSF/phoenix/commit/b10bb7aa14e373191bea6508d723c79c42c3f2b3))
* **event-display:** add guidelines and simplify some coordinate transformations ([56f94f0](https://github.com/HSF/phoenix/commit/56f94f043b5bdf5e521c05e0bc058186c78270ad))
* **event-display:** create an active observable variable ([854e543](https://github.com/HSF/phoenix/commit/854e5439a1ebeba80940989a716338f1542984db))
* upgrade all packages except three.js ([8e2eff4](https://github.com/HSF/phoenix/commit/8e2eff4b58e02f19cefd3e02e7edf92a81474783))
* **event-display:** introduce new URL options and improve handling them ([f7cd6b4](https://github.com/HSF/phoenix/commit/f7cd6b4b6059db82900bc9a0245d8365a5917e8b))






# [1.5.0](https://github.com/HSF/phoenix/compare/v1.4.1...v1.5.0) (2021-03-24)


### Bug Fixes

* **event-display:** fix jsroot loading root file ([8cbcaa5](https://github.com/HSF/phoenix/commit/8cbcaa5d2e4ba89940d65d217e302e7500305641))


### Features

* **app:** ability to import ig archive in CMS ([9540af5](https://github.com/HSF/phoenix/commit/9540af5d08ab2867e6ef0496a1bd1e3215e91af7))
* **app:** add ability to import zip with both jivexml and json ([5d62da8](https://github.com/HSF/phoenix/commit/5d62da8aed3621adfff3f8a712e27ff6978efb22))
* **app:** allow loading compressed jivexml (multiple files) ([d4f3cc7](https://github.com/HSF/phoenix/commit/d4f3cc7a7a5f8e5f2f7e94ce0cc99165debd9952))
* **app:** allow loading compressed json event data (multiple files) ([360fb20](https://github.com/HSF/phoenix/commit/360fb20d75f793131cf22471cf6a2db959f5c1f0))
* **app:** dont process zip through json or jivexml import ([17b4e85](https://github.com/HSF/phoenix/commit/17b4e8587ac7743b9c556c73fa3a48862e9ad4ef))
* **app:** dynamically define supported event formats for io import ([1449cbe](https://github.com/HSF/phoenix/commit/1449cbedec631f4c0d69ad35129c64a949e493e4))
* **app:** make event data io options configurable ([989ac0e](https://github.com/HSF/phoenix/commit/989ac0ec0a50b9130fc01613735eb1f3c4b226e4))
* **event-display:** resize canvas with window resize ([5ea04f1](https://github.com/HSF/phoenix/commit/5ea04f174b5adbe54af0aa4663466c5b6291c0a2))
* **event-display:** update to use CDN for JSROOT ([2fa310f](https://github.com/HSF/phoenix/commit/2fa310fc0171bd19e0ec1b75322eba6b532e5bfe))






## [1.4.1](https://github.com/HSF/phoenix/compare/v1.4.0...v1.4.1) (2021-02-26)

**Note:** Version bump only for package phoenix-ui-components






# [1.4.0](https://github.com/HSF/phoenix/compare/v1.3.0...v1.4.0) (2021-02-16)


### Bug Fixes

* **event-display:** improve object selection from uuid and label input ([3475836](https://github.com/HSF/phoenix/commit/3475836eacca1485f6dddab8dc049bbb605a5e27))


### Features

* **app:** ability to add label ([cccd3ed](https://github.com/HSF/phoenix/commit/cccd3ed22583dd9061e09a1c8cf455ee60db7a22))
* **app:** add label icon and form ([a65a83e](https://github.com/HSF/phoenix/commit/a65a83ece414ae86e5ed66bbb1f97a97a0bd09e7))
* **event-display:** delete label on empty value and change add label icon ([3756330](https://github.com/HSF/phoenix/commit/3756330d06c459662a0e99d447e5984ebea87e27))
* **event-display:** set up add label to object functions ([db261a6](https://github.com/HSF/phoenix/commit/db261a6fe5b770f912bef080f1ceec6374a81d08))
* Update Angular and all packages to latest ([f4c2e31](https://github.com/HSF/phoenix/commit/f4c2e31207e890436a6387e2e34ef31e3d0c48a6))





# [1.3.0](https://github.com/HSF/phoenix/compare/v1.2.0...v1.3.0) (2021-01-16)


### Bug Fixes

* **app:** improve IO code ([a09be14](https://github.com/HSF/phoenix/commit/a09be1491f1357bd3c5925d6f6bba7d101dd6e94))
* **app:** make import words consistent ([08e771d](https://github.com/HSF/phoenix/commit/08e771d4bb76873ed6931f8aee485925c7f34889))
* **app:** minor test improvements ([8a0d5cf](https://github.com/HSF/phoenix/commit/8a0d5cf26ad06302ae7d6879863aad8dcd17e0ba))
* **app:** upgrade to ngx-slider ([6c9b928](https://github.com/HSF/phoenix/commit/6c9b9282fbb1832105dbbd1b54255b9f542ce859))
* **event-display:** code improvements ([f94c0e4](https://github.com/HSF/phoenix/commit/f94c0e40384ee95f22ba1a92938cf124a6d89a31))
* **event-display:** fix parsing of GLTF geometry ([dc5d489](https://github.com/HSF/phoenix/commit/dc5d489fd2b2730b9d235851c09baf86d88325d3))


### Features

* **app:** restyle IO options ([1542808](https://github.com/HSF/phoenix/commit/15428081d748d8e8f548c6d76ef46358d28c82be))
* **app:** support for importing ROOT geometry ([89adb25](https://github.com/HSF/phoenix/commit/89adb258182bf27a22748ddd14a3880de9a89af3))






# [1.2.0](https://github.com/HSF/phoenix/compare/v1.1.0...v1.2.0) (2020-12-06)


### Bug Fixes

* **app:** add missing icons to assets ([7256013](https://github.com/HSF/phoenix/commit/7256013e712f8d3fa62b7cbf54fb7bd42e25d725))
* **app:** fix tests ([fa110c2](https://github.com/HSF/phoenix/commit/fa110c2f839985d2eab9540cd6138c68596d27ff))
* **app:** make VR icon disabled not hidden ([8712753](https://github.com/HSF/phoenix/commit/87127539d62197d6414e76e9bb5a39512c422452))
* **app:** minor fixes for ss mode ([ac829ae](https://github.com/HSF/phoenix/commit/ac829ae1c70c780583d729ef6b871e4bf78a2b33))
* **app:** minor test fix ([73e2bf4](https://github.com/HSF/phoenix/commit/73e2bf437c4f72f962843a97e3a8d3abaaf2ca3a))
* **app:** revert phoenix-ui-components package.json ([640155b](https://github.com/HSF/phoenix/commit/640155b2c0b1164e7b2b5e1f033e61c846fee42d))
* **app:** use optional chaining for fullscreen in SS mode ([6234655](https://github.com/HSF/phoenix/commit/6234655c3a5030088991787e91ddb67d9201bcf8))
* **event-display:** stop animation loop on home ([c39ecd3](https://github.com/HSF/phoenix/commit/c39ecd3d57744e5ad117de6cd0aafc2c81b5c58d))


### Features

* **app:** add tests for screenshot mode toggle ([18f27c5](https://github.com/HSF/phoenix/commit/18f27c59457f1f149879bf300ccc25b57f949a0f))
* **app:** add toggle for screenshot mode ([22a1ec8](https://github.com/HSF/phoenix/commit/22a1ec8903ac80d72f564eca29e49d15cbd411ce))
* **app:** component for toggling antialiasing ([5545d80](https://github.com/HSF/phoenix/commit/5545d80ea67a4d803c8c7839accd76f06b2a2fe8))
* **app:** enter fullscreen in screenshot mode ([70f139f](https://github.com/HSF/phoenix/commit/70f139fd23f5430b95aeb4741ff03b040cd40358))
* **app:** hide overlays screenshot mode ([4fd0197](https://github.com/HSF/phoenix/commit/4fd0197a700240a1b40828b288e6bbb7d1b4d72f))
* **app:** make loader generic ([ff10477](https://github.com/HSF/phoenix/commit/ff10477b40fae8554813b283a644c6aeb421f88a))
* **app:** rename antialias toggle to performance and add icon ([5b3cbae](https://github.com/HSF/phoenix/commit/5b3cbae8171b5f2d0006de5991be0c32f97af4e4))
* **app:** set up performance mode with selection ([947f6bf](https://github.com/HSF/phoenix/commit/947f6bf2f4da25528de3ab3eeb44c579c084d9a6))
* **app:** use event display loader in Angular component ([25b2a9d](https://github.com/HSF/phoenix/commit/25b2a9df57b48b0b372358f5350648e3b1b7e846))
* **event-display:** handle loading better ([9474565](https://github.com/HSF/phoenix/commit/9474565a2bc9b3764cb0970df14ed79a1d943a03))
* **event-display:** use object to simplify configuration ([4b10452](https://github.com/HSF/phoenix/commit/4b10452a80aed8e67ddac5d550cc9fd15383bad3))






# [1.1.0](https://github.com/HSF/phoenix/compare/v1.0.2...v1.1.0) (2020-11-07)


### Bug Fixes

* **app:** fix attribute pipe ([0980379](https://github.com/HSF/phoenix/commit/09803798a1e5bef8a02e004a63a671d666d0a56a))
* **app:** fix tests ([f87c587](https://github.com/HSF/phoenix/commit/f87c5876f5a7a83ef3f0a1cb71ff345b492f4263))
* **app:** fix tests ([fd5c475](https://github.com/HSF/phoenix/commit/fd5c4757c575a7c7a3980bd9a12e010e325fa683))
* **app:** fix tests 2 and add assets to phoenix-ui ([3527eb4](https://github.com/HSF/phoenix/commit/3527eb4dd91f79a016f3557b6b8b976f52d30307))
* **app:** rename phoenix-ui to phoenix-ui-components ([bec982c](https://github.com/HSF/phoenix/commit/bec982c5b2361f8b5be99960d9239d6347a2ab86))
* **app:** style encapsulation for components ([e247c33](https://github.com/HSF/phoenix/commit/e247c3310a7be95c9d5b15492419dc54a6f11a89))


### Features

* **app:** theming support for phoenix-ui-components ([aebf6ed](https://github.com/HSF/phoenix/commit/aebf6ed707d8605ba51ad40fa9085925160e7ce7))
