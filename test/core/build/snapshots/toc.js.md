# Snapshot report for `test/core/build/toc.js`

The actual snapshot is saved in `toc.js.snap`.

Generated by [AVA](https://ava.li).

## should generate a table of content based on the content headings

> Snapshot 1

    `-   [Package Name](#package-name)␊
        -   [Installation](#installation)␊
        -   [API](#api)␊
            -   [processor.use(stringify, options)](#processorusestringify-options)␊
            -   [stringify.Compiler](#stringifycompiler)␊
        -   [License](#license)␊
    `

## should use existing table of content if it is already present on the content

> Snapshot 1

    `-   [API definition](#api)␊
    -   [License](#license)␊
    `
