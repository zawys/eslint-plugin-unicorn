# Snapshot report for `test/prefer-trim-start-end.js`

The actual snapshot is saved in `prefer-trim-start-end.js.snap`.

Generated by [AVA](https://avajs.dev).

## prefer-trim-start-end - #1

> Snapshot 1

    `␊
    > 1 | foo.trimLeft()␊
        | ^^^^^^^^^^^^^^ Prefer `String#trimStart()` over `String#trimLeft()`.␊
    `

## prefer-trim-start-end - #2

> Snapshot 1

    `␊
    > 1 | foo.trimRight()␊
        | ^^^^^^^^^^^^^^^ Prefer `String#trimEnd()` over `String#trimRight()`.␊
    `