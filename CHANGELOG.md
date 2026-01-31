# CHANGELOG

> Package changelog.

<section class="release" id="v0.1.0">

## 0.1.0 (2026-01-31)

<section class="features">

### Features

-   [`211d758`](https://github.com/stdlib-js/stdlib/commit/211d7589cc78cf73556270c7bd8e669537d21799) - update namespace TypeScript declarations [(#5511)](https://github.com/stdlib-js/stdlib/pull/5511)
-   [`2f0aa48`](https://github.com/stdlib-js/stdlib/commit/2f0aa48ef6d561779d4bd4c4a54fe00a5a26c0e1) - update namespace TypeScript declarations [(#5436)](https://github.com/stdlib-js/stdlib/pull/5436)
-   [`be4c7b1`](https://github.com/stdlib-js/stdlib/commit/be4c7b15c13180934e2b962719ab81ec808ea12d) - add `math/array` namespace
-   [`7aa1502`](https://github.com/stdlib-js/stdlib/commit/7aa150232101abdd4b45c713dfaa71811fcdf850) - add `math/array/special`
-   [`6788899`](https://github.com/stdlib-js/stdlib/commit/678889947a970319197de4db6d48bcac3adf224c) - add `math/array/special/abs`
-   [`a4b312d`](https://github.com/stdlib-js/stdlib/commit/a4b312d7b75231f171b3c475d884e17e350f2856) - add `unaryFactory` to namespace
-   [`4b8fd47`](https://github.com/stdlib-js/stdlib/commit/4b8fd47d1f57a0953e24234cddf56ef81d9e01a5) - add `math/array/tools/unary-factory`
-   [`824f294`](https://github.com/stdlib-js/stdlib/commit/824f29485447d0e3224d1fcc784f2355b6b7fd14) - add `math/array/tools` namespace
-   [`683f593`](https://github.com/stdlib-js/stdlib/commit/683f5937fb80b5382d64bf1aacf797d82ed01bb8) - add `math/array/tools/unary`

</section>

<!-- /.features -->

<section class="bug-fixes">

### Bug Fixes

-   [`e051a2f`](https://github.com/stdlib-js/stdlib/commit/e051a2fbf9cb31b562972c20c361a71b6ad837f6) - improve type specificity
-   [`6c571bf`](https://github.com/stdlib-js/stdlib/commit/6c571bf330e3fc293f6ef7c40fcc6bfefcd7f61d) - preserve output array type specificity

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`211d758`](https://github.com/stdlib-js/stdlib/commit/211d7589cc78cf73556270c7bd8e669537d21799): remove `mulf` from `math/base/ops` namespace

    -   To migrate, users should access the same symbol via the `number/float32/base` namespace.

-   [`2f0aa48`](https://github.com/stdlib-js/stdlib/commit/2f0aa48ef6d561779d4bd4c4a54fe00a5a26c0e1): remove `mulf` symbol

    -   To migrate, users should access the same symbol via the `number/float32/base` namespace.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`7899877`](https://github.com/stdlib-js/stdlib/commit/7899877266584eb169e76c2bdda34d886d3668b1) - **refactor:** defensively copy provided dtype arrays _(by Athan Reines)_
-   [`65ddf8d`](https://github.com/stdlib-js/stdlib/commit/65ddf8d4d51ccfda52d1c5a06408e43fb386c27e) - **test:** use .strictEqual() instead of .equal() and fix lint errors _(by Philipp Burckhardt)_
-   [`dd317a4`](https://github.com/stdlib-js/stdlib/commit/dd317a4963fb9c35e1967a4b96556c3b060675c5) - **docs:** fix copy _(by Athan Reines)_
-   [`e051a2f`](https://github.com/stdlib-js/stdlib/commit/e051a2fbf9cb31b562972c20c361a71b6ad837f6) - **fix:** improve type specificity _(by Athan Reines)_
-   [`f81d254`](https://github.com/stdlib-js/stdlib/commit/f81d254ca5fc52dede022955c37aa0c90893969a) - **docs:** fix example _(by Athan Reines)_
-   [`6c571bf`](https://github.com/stdlib-js/stdlib/commit/6c571bf330e3fc293f6ef7c40fcc6bfefcd7f61d) - **fix:** preserve output array type specificity _(by Athan Reines)_
-   [`15e183d`](https://github.com/stdlib-js/stdlib/commit/15e183d2511a067e373aee356f8b36ce5717278a) - **docs:** update namespace TypeScript declarations [(#6242)](https://github.com/stdlib-js/stdlib/pull/6242) _(by stdlib-bot)_
-   [`97ed648`](https://github.com/stdlib-js/stdlib/commit/97ed6482bfa82bba41232501323afca2d7e4d95c) - **docs:** add returns annotations _(by Philipp Burckhardt)_
-   [`3938b26`](https://github.com/stdlib-js/stdlib/commit/3938b265e603116448c89fcaa58df70e79d40f59) - **refactor:** update paths _(by Gururaj Gurram)_
-   [`211d758`](https://github.com/stdlib-js/stdlib/commit/211d7589cc78cf73556270c7bd8e669537d21799) - **feat:** update namespace TypeScript declarations [(#5511)](https://github.com/stdlib-js/stdlib/pull/5511) _(by stdlib-bot)_
-   [`2f0aa48`](https://github.com/stdlib-js/stdlib/commit/2f0aa48ef6d561779d4bd4c4a54fe00a5a26c0e1) - **feat:** update namespace TypeScript declarations [(#5436)](https://github.com/stdlib-js/stdlib/pull/5436) _(by stdlib-bot)_
-   [`9d532b5`](https://github.com/stdlib-js/stdlib/commit/9d532b5510055d80c5df8ba4c8e897c1670dcd1a) - **docs:** update namespace table of contents [(#5438)](https://github.com/stdlib-js/stdlib/pull/5438) _(by stdlib-bot, Philipp Burckhardt)_
-   [`be4c7b1`](https://github.com/stdlib-js/stdlib/commit/be4c7b15c13180934e2b962719ab81ec808ea12d) - **feat:** add `math/array` namespace _(by Athan Reines)_
-   [`7aa1502`](https://github.com/stdlib-js/stdlib/commit/7aa150232101abdd4b45c713dfaa71811fcdf850) - **feat:** add `math/array/special` _(by Athan Reines)_
-   [`98336f5`](https://github.com/stdlib-js/stdlib/commit/98336f5011237a2d607be003f05060146e55d204) - **docs:** fix comment _(by Athan Reines)_
-   [`1e9b650`](https://github.com/stdlib-js/stdlib/commit/1e9b650d29bc3584af013e3ef7d4206dc674b0dd) - **docs:** fix comment _(by Athan Reines)_
-   [`6788899`](https://github.com/stdlib-js/stdlib/commit/678889947a970319197de4db6d48bcac3adf224c) - **feat:** add `math/array/special/abs` _(by Athan Reines)_
-   [`a4b312d`](https://github.com/stdlib-js/stdlib/commit/a4b312d7b75231f171b3c475d884e17e350f2856) - **feat:** add `unaryFactory` to namespace _(by Athan Reines)_
-   [`4b8fd47`](https://github.com/stdlib-js/stdlib/commit/4b8fd47d1f57a0953e24234cddf56ef81d9e01a5) - **feat:** add `math/array/tools/unary-factory` _(by Athan Reines)_
-   [`17a0a25`](https://github.com/stdlib-js/stdlib/commit/17a0a25ecf237da6dcbe7cc0e8f660891b9253aa) - **docs:** fix example _(by Athan Reines)_
-   [`e876c87`](https://github.com/stdlib-js/stdlib/commit/e876c87d1f3f6d8f6a76b600ba7e64704e561154) - **test:** fix assertions _(by Athan Reines)_
-   [`89773d1`](https://github.com/stdlib-js/stdlib/commit/89773d14d1267fc8a4657d02ec978d7f740ecf9f) - **refactor:** rename symbol _(by Athan Reines)_
-   [`824f294`](https://github.com/stdlib-js/stdlib/commit/824f29485447d0e3224d1fcc784f2355b6b7fd14) - **feat:** add `math/array/tools` namespace _(by Athan Reines)_
-   [`683f593`](https://github.com/stdlib-js/stdlib/commit/683f5937fb80b5382d64bf1aacf797d82ed01bb8) - **feat:** add `math/array/tools/unary` _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 3 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Gururaj Gurram
-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

