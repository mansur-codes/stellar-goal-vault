# Changelog

## 1.0.0 (2026-06-01)


### Features

* [#116](https://github.com/mansur-codes/stellar-goal-vault/issues/116) Add API Integration Tests For Campaign Lifecycle ([cb62b3a](https://github.com/mansur-codes/stellar-goal-vault/commit/cb62b3affbd636dc992fc85138f27283ce7799c1))
* [#17](https://github.com/mansur-codes/stellar-goal-vault/issues/17) Add Asset Filtering To GET /api/campaigns ([01713bd](https://github.com/mansur-codes/stellar-goal-vault/commit/01713bd275ae9411ecd9c64a1c9bb793725f08a8))
* add asset code filter for campaign discovery ([49cd3a1](https://github.com/mansur-codes/stellar-goal-vault/commit/49cd3a1ee781c256e68820f7896f2c5d55931220))
* add backend search functionality for campaigns ([f77d88a](https://github.com/mansur-codes/stellar-goal-vault/commit/f77d88a817af9333094e82cfc6c2a19fcad62927))
* add batch_refund function for failed campaigns ([13d9997](https://github.com/mansur-codes/stellar-goal-vault/commit/13d99973b76f9358763facd265eb297ffbdd0565)), closes [#114](https://github.com/mansur-codes/stellar-goal-vault/issues/114)
* add blockchain metadata support for future Soroban sync ([d21f704](https://github.com/mansur-codes/stellar-goal-vault/commit/d21f70431fcab58569beb27776b65b161236a8d3))
* add bundle visualizer, useLocalStorage, CSV export, and docker health checks ([a34a6b4](https://github.com/mansur-codes/stellar-goal-vault/commit/a34a6b4a29fd77c262e055e988af45e4159c354a))
* add campaign contributors summary ([e4a3c97](https://github.com/mansur-codes/stellar-goal-vault/commit/e4a3c97b5d4fae059bbe60072d6d6dc2cd90e3b6))
* add campaign goal edit endpoint for creators ([bcb33a1](https://github.com/mansur-codes/stellar-goal-vault/commit/bcb33a15ea8b82f515931e4107504182e9075d29))
* add campaign search api ([d5b7583](https://github.com/mansur-codes/stellar-goal-vault/commit/d5b75835405f28f334d4ca0fb1b5fa9ee602b5b0))
* add campaign share button ([faae957](https://github.com/mansur-codes/stellar-goal-vault/commit/faae9577976e480e9d7363583e4d4ec13ad602c8))
* Add Confetti Effect When Campaign Reaches Goal ([d90650f](https://github.com/mansur-codes/stellar-goal-vault/commit/d90650ff33ce05ffe2cd37cc48c57c0bd40ebc37))
* add docker override, security policy, error boundaries, and env validation ([67470f5](https://github.com/mansur-codes/stellar-goal-vault/commit/67470f5291b20e13542680d7953148ba55924f6a))
* add frontend tests for create and pledge flows ([4a4db86](https://github.com/mansur-codes/stellar-goal-vault/commit/4a4db86ab4c9b9e95caa3a912380f5f7774459a0))
* add get_contributor_count function ([922a5a0](https://github.com/mansur-codes/stellar-goal-vault/commit/922a5a0ca932b7150b9cea64b9d08c232c7ee72d))
* add GitHub Actions CI workflow for backend, frontend, and contract builds ([b023358](https://github.com/mansur-codes/stellar-goal-vault/commit/b02335805ac20893aa4dfa284ab611ca0a2627ef))
* add JSDoc, ESLint, Soroban CI, and release-please automation ([de33dce](https://github.com/mansur-codes/stellar-goal-vault/commit/de33dce99b926b5252ef0572c9c985eb19f2c190))
* add keyboard shortcuts help overlay with global key bindings ([b364c17](https://github.com/mansur-codes/stellar-goal-vault/commit/b364c170ae8757705f99fd3a286669076bd5506d))
* add paginated campaign pledge list endpoint ([6186fe2](https://github.com/mansur-codes/stellar-goal-vault/commit/6186fe203aab09ba4a38f473c31ac1088f27303e))
* add per-contributor pledge limit per campaign ([c9b51d0](https://github.com/mansur-codes/stellar-goal-vault/commit/c9b51d00e54c55df603d806eb436dca5b80a0db9))
* add property-based tests for funding invariants ([369b8d9](https://github.com/mansur-codes/stellar-goal-vault/commit/369b8d9aa2af8cae87081ace413fbfa0558493ce))
* add soft delete support for campaigns ([c600d00](https://github.com/mansur-codes/stellar-goal-vault/commit/c600d00d7573010149dd8ccb01cd1d72e82ed9ae))
* add Soroban RPC event indexer, fix all build errors, and ensure robust backend/frontend integration ([5bc98e1](https://github.com/mansur-codes/stellar-goal-vault/commit/5bc98e1ecfc96127e699be395d99fc4a08917fb1))
* add stellar goal vault MVP ([bcfaa43](https://github.com/mansur-codes/stellar-goal-vault/commit/bcfaa4391da8f1be251e152e551b1aa0454efc77))
* add testnet faucet link to dev footer ([00347fb](https://github.com/mansur-codes/stellar-goal-vault/commit/00347fb8d82b7f390d6c526d428c2c625f5bad23))
* Add validated status query parameter to campaign list endpoint with server-side filtering ([1f3f210](https://github.com/mansur-codes/stellar-goal-vault/commit/1f3f210f539b1671826bb1cb2d32aaf480e73065))
* add wallet disconnect button and Freighter account sync ([32fd775](https://github.com/mansur-codes/stellar-goal-vault/commit/32fd77579ffebd56559341a2f0e91478734aeabf))
* **api:** sanitize campaign html content using express-validator [#311](https://github.com/mansur-codes/stellar-goal-vault/issues/311) ([c25e861](https://github.com/mansur-codes/stellar-goal-vault/commit/c25e8613cbac604b48c149c34ef6bd659ef7ecf5))
* **backend:** add response compression middleware (gzip/br) to Express ([a42a740](https://github.com/mansur-codes/stellar-goal-vault/commit/a42a740b264234548b96f7e3b49d1ce4606b7578))
* **backend:** add structured json logging ([52dee55](https://github.com/mansur-codes/stellar-goal-vault/commit/52dee5542ebc204e7cd916043fca3d91733041fb))
* **backend:** add structured request logging middleware ([91c1421](https://github.com/mansur-codes/stellar-goal-vault/commit/91c14218b49f93ae2120fcde8931819c22a01458))
* **backend:** optimize campaignStore list query with single SQL join ([eee0256](https://github.com/mansur-codes/stellar-goal-vault/commit/eee025657ff4ddb5cc5b7d35d09cd28699d5b80e))
* feat: sync selected campaign to URL query param with graceful fallback for invalid shared links ([832aba8](https://github.com/mansur-codes/stellar-goal-vault/commit/832aba8c17fa9bccf820bbd55b53c977ebc1a3aa))
* **frontend:** add dark mode toggle with theme persistence and UI updates ([e07ab5c](https://github.com/mansur-codes/stellar-goal-vault/commit/e07ab5cc9bf67681bb2e48f305568297eeed8a79))
* **frontend:** add pledge confirmation modal to CampaignDetailPanel ([1af8f94](https://github.com/mansur-codes/stellar-goal-vault/commit/1af8f944c1c988562a73118698a0a76097cdd5b0))
* **frontend:** add service worker for offline-first campaign list caching ([9ecf1bd](https://github.com/mansur-codes/stellar-goal-vault/commit/9ecf1bdc6d34f3c39eb7dec565d30368e86ffde6))
* **frontend:** add status tabs with counts for campaign filtering ([07249f1](https://github.com/mansur-codes/stellar-goal-vault/commit/07249f1939be8a7487a6ec37927ebb2a35965a5e)), closes [#77](https://github.com/mansur-codes/stellar-goal-vault/issues/77)
* **frontend:** add toast notification system for action feedback ([c04e65e](https://github.com/mansur-codes/stellar-goal-vault/commit/c04e65ee0c816a9a463ae1769d61bdd5300fa43c))
* **frontend:** integrate Freighter pledge flow ([695d0cd](https://github.com/mansur-codes/stellar-goal-vault/commit/695d0cd538e949e98ac12a6ac57bd1c411d641e4))
* **frontend:** lazy-load CampaignDetailPanel and CreatorAnalytics with React.lazy ([b28d2f7](https://github.com/mansur-codes/stellar-goal-vault/commit/b28d2f7ff7feba907e02237fe5a446e55f56ac65))
* GitHub Actions PR Test Workflow ([4eeceaf](https://github.com/mansur-codes/stellar-goal-vault/commit/4eeceaf326c98298faad0623ff7ad7b0442f3045))
* Implement a new "Stellar Midnight" UI theme with glassmorphism, animations, and empty states for improved aesthetics and user experience. ([b67372f](https://github.com/mansur-codes/stellar-goal-vault/commit/b67372f30cee6b79a8d70c986fe56ccac6895587))
* implement asset allowlist and campaign metadata support ([4e925c4](https://github.com/mansur-codes/stellar-goal-vault/commit/4e925c415744538ba2d108bade1a320aa2ef4bbf))
* Implement comprehensive frontend validation for Create Campaign Form ([909426c](https://github.com/mansur-codes/stellar-goal-vault/commit/909426ce485d37cdb561ffc191b49c06832daf83))
* implement frontend foundation and Freighter wallet integration for campaign management ([06f0a7d](https://github.com/mansur-codes/stellar-goal-vault/commit/06f0a7d2861cd1e5f2d8dd1098ed2a146b0500f3))
* **ui:** implement virtual scrolling for campaign list ([8d7588b](https://github.com/mansur-codes/stellar-goal-vault/commit/8d7588bba7b317191f8d2039a31bca24b4478341)), closes [#324](https://github.com/mansur-codes/stellar-goal-vault/issues/324)


### Bug Fixes

* add contract version storage and getter ([4fb0a61](https://github.com/mansur-codes/stellar-goal-vault/commit/4fb0a6177f4b3bd146afb0b9d0ea043468ccccf0))
* add defensive guards for promises and token array checks ([94c0cb3](https://github.com/mansur-codes/stellar-goal-vault/commit/94c0cb3fdabf305bb7258126b98c43f2c8a9fac3))
* **api:** restrict JSON body size to 16kb to prevent memory exhaustion ([25fe47c](https://github.com/mansur-codes/stellar-goal-vault/commit/25fe47c77762b3963daa0376207a1fd1ebd2efcd)), closes [#307](https://github.com/mansur-codes/stellar-goal-vault/issues/307)
* **ci:** repair backend dependency and frontend build ([c30ff50](https://github.com/mansur-codes/stellar-goal-vault/commit/c30ff504ebbea698c8099db6cd07ed70e1e05c95))
* complete incomplete frontend code from merge conflicts ([7033e59](https://github.com/mansur-codes/stellar-goal-vault/commit/7033e59f226a0632f70d0efcaa855c99641d49e8))
* handle pledge failure state in tests ([70bd712](https://github.com/mansur-codes/stellar-goal-vault/commit/70bd7126c38b26d32a43251b5b074e778ee62cce))
* resolve all TypeScript and CSS build errors ([c9cae85](https://github.com/mansur-codes/stellar-goal-vault/commit/c9cae858640952e933cc0a2f8688a886bccfc81d))
* resolve CI failures from broken main branch state ([cd3cd7e](https://github.com/mansur-codes/stellar-goal-vault/commit/cd3cd7e84b4793227802f2b6be56a96306ebad7b))
* resolve compilation errors and finalize request logging middleware [#21](https://github.com/mansur-codes/stellar-goal-vault/issues/21) ([ca0eb7e](https://github.com/mansur-codes/stellar-goal-vault/commit/ca0eb7e5527bc0cc391d9d275a69338433df1a5c))
* resolve issues [#301](https://github.com/mansur-codes/stellar-goal-vault/issues/301), [#302](https://github.com/mansur-codes/stellar-goal-vault/issues/302), [#309](https://github.com/mansur-codes/stellar-goal-vault/issues/309) — templates, audit gates, SRI check ([8f00af2](https://github.com/mansur-codes/stellar-goal-vault/commit/8f00af2c89a35004efe77ec2d11efe747a3ff99a))
* resolve merge conflicts and integrate search with filters ([5508493](https://github.com/mansur-codes/stellar-goal-vault/commit/5508493c2d08028439bd70cb310d2b0bac748a13))


### Performance Improvements

* optimize campaign list performance and prevent unnecessary re-renders [#273](https://github.com/mansur-codes/stellar-goal-vault/issues/273) ([8c78649](https://github.com/mansur-codes/stellar-goal-vault/commit/8c7864975f0f8bea4f9ffc63b70adfd1957f4286))
