# Open edX Theme for use with Residential MITx

## Branches:

| branch                                                         | description                                                                              |
|----------------------------------------------------------------|------------------------------------------------------------------------------------------|
| [dogwood](https://github.com/mitodl/mitx-theme/tree/dogwood)   | OBSOLETE theme for the dogwood release of Residential MITx                               |
| [ficus](https://github.com/mitodl/mitx-theme/tree/ficus)       | OBSOLETE theme for use with the `mitx-ficus` release for Residential MITx                |
| [ginko](https://github.com/mitodl/mitx-theme/tree/ginko)       | theme for use with the `mitx-ginko` release, on https://lms.mitx.mit.edu                 |
| [hawthorn](https://github.com/mitodl/mitx-theme/tree/hawthorn) | theme for use with the `mitx-hawthorn` release, on https://lms.mitx.mit.edu              |
| [ironwood](https://github.com/mitodl/mitx-theme/tree/ironwood) | theme for use with the `ironwood` release, on https://lms.mitx.mit.edu                   |
| [master](https://github.com/mitodl/mitx-theme/tree/master)     | currently for use with the `mitx-hawthorn` release, on https://mitx-qa-next.mitx.mit.edu |
| [koa](https://github.com/mitodl/mitx-theme/tree/koa)           | This branch is to be used with Open edX's koa release                                   |

### Mitx theme configuration

To configure `mitx-theme` for Open edX you can follow the same steps provided in [MIT xPRO theme](https://github.com/mitodl/mitxpro-theme/blob/master/README.md) except for below steps where you would need `mitx-theme` specific values:

1. You don't need to set `XPRO_BASE_URL` mentioned in above link.
2. While following steps in [Apply mitxpro-theme](https://github.com/mitodl/mitxpro-theme/blob/master/README.md#apply-mitxpro-theme) please use
`mitx-theme` instead of `mitxpro-theme`.
3. In [Compiling a theme](https://github.com/mitodl/mitxpro-theme/blob/master/README.md#compiling-a-theme) you need to use `mitx-theme` e.g.
    ```
    $ make lms-shell
    $ paver update_assets --themes mitx-theme
    ```

