# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.4.0 (2023-02-11)


### Bug Fixes

* adding module to type property in package.json ([1359ac6](https://github.com/atasoy182/react-financial-charts/commit/1359ac6e93d9638792c7bb478bba5fe1e5484a82)), closes [#520](https://github.com/atasoy182/react-financial-charts/issues/520)
* **axis:** adding strokeOpacity and missing props ([7870a36](https://github.com/atasoy182/react-financial-charts/commit/7870a36f1303e83a137eab7158fc62ac9337f8a6)), closes [#29](https://github.com/atasoy182/react-financial-charts/issues/29)
* **axis:** axisAt and orient now have defaults ([509fab1](https://github.com/atasoy182/react-financial-charts/commit/509fab1e5da5913f856fa22f71474b1c840e6512)), closes [#31](https://github.com/atasoy182/react-financial-charts/issues/31)
* **axis:** only allow zoom if the ticks are showing ([fb96940](https://github.com/atasoy182/react-financial-charts/commit/fb96940f93335060899966dab78a12ec75a9cb88))
* **bollinger:** correcting props ([91d7f60](https://github.com/atasoy182/react-financial-charts/commit/91d7f60870bec104a27482755190f0f1912bdede))
* **charts:** arrowWidth was being ignored ([dce50aa](https://github.com/atasoy182/react-financial-charts/commit/dce50aaffd71f667dc0ea7e4edd3fd088625abac)), closes [#75](https://github.com/atasoy182/react-financial-charts/issues/75)
* **charts:** edge coordinates can now use rectWidth ([5b0a20b](https://github.com/atasoy182/react-financial-charts/commit/5b0a20b6858f2cbbc915c2980275cdb73f568556))
* **charts:** fixing coordinates component props ([1fca524](https://github.com/atasoy182/react-financial-charts/commit/1fca5244173bea5438a19eac061df9e0505fe246))
* **charts:** fixing gridlines when the axis is on the left or top ([61d5e7b](https://github.com/atasoy182/react-financial-charts/commit/61d5e7b0225bb8c317cf04484f9a279341eb1791))
* **charts:** getXTicks is incorrectly doing a greater than ([80e5739](https://github.com/atasoy182/react-financial-charts/commit/80e5739f3c3c2aff1bfbe310e3f74c71f50a3058))
* **charts:** including src folder in the package for source maps ([632a699](https://github.com/atasoy182/react-financial-charts/commit/632a699e003363df8737a7fa5214707b6a70cc24))
* **charts:** modifying axis ticks based on height and width ([94efee1](https://github.com/atasoy182/react-financial-charts/commit/94efee14467d663caf2f04eddeb52e0cae2701d7))
* **charts:** reversing scroll direction on touch devices and trackpads ([e12ce7c](https://github.com/atasoy182/react-financial-charts/commit/e12ce7c445c9049beb0d7243581043fecd8662a5)), closes [#57](https://github.com/atasoy182/react-financial-charts/issues/57)
* **charts:** updating default time formats ([6670952](https://github.com/atasoy182/react-financial-charts/commit/667095253dda726de9de0d93fc71ea830fcecab6))
* lineDash was incorrect for canvas when set to None ([5ff3134](https://github.com/atasoy182/react-financial-charts/commit/5ff313488e33e2734bcfb860d102aa77a4f39aa1))
* **colors:** alpha channel is now used if rgba is used ([0c3e2d5](https://github.com/atasoy182/react-financial-charts/commit/0c3e2d52978861daaa74d371d533e3850d9e15df)), closes [#27](https://github.com/atasoy182/react-financial-charts/issues/27)
* **coordinates:** edge coordinates now go right up to the axis ([ba44493](https://github.com/atasoy182/react-financial-charts/commit/ba444937a177d7efb95cee6ab924b902c42ea15d))
* **coordinates:** updating default fill to [#37474](https://github.com/atasoy182/react-financial-charts/issues/37474)F ([7b8362a](https://github.com/atasoy182/react-financial-charts/commit/7b8362a12028782fc71d2067e2d3fec3317ee9c7)), closes [#30](https://github.com/atasoy182/react-financial-charts/issues/30)
* **interaction:** correcting scroll behavior when interaction is disabled ([1e32380](https://github.com/atasoy182/react-financial-charts/commit/1e32380bbcf2fcca2658127633baf7c2e03d786d))
* **ohlc:** Add option to display the last item as default ([c23b676](https://github.com/atasoy182/react-financial-charts/commit/c23b6762e7a9cf40800e48a6b2e0461b2f9f61c2))
* **ohlc:** correcting props ([86bb4b2](https://github.com/atasoy182/react-financial-charts/commit/86bb4b2b0872b66e4fc3744d82b5e3089b8d0204))
* **props:** correcting more props ([4942299](https://github.com/atasoy182/react-financial-charts/commit/494229920e2c5b5999dae5dd2bad605d842b80c6))
* **props:** correcting more props ([f22fb3c](https://github.com/atasoy182/react-financial-charts/commit/f22fb3ccbe07bc0c6520329f09510511192c9db9))
* adding missing readme from package ([1f38c35](https://github.com/atasoy182/react-financial-charts/commit/1f38c357d2f6b561fc767927868622d4955edc9c))
* ChartCanvas type is now optional ([22365a2](https://github.com/atasoy182/react-financial-charts/commit/22365a212a6eabf802bf2f9eb2a552dc9ec9eb9b))
* correcting and adding types to props ([aa98bd3](https://github.com/atasoy182/react-financial-charts/commit/aa98bd36de5fe3080c8c5226cd2553d70c0de642))
* correcting types from ChartCanvas ([a99551f](https://github.com/atasoy182/react-financial-charts/commit/a99551f2d9dfa371f695ac53743e3dd644b4ccc2))
* interfaces from withDeviceRatio need to be public ([6850ab1](https://github.com/atasoy182/react-financial-charts/commit/6850ab134a3de18ad99d08e9492b55635a66ccec))


### Features

* adding more prop types across all components ([efefd4d](https://github.com/atasoy182/react-financial-charts/commit/efefd4dc3000ffe5ad5e63380ab324ab1e232a67))
* adding react 17 as peer dependency ([569209b](https://github.com/atasoy182/react-financial-charts/commit/569209b6eb00f3c93eae1b5a9e4f014c055c93c7)), closes [#468](https://github.com/atasoy182/react-financial-charts/issues/468)
* **charts:** adding showGridLines prop to axis ([2c0f7fe](https://github.com/atasoy182/react-financial-charts/commit/2c0f7fe14b7afa95bdec4165443c3090db3d0c81))
* **charts:** default tooltip value can be changed ([f19ec61](https://github.com/atasoy182/react-financial-charts/commit/f19ec6144024dd8660212d28758ec751e7f4b0f7))
* **charts:** tweaking default mouse coordinate fill ([ead5c1a](https://github.com/atasoy182/react-financial-charts/commit/ead5c1a7f85a2d11d10d12a5a45ff4b49d0dfb15))
* **charts:** updated zoom buttons styling ([d3c1bbb](https://github.com/atasoy182/react-financial-charts/commit/d3c1bbb9eea624aead45684ca2cbbfca0cccdb5f))
* **elder-ray:** allowing stroke dash to be set on the zero line ([71e9a9b](https://github.com/atasoy182/react-financial-charts/commit/71e9a9bbaacc3f596e5542a9b15b28e259b0e5d5))
* **types:** adding more types for calculators and indicators ([3d52cf4](https://github.com/atasoy182/react-financial-charts/commit/3d52cf47b5e3c5c09e7eb4a1e8213ce0367f4195))
* moving examples to storybook ([3ce0955](https://github.com/atasoy182/react-financial-charts/commit/3ce0955ba0b94cd7923a8bc735406e5797e73b56))


* feat!: separating code into packages ([670537f](https://github.com/atasoy182/react-financial-charts/commit/670537fa280dddfbe921639a8e22a7c11d14e5f3))


### BREAKING CHANGES

* first stage of refactor breaking the code down.





## [1.3.2](https://github.com/reactivemarkets/react-financial-charts/compare/v1.3.1...v1.3.2) (2021-10-17)

**Note:** Version bump only for package react-financial-charts





## [1.3.1](https://github.com/reactivemarkets/react-financial-charts/compare/v1.3.0...v1.3.1) (2021-06-16)

**Note:** Version bump only for package react-financial-charts





# [1.3.0](https://github.com/reactivemarkets/react-financial-charts/compare/v1.2.2...v1.3.0) (2021-05-23)


### Bug Fixes

* adding module to type property in package.json ([1359ac6](https://github.com/reactivemarkets/react-financial-charts/commit/1359ac6e93d9638792c7bb478bba5fe1e5484a82)), closes [#520](https://github.com/reactivemarkets/react-financial-charts/issues/520)





## [1.2.2](https://github.com/reactivemarkets/react-financial-charts/compare/v1.2.1...v1.2.2) (2021-04-30)

**Note:** Version bump only for package react-financial-charts





## [1.2.1](https://github.com/reactivemarkets/react-financial-charts/compare/v1.2.0...v1.2.1) (2021-04-27)

**Note:** Version bump only for package react-financial-charts





# [1.2.0](https://github.com/reactivemarkets/react-financial-charts/compare/v1.1.0...v1.2.0) (2021-04-26)

**Note:** Version bump only for package react-financial-charts





# [1.1.0](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.1...v1.1.0) (2021-02-26)


### Features

* adding react 17 as peer dependency ([569209b](https://github.com/reactivemarkets/react-financial-charts/commit/569209b6eb00f3c93eae1b5a9e4f014c055c93c7)), closes [#468](https://github.com/reactivemarkets/react-financial-charts/issues/468)





## [1.0.1](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0...v1.0.1) (2021-01-01)

**Note:** Version bump only for package react-financial-charts





# [1.0.0](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.16...v1.0.0) (2020-12-30)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.16](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.15...v1.0.0-alpha.16) (2020-09-04)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.15](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.14...v1.0.0-alpha.15) (2020-09-03)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.14](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.13...v1.0.0-alpha.14) (2020-09-02)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.13](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.12...v1.0.0-alpha.13) (2020-09-01)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.12](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.11...v1.0.0-alpha.12) (2020-08-28)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.11](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.10...v1.0.0-alpha.11) (2020-08-28)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.10](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.9...v1.0.0-alpha.10) (2020-08-28)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.9](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.8...v1.0.0-alpha.9) (2020-08-24)


### Features

* adding more prop types across all components ([efefd4d](https://github.com/reactivemarkets/react-financial-charts/commit/efefd4dc3000ffe5ad5e63380ab324ab1e232a67))





# [1.0.0-alpha.8](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.7...v1.0.0-alpha.8) (2020-08-17)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.7](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.6...v1.0.0-alpha.7) (2020-07-26)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.6](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.5...v1.0.0-alpha.6) (2020-07-23)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.5](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.4...v1.0.0-alpha.5) (2020-07-23)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.4](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.3...v1.0.0-alpha.4) (2020-07-19)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.3](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.2...v1.0.0-alpha.3) (2020-07-19)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.2](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.1...v1.0.0-alpha.2) (2020-07-15)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.1](https://github.com/reactivemarkets/react-financial-charts/compare/v1.0.0-alpha.0...v1.0.0-alpha.1) (2020-07-10)

**Note:** Version bump only for package react-financial-charts





# [1.0.0-alpha.0](https://github.com/reactivemarkets/react-financial-charts/compare/v0.5.1...v1.0.0-alpha.0) (2020-07-08)


* feat!: separating code into packages ([670537f](https://github.com/reactivemarkets/react-financial-charts/commit/670537fa280dddfbe921639a8e22a7c11d14e5f3))


### BREAKING CHANGES

* first stage of refactor breaking the code down.





## [0.5.1](https://github.com/reactivemarkets/react-financial-charts/compare/v0.5.0...v0.5.1) (2020-01-08)


### Bug Fixes

* **charts:** fixing gridlines when the axis is on the left or top ([61d5e7b](https://github.com/reactivemarkets/react-financial-charts/commit/61d5e7b0225bb8c317cf04484f9a279341eb1791))





# [0.5.0](https://github.com/reactivemarkets/react-financial-charts/compare/v0.4.1...v0.5.0) (2020-01-07)


### Features

* **charts:** adding showGridLines prop to axis ([2c0f7fe](https://github.com/reactivemarkets/react-financial-charts/commit/2c0f7fe14b7afa95bdec4165443c3090db3d0c81))
* **charts:** default tooltip value can be changed ([f19ec61](https://github.com/reactivemarkets/react-financial-charts/commit/f19ec6144024dd8660212d28758ec751e7f4b0f7))
* **charts:** tweaking default mouse coordinate fill ([ead5c1a](https://github.com/reactivemarkets/react-financial-charts/commit/ead5c1a7f85a2d11d10d12a5a45ff4b49d0dfb15))





## [0.4.1](https://github.com/reactivemarkets/react-financial-charts/compare/v0.4.0...v0.4.1) (2019-12-17)


### Bug Fixes

* **charts:** getXTicks is incorrectly doing a greater than ([80e5739](https://github.com/reactivemarkets/react-financial-charts/commit/80e5739f3c3c2aff1bfbe310e3f74c71f50a3058))
* **charts:** including src folder in the package for source maps ([632a699](https://github.com/reactivemarkets/react-financial-charts/commit/632a699e003363df8737a7fa5214707b6a70cc24))





# [0.4.0](https://github.com/reactivemarkets/react-financial-charts/compare/v0.3.3...v0.4.0) (2019-12-16)


### Bug Fixes

* **charts:** edge coordinates can now use rectWidth ([5b0a20b](https://github.com/reactivemarkets/react-financial-charts/commit/5b0a20b6858f2cbbc915c2980275cdb73f568556))
* **charts:** fixing coordinates component props ([1fca524](https://github.com/reactivemarkets/react-financial-charts/commit/1fca5244173bea5438a19eac061df9e0505fe246))
* **charts:** modifying axis ticks based on height and width ([94efee1](https://github.com/reactivemarkets/react-financial-charts/commit/94efee14467d663caf2f04eddeb52e0cae2701d7))


### Features

* **charts:** updated zoom buttons styling ([d3c1bbb](https://github.com/reactivemarkets/react-financial-charts/commit/d3c1bbb9eea624aead45684ca2cbbfca0cccdb5f))





## [0.3.3](https://github.com/reactivemarkets/react-financial-charts/compare/v0.3.2...v0.3.3) (2019-11-27)


### Bug Fixes

* **charts:** updating default time formats ([6670952](https://github.com/reactivemarkets/react-financial-charts/commit/667095253dda726de9de0d93fc71ea830fcecab6))





## [0.3.2](https://github.com/reactivemarkets/react-financial-charts/compare/v0.3.1...v0.3.2) (2019-11-21)

**Note:** Version bump only for package react-financial-charts





## [0.3.1](https://github.com/reactivemarkets/react-financial-charts/compare/v0.3.0...v0.3.1) (2019-10-14)


### Bug Fixes

* lineDash was incorrect for canvas when set to None ([5ff3134](https://github.com/reactivemarkets/react-financial-charts/commit/5ff3134))
* **charts:** reversing scroll direction on touch devices and trackpads ([e12ce7c](https://github.com/reactivemarkets/react-financial-charts/commit/e12ce7c)), closes [#57](https://github.com/reactivemarkets/react-financial-charts/issues/57)
* **coordinates:** edge coordinates now go right up to the axis ([ba44493](https://github.com/reactivemarkets/react-financial-charts/commit/ba44493))





# [0.3.0](https://github.com/reactivemarkets/react-financial-charts/compare/v0.2.3...v0.3.0) (2019-10-04)


### Bug Fixes

* **charts:** arrowWidth was being ignored ([dce50aa](https://github.com/reactivemarkets/react-financial-charts/commit/dce50aa)), closes [#75](https://github.com/reactivemarkets/react-financial-charts/issues/75)


### Features

* **types:** adding more types for calculators and indicators ([3d52cf4](https://github.com/reactivemarkets/react-financial-charts/commit/3d52cf4))





## [0.2.3](https://github.com/reactivemarkets/react-financial-charts/compare/v0.2.2...v0.2.3) (2019-09-26)


### Bug Fixes

* **interaction:** correcting scroll behavior when interaction is disabled ([1e32380](https://github.com/reactivemarkets/react-financial-charts/commit/1e32380))





## [0.2.2](https://github.com/reactivemarkets/react-financial-charts/compare/v0.2.1...v0.2.2) (2019-09-19)


### Bug Fixes

* **ohlc:** Add option to display the last item as default ([c23b676](https://github.com/reactivemarkets/react-financial-charts/commit/c23b676))
* **props:** correcting more props ([4942299](https://github.com/reactivemarkets/react-financial-charts/commit/4942299))
* **props:** correcting more props ([f22fb3c](https://github.com/reactivemarkets/react-financial-charts/commit/f22fb3c))





## [0.2.1](https://github.com/reactivemarkets/react-financial-charts/compare/v0.2.0...v0.2.1) (2019-09-14)


### Bug Fixes

* **bollinger:** correcting props ([91d7f60](https://github.com/reactivemarkets/react-financial-charts/commit/91d7f60))
* **ohlc:** correcting props ([86bb4b2](https://github.com/reactivemarkets/react-financial-charts/commit/86bb4b2))





# [0.2.0](https://github.com/reactivemarkets/react-financial-charts/compare/v0.1.5...v0.2.0) (2019-09-12)


### Bug Fixes

* **axis:** only allow zoom if the ticks are showing ([fb96940](https://github.com/reactivemarkets/react-financial-charts/commit/fb96940))


### Features

* **elder-ray:** allowing stroke dash to be set on the zero line ([71e9a9b](https://github.com/reactivemarkets/react-financial-charts/commit/71e9a9b))





## [0.1.5](https://github.com/reactivemarkets/react-financial-charts/compare/v0.1.4...v0.1.5) (2019-09-11)


### Bug Fixes

* **axis:** adding strokeOpacity and missing props ([7870a36](https://github.com/reactivemarkets/react-financial-charts/commit/7870a36)), closes [#29](https://github.com/reactivemarkets/react-financial-charts/issues/29)
* **axis:** axisAt and orient now have defaults ([509fab1](https://github.com/reactivemarkets/react-financial-charts/commit/509fab1)), closes [#31](https://github.com/reactivemarkets/react-financial-charts/issues/31)
* **colors:** alpha channel is now used if rgba is used ([0c3e2d5](https://github.com/reactivemarkets/react-financial-charts/commit/0c3e2d5)), closes [#27](https://github.com/reactivemarkets/react-financial-charts/issues/27)
* **coordinates:** updating default fill to [#37474](https://github.com/reactivemarkets/react-financial-charts/issues/37474)F ([7b8362a](https://github.com/reactivemarkets/react-financial-charts/commit/7b8362a)), closes [#30](https://github.com/reactivemarkets/react-financial-charts/issues/30)





## [0.1.4](https://github.com/reactivemarkets/react-financial-charts/compare/v0.1.3...v0.1.4) (2019-09-10)


### Bug Fixes

* correcting types from ChartCanvas ([a99551f](https://github.com/reactivemarkets/react-financial-charts/commit/a99551f))





## [0.1.3](https://github.com/reactivemarkets/react-financial-charts/compare/v0.1.2...v0.1.3) (2019-09-10)


### Bug Fixes

* ChartCanvas type is now optional ([22365a2](https://github.com/reactivemarkets/react-financial-charts/commit/22365a2))
* correcting and adding types to props ([aa98bd3](https://github.com/reactivemarkets/react-financial-charts/commit/aa98bd3))





## [0.1.2](https://github.com/reactivemarkets/react-financial-charts/compare/v0.1.1...v0.1.2) (2019-09-10)


### Bug Fixes

* interfaces from withDeviceRatio need to be public ([6850ab1](https://github.com/reactivemarkets/react-financial-charts/commit/6850ab1))





## [0.1.1](https://github.com/reactivemarkets/react-financial-charts/compare/v0.1.0...v0.1.1) (2019-09-09)


### Bug Fixes

* adding missing readme from package ([1f38c35](https://github.com/reactivemarkets/react-financial-charts/commit/1f38c35))





# 0.1.0 (2019-09-08)


### Features

* moving examples to storybook ([3ce0955](https://github.com/reactivemarkets/react-financial-charts/commit/3ce0955))
