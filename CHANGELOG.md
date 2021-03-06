<a name="0.11.1"></a>
## [0.11.1](https://github.com/ipld/js-ipld-block/compare/v0.11.0...v0.11.1) (2021-03-05)


### Bug Fixes

* update type export ([889ac77](https://github.com/ipld/js-ipld-block/commit/889ac77))



<a name="0.11.0"></a>
# [0.11.0](https://github.com/ipld/js-ipld-block/compare/v0.10.1...v0.11.0) (2020-10-21)


### Bug Fixes

* account error msg diff betwenn browsers ([85bef56](https://github.com/ipld/js-ipld-block/commit/85bef56))
* change deprecation to cover 0.11 ([36a4b61](https://github.com/ipld/js-ipld-block/commit/36a4b61))
* type mapping dir ([ddd1843](https://github.com/ipld/js-ipld-block/commit/ddd1843))


### Features

* add typedef generation ([e31d46b](https://github.com/ipld/js-ipld-block/commit/e31d46b))



<a name="0.10.1"></a>
## [0.10.1](https://github.com/ipld/js-ipld-block/compare/v0.10.0...v0.10.1) (2020-09-01)



<a name="0.10.0"></a>
# [0.10.0](https://github.com/ipld/js-ipld-block/compare/v0.9.2...v0.10.0) (2020-08-04)


### Bug Fixes

* replace node buffers with uint8arrays ([0696e4d](https://github.com/ipld/js-ipld-block/commit/0696e4d))


### BREAKING CHANGES

* - The `.data` property used to be a Buffer, now it is a Uint8Array



<a name="0.9.2"></a>
## [0.9.2](https://github.com/ipld/js-ipld-block/compare/v0.9.1...v0.9.2) (2020-06-12)


### Features

* add Uint8Array support ([418eb5f](https://github.com/ipld/js-ipld-block/commit/418eb5f))



<a name="0.9.1"></a>
## [0.9.1](https://github.com/ipld/js-ipld-block/compare/v0.9.0...v0.9.1) (2020-04-01)


### Bug Fixes

* add buffer ([b4e748c](https://github.com/ipld/js-ipld-block/commit/b4e748c))



<a name="0.9.0"></a>
# [0.9.0](https://github.com/ipld/js-ipld-block/compare/v0.8.0...v0.9.0) (2019-05-09)


### Features

* this module is now named `ipld-block` ([5a3bbde](https://github.com/ipld/js-ipld-block/commit/5a3bbde))


### BREAKING CHANGES

* The symbol for comparing blocks changed

This means that if you are a user of this module, updating to this version
is also a breaking change for your module. Don't forgot to make the corresponding
version bump on your next release.



<a name="0.8.0"></a>
# [0.8.0](https://github.com/ipfs/js-ipfs-block/compare/v0.7.1...v0.8.0) (2018-10-26)



<a name="0.7.1"></a>
## [0.7.1](https://github.com/ipfs/js-ipfs-block/compare/v0.7.0...v0.7.1) (2018-04-09)



<a name="0.7.0"></a>
# [0.7.0](https://github.com/ipfs/js-ipfs-block/compare/v0.6.1...v0.7.0) (2018-04-09)


### Features

* use class-is module for type checks ([958cd09](https://github.com/ipfs/js-ipfs-block/commit/958cd09))



<a name="0.6.1"></a>
## [0.6.1](https://github.com/ipfs/js-ipfs-block/compare/v0.6.0...v0.6.1) (2017-11-06)


### Bug Fixes

* **package:** update cids to version 0.5.0 ([#33](https://github.com/ipfs/js-ipfs-block/issues/33)) ([f0101f0](https://github.com/ipfs/js-ipfs-block/commit/f0101f0))


### Features

* windows support  ([7e2623b](https://github.com/ipfs/js-ipfs-block/commit/7e2623b))



<a name="0.6.0"></a>
# [0.6.0](https://github.com/ipfs/js-ipfs-block/compare/v0.5.5...v0.6.0) (2017-03-20)


### Features

* simplify block to only be data and cid ([#31](https://github.com/ipfs/js-ipfs-block/issues/31)) ([0581c27](https://github.com/ipfs/js-ipfs-block/commit/0581c27))



<a name="0.5.5"></a>
## [0.5.5](https://github.com/ipfs/js-ipfs-block/compare/v0.5.4...v0.5.5) (2017-02-09)


### Bug Fixes

* **package:** update multihashing-async to version 0.4.0 ([#27](https://github.com/ipfs/js-ipfs-block/issues/27)) ([18a7d28](https://github.com/ipfs/js-ipfs-block/commit/18a7d28))



<a name="0.5.4"></a>
## [0.5.4](https://github.com/ipfs/js-ipfs-block/compare/v0.5.3...v0.5.4) (2016-12-22)


### Bug Fixes

* **deps:** add async to dependencies ([5f75307](https://github.com/ipfs/js-ipfs-block/commit/5f75307))



<a name="0.5.3"></a>
## [0.5.3](https://github.com/ipfs/js-ipfs-block/compare/v0.5.2...v0.5.3) (2016-12-11)


### Bug Fixes

* Buffer check ([185e8f6](https://github.com/ipfs/js-ipfs-block/commit/185e8f6))



<a name="0.5.2"></a>
## [0.5.2](https://github.com/ipfs/js-ipfs-block/compare/v0.5.1...v0.5.2) (2016-12-11)


### Features

* convert String values to buffers to avoid strange situations in the browser ([#19](https://github.com/ipfs/js-ipfs-block/issues/19)) ([794dade](https://github.com/ipfs/js-ipfs-block/commit/794dade))



<a name="0.5.1"></a>
## [0.5.1](https://github.com/ipfs/js-ipfs-block/compare/v0.5.0...v0.5.1) (2016-12-01)



<a name="0.5.0"></a>
# [0.5.0](https://github.com/ipfs/js-ipfs-block/compare/v0.4.0...v0.5.0) (2016-11-03)



<a name="0.4.0"></a>
# [0.4.0](https://github.com/ipfs/js-ipfs-block/compare/v0.3.0...v0.4.0) (2016-10-26)


### Features

* support multiple hash functions ([e2b9da4](https://github.com/ipfs/js-ipfs-block/commit/e2b9da4))



<a name="0.3.0"></a>
# [0.3.0](https://github.com/ipfs/js-ipfs-block/compare/v0.2.2...v0.3.0) (2016-05-02)



<a name="0.2.2"></a>
## [0.2.2](https://github.com/ipfs/js-ipfs-block/compare/v0.2.1...v0.2.2) (2016-04-30)



<a name="0.2.1"></a>
## [0.2.1](https://github.com/ipfs/js-ipfs-block/compare/v0.2.0...v0.2.1) (2016-04-30)



<a name="0.2.0"></a>
# 0.2.0 (2016-04-26)



