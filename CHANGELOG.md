# Changelog

## 1.3.0 (2026-03-27)

Full Changelog: [v1.2.0...v1.3.0](https://github.com/avm-codes/sandbox-sdk-python/compare/v1.2.0...v1.3.0)

### Features

* **api:** api update ([2d8989f](https://github.com/avm-codes/sandbox-sdk-python/commit/2d8989f7e3ad2d369faf1005fd790b91af97aa7d))
* **client:** add custom JSON encoder for extended type support ([1bbcad4](https://github.com/avm-codes/sandbox-sdk-python/commit/1bbcad4015bfc5c9e1b4cb276277b6eccad45edb))
* **internal:** implement indices array format for query and form serialization ([da57a67](https://github.com/avm-codes/sandbox-sdk-python/commit/da57a670777e42b61e4550df716a95ce2bbb1426))


### Bug Fixes

* **deps:** bump minimum typing-extensions version ([61bb24a](https://github.com/avm-codes/sandbox-sdk-python/commit/61bb24a5abc2dd9906b9d02aea73460c22b47afb))
* **docs:** fix mcp installation instructions for remote servers ([9fbc1e9](https://github.com/avm-codes/sandbox-sdk-python/commit/9fbc1e9f084e5196ac909c468cde7a2bd9f639cd))
* **pydantic:** do not pass `by_alias` unless set ([2879917](https://github.com/avm-codes/sandbox-sdk-python/commit/2879917991db9053c3a81dabf916fd1236cbbe1f))
* sanitize endpoint path params ([b7ec100](https://github.com/avm-codes/sandbox-sdk-python/commit/b7ec1002bc33cf696eb2303bf1a8d21049676741))


### Chores

* **ci:** skip lint on metadata-only changes ([58304c9](https://github.com/avm-codes/sandbox-sdk-python/commit/58304c9ea8b44629751d04c4b584497976e482d7))
* **ci:** skip uploading artifacts on stainless-internal branches ([cd3408b](https://github.com/avm-codes/sandbox-sdk-python/commit/cd3408b3cfc77217ab411640d8a47c5a4d58bef5))
* format all `api.md` files ([c896c3f](https://github.com/avm-codes/sandbox-sdk-python/commit/c896c3fca5885f8b7183b0ff4c146d179ad6ed9d))
* **internal:** add request options to SSE classes ([10d1816](https://github.com/avm-codes/sandbox-sdk-python/commit/10d18162cd1788341a5abb8799bd9c045220bafc))
* **internal:** bump dependencies ([9433fd2](https://github.com/avm-codes/sandbox-sdk-python/commit/9433fd2c0072bee6e43ab4a37b6ecd5573e348c1))
* **internal:** fix lint error on Python 3.14 ([21bf31b](https://github.com/avm-codes/sandbox-sdk-python/commit/21bf31ba61bffb1cf779e0825ef02c95014c4f63))
* **internal:** make `test_proxy_environment_variables` more resilient ([504ddb9](https://github.com/avm-codes/sandbox-sdk-python/commit/504ddb946b7b4121e30f1ee9896f119166347aa1))
* **internal:** make `test_proxy_environment_variables` more resilient to env ([eb59174](https://github.com/avm-codes/sandbox-sdk-python/commit/eb591746df49fa757b96705935ea9985438752be))
* **internal:** remove mock server code ([fb23c04](https://github.com/avm-codes/sandbox-sdk-python/commit/fb23c0434796b7c7b502dc1598479ac158b3e914))
* **internal:** tweak CI branches ([6759f0c](https://github.com/avm-codes/sandbox-sdk-python/commit/6759f0cdb01c4df3c22df837e72c370618932acf))
* **internal:** update gitignore ([e1273c2](https://github.com/avm-codes/sandbox-sdk-python/commit/e1273c22a35168824182b7d53f4dfc621c4c20a9))
* update mock server docs ([81540d2](https://github.com/avm-codes/sandbox-sdk-python/commit/81540d21efefbc73cbeff74bdd9dc52224652fa6))

## 1.2.0 (2026-01-26)

Full Changelog: [v1.1.0...v1.2.0](https://github.com/avm-codes/sandbox-sdk-python/compare/v1.1.0...v1.2.0)

### Features

* **api:** api update ([dc96fae](https://github.com/avm-codes/sandbox-sdk-python/commit/dc96fae0cd8dd98bce29d7a22cc75dffacf119ba))
* **client:** add support for binary request streaming ([7ad0207](https://github.com/avm-codes/sandbox-sdk-python/commit/7ad0207b84fd0ef013cff6f40c5997992cad897d))


### Bug Fixes

* **types:** allow pyright to infer TypedDict types within SequenceNotStr ([657414c](https://github.com/avm-codes/sandbox-sdk-python/commit/657414cd72a8621599b7337e6f4d84c9d5c460fb))
* use async_to_httpx_files in patch method ([7fb10b4](https://github.com/avm-codes/sandbox-sdk-python/commit/7fb10b4ebf8a224acc16b28d1a87d4a2f6fa94cd))


### Chores

* add missing docstrings ([14cf024](https://github.com/avm-codes/sandbox-sdk-python/commit/14cf0246db08ac7f4351dce523e31eaf4ea6296c))
* **ci:** upgrade `actions/github-script` ([c4dbb81](https://github.com/avm-codes/sandbox-sdk-python/commit/c4dbb81b053c3e236516dd95947ca31a01ff5796))
* **docs:** use environment variables for authentication in code snippets ([efa2e98](https://github.com/avm-codes/sandbox-sdk-python/commit/efa2e985870224e7c161b34b9d6620861bb058eb))
* **internal:** add `--fix` argument to lint script ([6765194](https://github.com/avm-codes/sandbox-sdk-python/commit/6765194e915b9fad7e565b355edf8799de6d4ef5))
* **internal:** add missing files argument to base client ([2c80e10](https://github.com/avm-codes/sandbox-sdk-python/commit/2c80e102c4df21ef4eb8da8fb441eb01a1e578af))
* **internal:** codegen related update ([11f99eb](https://github.com/avm-codes/sandbox-sdk-python/commit/11f99eb59e130f490579644753ca3ad2c58728cd))
* **internal:** update `actions/checkout` version ([39533e0](https://github.com/avm-codes/sandbox-sdk-python/commit/39533e0462c6a6ed774b31ee8c120e52a1c57ff0))
* speedup initial import ([e2dd07a](https://github.com/avm-codes/sandbox-sdk-python/commit/e2dd07add9c0240cb8a7c0d246c73d853f6135f1))
* update lockfile ([36a4ca5](https://github.com/avm-codes/sandbox-sdk-python/commit/36a4ca5a9d1dad261df0bdd1677603158c46261a))


### Documentation

* prominently feature MCP server setup in root SDK readmes ([4fdb9d0](https://github.com/avm-codes/sandbox-sdk-python/commit/4fdb9d0b134ff71bdf848e4a265f1949dcebf59b))

## 1.1.0 (2025-12-01)

Full Changelog: [v1.0.0...v1.1.0](https://github.com/avm-codes/sandbox-sdk-python/compare/v1.0.0...v1.1.0)

### Features

* **api:** api update ([8da21c4](https://github.com/avm-codes/sandbox-sdk-python/commit/8da21c400c602db2fe38be70c8324693625d080a))


### Bug Fixes

* ensure streams are always closed ([85f7b3b](https://github.com/avm-codes/sandbox-sdk-python/commit/85f7b3bb30d7a65867ac231aa28dd931b92233df))


### Chores

* add Python 3.14 classifier and testing ([a0d25a0](https://github.com/avm-codes/sandbox-sdk-python/commit/a0d25a0c99592441305c2ab7d21ea288bd337226))
* **deps:** mypy 1.18.1 has a regression, pin to 1.17 ([409dcc8](https://github.com/avm-codes/sandbox-sdk-python/commit/409dcc828c8307133a1a8da2294c981f23b6b59e))

## 1.0.0 (2025-11-13)

Full Changelog: [v0.0.1...v1.0.0](https://github.com/avm-codes/sandbox-sdk-python/compare/v0.0.1...v1.0.0)

### Chores

* configure new SDK language ([ae1bc06](https://github.com/avm-codes/sandbox-sdk-python/commit/ae1bc06d0c6274651a194a434ae0240467dfc22a))
* update SDK settings ([50385a7](https://github.com/avm-codes/sandbox-sdk-python/commit/50385a71a857af075188c76f4363ef8c880f3b65))
* update SDK settings ([cde1082](https://github.com/avm-codes/sandbox-sdk-python/commit/cde108200bbc0424a6e7acc1d1217f3f5d613a7a))
