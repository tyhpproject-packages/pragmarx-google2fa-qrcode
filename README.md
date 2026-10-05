<!-- tyhp-readme:start -->
# tyhpdef/pragmarx-google2fa-qrcode

Tyhp type definitions for `pragmarx/google2fa-qrcode` `4.0.0`.

```bash
composer require --dev tyhpdef/pragmarx-google2fa-qrcode:4.0.0
```

This is a metapackage. Composer also installs `tyhpdef/pragmarx-google2fa-qrcode-impl` (type files).
Require **this** name, not `tyhpdef/pragmarx-google2fa-qrcode-impl`.

See https://tyhplang.com.

## Maintain `pragmarx/google2fa-qrcode`? Ship the types yourself

If you are a Packagist maintainer of `pragmarx/google2fa-qrcode`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/pragmarx-google2fa-qrcode-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `pragmarx/google2fa-qrcode` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/pragmarx-google2fa-qrcode": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `pragmarx/google2fa-qrcode` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `pragmarx/google2fa-qrcode` with a real constraint,
   `"replace": { "tyhpdef/pragmarx-google2fa-qrcode": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `pragmarx/google2fa-qrcode` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/pragmarx-google2fa-qrcode` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
