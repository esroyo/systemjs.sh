# Changelog

All notable changes to this project will be documented in this file. See [commit-and-tag-version](https://github.com/absolute-version/commit-and-tag-version) for commit guidelines.

## [1.16.2](https://github.com/esroyo/systemjs.sh/compare/v1.16.1...v1.16.2) (2024-03-03)


### Bug Fixes

* replace UPSTREAM origin in non-js body responses ([cafbed6](https://github.com/esroyo/systemjs.sh/commit/cafbed63399e89b62fae38c9d753e3bac9be6870))


### Other

* drop user-land expires in favor of cache built-ins ([981346a](https://github.com/esroyo/systemjs.sh/commit/981346aed858ae6f3b1d15b3b0738b380f640283))
* refactor without steps ([d80898a](https://github.com/esroyo/systemjs.sh/commit/d80898a24177435740c125f0d8e2a4ba65e06e8f))

## [1.16.1](https://github.com/esroyo/systemjs.sh/compare/v1.16.0...v1.16.1) (2024-03-02)

## [1.16.0](https://github.com/esroyo/systemjs.sh/compare/v1.15.3...v1.16.0) (2024-02-29)


### Features

* take advantage of redis EX ([5395db1](https://github.com/esroyo/systemjs.sh/commit/5395db14e930467b81e64e10645ec98ce25200fa))

## [1.15.3](https://github.com/esroyo/systemjs.sh/compare/v1.15.2...v1.15.3) (2024-02-28)


### Bug Fixes

* include upstream 403 responses in the cache ([54b0e87](https://github.com/esroyo/systemjs.sh/commit/54b0e87cead34ebdbd4896a0fa31e8b7b0fbc218))

## [1.15.2](https://github.com/esroyo/systemjs.sh/compare/v1.15.1...v1.15.2) (2024-02-27)


### Bug Fixes

* 404 should be cached ([4bc28d7](https://github.com/esroyo/systemjs.sh/commit/4bc28d79b5a4428c7641219c5bad0458445ff52f))

## [1.15.1](https://github.com/esroyo/systemjs.sh/compare/v1.15.0...v1.15.1) (2024-02-27)


### Bug Fixes

* handle redis connection failure ([4b47e0c](https://github.com/esroyo/systemjs.sh/commit/4b47e0c16640b8678a1414bdc6bdf4651b5cbf73))

## [1.15.0](https://github.com/esroyo/systemjs.sh/compare/v1.14.8...v1.15.0) (2024-02-27)


### Features

* add option to disable Worker `WORKER_ENABLE` ([9f6b565](https://github.com/esroyo/systemjs.sh/commit/9f6b565d758dd65fce2758a1036bae5c04b587fd))
* add redis cache via option CACHE_REDIS_HOSTNAME ([624ea09](https://github.com/esroyo/systemjs.sh/commit/624ea09b0f4e4e90e745e04827c723d8b07fda17))

## [1.14.8](https://github.com/esroyo/systemjs.sh/compare/v1.14.7...v1.14.8) (2024-02-27)


### Bug Fixes

* ensure clearing of performance is done after response is created ([2346ab3](https://github.com/esroyo/systemjs.sh/commit/2346ab352c40828e08955fbc5d6434d536b04920))

## [1.14.7](https://github.com/esroyo/systemjs.sh/compare/v1.14.6...v1.14.7) (2024-02-27)


### Bug Fixes

* clear performance entries once serverTiming is build ([0c912bf](https://github.com/esroyo/systemjs.sh/commit/0c912bf17bac9351d9f3b7f5ec5fef05eef428ae))
* ensure clearing of performance is done at the end ([fe4540f](https://github.com/esroyo/systemjs.sh/commit/fe4540f211313b2c0a09065911e6fbebac85716d))

## [1.14.6](https://github.com/esroyo/systemjs.sh/compare/v1.14.5...v1.14.6) (2024-02-23)

## [1.14.5](https://github.com/esroyo/systemjs.sh/compare/v1.14.4...v1.14.5) (2024-02-23)

## [1.14.4](https://github.com/esroyo/systemjs.sh/compare/v1.14.3...v1.14.4) (2024-02-22)


### Bug Fixes

* correct the calc of the public final url manually ([8859d12](https://github.com/esroyo/systemjs.sh/commit/8859d12b3c0821d7bcd8c30613d525df2486c67d))

## [1.14.3](https://github.com/esroyo/systemjs.sh/compare/v1.14.2...v1.14.3) (2024-02-22)


### Bug Fixes

* correct the calc of the public final url ([0ac6c34](https://github.com/esroyo/systemjs.sh/commit/0ac6c34eb93d57cd93f914237683b868a5d0e983))
* finetune cache write condition ([35ce0f4](https://github.com/esroyo/systemjs.sh/commit/35ce0f4d085823a96da7bd9d842083bc5ccb5122))

## [1.14.2](https://github.com/esroyo/systemjs.sh/compare/v1.14.1...v1.14.2) (2024-02-22)


### Bug Fixes

* cache key should use final canonized url ([e4e787d](https://github.com/esroyo/systemjs.sh/commit/e4e787d833b0d63131cf363f60eee88edc3c5ece))

## [1.14.1](https://github.com/esroyo/systemjs.sh/compare/v1.14.0...v1.14.1) (2024-02-22)


### Bug Fixes

* remove x-forwarded-for header ([e356e4a](https://github.com/esroyo/systemjs.sh/commit/e356e4a0d3aa9828b37674b9083a07b35577d0f2))

## [1.14.0](https://github.com/esroyo/systemjs.sh/compare/v1.13.0...v1.14.0) (2024-02-22)


### Features

* CACHE_CLIENT_REDIRECT will enable a fast-path response ([1cbc475](https://github.com/esroyo/systemjs.sh/commit/1cbc4750b591357fb65a72cde51f55a705b1e177))


### Bug Fixes

* remove upstream Date header ([cd93961](https://github.com/esroyo/systemjs.sh/commit/cd939618a0e13033e403afcb52604c5f630499f7))

## [1.13.0](https://github.com/esroyo/systemjs.sh/compare/v1.12.0...v1.13.0) (2024-02-19)


### Features

* add CACHE_CLIENT_REDIRECT option (default 600) ([dfbbf3e](https://github.com/esroyo/systemjs.sh/commit/dfbbf3e1f77701861fbfaa0d1be17b7a210edfe5))

## [1.12.0](https://github.com/esroyo/systemjs.sh/compare/v1.11.1...v1.12.0) (2024-02-14)


### Features

* perform caching based on upstream max-age (rename env var to CACHE) ([e95ffde](https://github.com/esroyo/systemjs.sh/commit/e95ffde9f4edd4ffd3639168ad87db9844900a33))
* use server-timing API to report duration ([611798b](https://github.com/esroyo/systemjs.sh/commit/611798b5230d51c56aac8f00f0090b245fd56d26))


### Bug Fixes

* only output cache hit/miss if CACHE is enabled ([4c9d25a](https://github.com/esroyo/systemjs.sh/commit/4c9d25ac6f6833f176ea3dbb79cf31b81c7c062e))

## [1.11.1](https://github.com/esroyo/systemjs.sh/compare/v1.11.0...v1.11.1) (2024-02-03)


### Bug Fixes

* typo on toSystemjs ref ([4368246](https://github.com/esroyo/systemjs.sh/commit/43682465156c954b4ec7e9a735e6955e45739675))

## [1.11.0](https://github.com/esroyo/systemjs.sh/compare/v1.10.2...v1.11.0) (2024-02-03)


### Features

* enable usage of rollup@4 ([93cb4ea](https://github.com/esroyo/systemjs.sh/commit/93cb4ea652398cfa41d7b9d7513d329d9ac31b4c))

## [1.10.2](https://github.com/esroyo/systemjs.sh/compare/v1.10.1...v1.10.2) (2024-02-02)


### Bug Fixes

* cache is partitioned by target/user-agent ([9baa3ad](https://github.com/esroyo/systemjs.sh/commit/9baa3ad75cf081e4de1f76ea1483e5ef79d67bce))

## [1.10.1](https://github.com/esroyo/systemjs.sh/compare/v1.10.0...v1.10.1) (2024-02-01)


### Bug Fixes

* make sure BASE_PATH is honored on URL without origin (absolute paths) on dyn imports ([3e3093a](https://github.com/esroyo/systemjs.sh/commit/3e3093ab2272f8e677299da7a09f26ee8f9d81a5))

## [1.10.0](https://github.com/esroyo/systemjs.sh/compare/v1.9.3...v1.10.0) (2024-01-31)


### Features

* enable/disable cache with env var CACHE_MAXAGE ([7336a4d](https://github.com/esroyo/systemjs.sh/commit/7336a4dfe785da5bbae7e737feff93b47265208f))

## [1.9.3](https://github.com/esroyo/systemjs.sh/compare/v1.9.2...v1.9.3) (2024-01-31)


### Bug Fixes

* add header "access-control-allow-origin" is not exists ([4d49deb](https://github.com/esroyo/systemjs.sh/commit/4d49debf8194074e507a0f73632adf7a3cabc9d3))

## [1.9.2](https://github.com/esroyo/systemjs.sh/compare/v1.9.1...v1.9.2) (2024-01-31)


### Bug Fixes

* make sure BASE_PATH is honored on URL without origin (absolute paths) ([8c67c6f](https://github.com/esroyo/systemjs.sh/commit/8c67c6f0473450d55ffb86f58b0add3584691746))

## [1.9.1](https://github.com/esroyo/systemjs.sh/compare/v1.9.0...v1.9.1) (2024-01-31)


### Bug Fixes

* avoid Worker recursion ([e8be08b](https://github.com/esroyo/systemjs.sh/commit/e8be08b8f1fff4308b6c244c57afa533770f59bc))
* enable cache on larger modules ([0b15505](https://github.com/esroyo/systemjs.sh/commit/0b1550526ae776d573680636a09a49e4a7b814b1))

## [1.9.0](https://github.com/esroyo/systemjs.sh/compare/v1.8.1...v1.9.0) (2024-01-31)


### Features

* do code transpilation on worker if possible ([380000f](https://github.com/esroyo/systemjs.sh/commit/380000fedd52c400cc9ab0af759a57b804eb21a9))

## [1.8.1](https://github.com/esroyo/systemjs.sh/compare/v1.8.0...v1.8.1) (2024-01-31)


### Bug Fixes

* handle kv set errors ([14ab7ca](https://github.com/esroyo/systemjs.sh/commit/14ab7ca9c750a463c9f005b38460b733b927aaab))

## [1.8.0](https://github.com/esroyo/systemjs.sh/compare/v1.7.3...v1.8.0) (2024-01-31)


### Features

* implement a simple cache using Kv ([eb4b2e5](https://github.com/esroyo/systemjs.sh/commit/eb4b2e5d565b7163daf5bc0d237335f5d2d0c0ef))

## [1.7.3](https://github.com/esroyo/systemjs.sh/compare/v1.7.2...v1.7.3) (2024-01-30)


### Bug Fixes

* prevent some headers propagation ([53f49f6](https://github.com/esroyo/systemjs.sh/commit/53f49f6683a30764583bcfd7b2e2663b39386de4))

## [1.7.2](https://github.com/esroyo/systemjs.sh/compare/v1.7.1...v1.7.2) (2023-11-24)

## [1.7.1](https://github.com/esroyo/systemjs.sh/compare/v1.7.0...v1.7.1) (2023-11-21)


### Bug Fixes

* ensure custom `X-` headers are not passed to ESM upstream ([da75efd](https://github.com/esroyo/systemjs.sh/commit/da75efdb367d9a015b08122804cbdd08c92d0a68))

## [1.7.0](https://github.com/esroyo/systemjs.sh/compare/v1.6.1...v1.7.0) (2023-11-21)


### Features

* add more debug on final stage ([b480c7d](https://github.com/esroyo/systemjs.sh/commit/b480c7dee035210d9c10b00a98470ba72fbb89df))

## [1.6.1](https://github.com/esroyo/systemjs.sh/compare/v1.6.0...v1.6.1) (2023-11-21)


### Bug Fixes

* handles different hosts on actual request and X-Real-Origin ([3dfc18b](https://github.com/esroyo/systemjs.sh/commit/3dfc18b87a7d9cb50a3fc2083eb780cc737c3936))

## [1.6.0](https://github.com/esroyo/systemjs.sh/compare/v1.5.0...v1.6.0) (2023-11-20)


### Features

* allow to return debug info using `X-Debug` header ([972ac79](https://github.com/esroyo/systemjs.sh/commit/972ac790364dee2824773210c27c6c0c97b4aab5))

## [1.5.0](https://github.com/esroyo/systemjs.sh/compare/v1.4.0...v1.5.0) (2023-11-16)


### Features

* add response `X-Debug-Performance` info ([00586fe](https://github.com/esroyo/systemjs.sh/commit/00586feb58a93b4a0a20fa4c67d5c82c554e461c))

## [1.4.0](https://github.com/esroyo/systemjs.sh/compare/v1.3.1...v1.4.0) (2023-11-16)


### Features

* add repsonse `X-Real-Origin` debug header ([3db9860](https://github.com/esroyo/systemjs.sh/commit/3db9860f25ccaa456aa68e19ef5d0d25ba9f9920))

## [1.3.1](https://github.com/esroyo/systemjs.sh/compare/v1.3.0...v1.3.1) (2023-11-16)


### Bug Fixes

* use X-Real-Origin after homepage redirect discard ([15d26e6](https://github.com/esroyo/systemjs.sh/commit/15d26e62a7e6c9561b8a853eb22a831e2b9dff7e))

## [1.3.0](https://github.com/esroyo/systemjs.sh/compare/v1.2.0...v1.3.0) (2023-11-15)


### Features

* enable option to detect redirections (curl, node, none) ([cae206b](https://github.com/esroyo/systemjs.sh/commit/cae206be0814ed163af49a841e0ed34d9ef49507))

## [1.2.0](https://github.com/esroyo/systemjs.sh/compare/v1.1.1...v1.2.0) (2023-11-14)


### Features

* request may use `X-Real-Origin` header as origin ([0940f91](https://github.com/esroyo/systemjs.sh/commit/0940f910f2b1cc5d6046b163dc1eb544a3264b70))

## [1.1.1](https://github.com/esroyo/systemjs.sh/compare/v1.1.0...v1.1.1) (2023-11-14)

## 1.1.0 (2023-11-14)


### Features

* add new env option for rollup `output.banner` ([2f0017c](https://github.com/esroyo/systemjs.sh/commit/2f0017c22172c0b4c550e7c1d943fee86ccbdc26))
* add support for config BASE_PATH ([7784483](https://github.com/esroyo/systemjs.sh/commit/77844833c9c43097dfe87fd654ffbbceb6afd61b))
* proxy request to esm.sh and convert to systemjs ([6895382](https://github.com/esroyo/systemjs.sh/commit/6895382dabb069901df4444cbc1f01a7934bee7e))
* redirect to ESM_SERVICE_HOST if request empty ([848f62d](https://github.com/esroyo/systemjs.sh/commit/848f62d9c206480b8a2cc3dc3320035f63b3f4c5))


### Bug Fixes

* add error log ([7e3820c](https://github.com/esroyo/systemjs.sh/commit/7e3820caf70f1c278e47b0c5f7b17670275203d2))
* avoid permission denied on Dockerfile build ([aaa75bb](https://github.com/esroyo/systemjs.sh/commit/aaa75bb697f2aefaff2528cce2073a190db9134c))
* forward response headers from ESM_SERVICE_HOST to client ([fcd0abf](https://github.com/esroyo/systemjs.sh/commit/fcd0abf916ce5f0e12689d36e9bbb98111e0751d))
* replace URLs on the response to self hostname ([6823b3d](https://github.com/esroyo/systemjs.sh/commit/6823b3d1681c249d47fa3b32c47a84358693d869))
* typo on header name ([3f43114](https://github.com/esroyo/systemjs.sh/commit/3f431142d3fc0272cc28f4d6dbc2a7cac4e6865b))
* will forward the request to esm.sh keeping parameters ([522f301](https://github.com/esroyo/systemjs.sh/commit/522f3011ee2189e19759410ed923f618d09e597b))
