# Changes

-   Fixed `runTestCases` function: In the main repo, there's a redundant call to
    compile the solution file, which remarkably increases execution time.
-   Output channel won't gain focus.
-   Added support for placeholders. The table below shows the possible
    placeholders and what they will expand to.

    |    Placeholder    |     Expands to      |
    | :---------------: | :-----------------: |
    | `{{problemName}}` | The problem's name  |
    | `{{problemURL}}`  |  The problem's URL  |
    |    `{{time}}`     | Current date & time |
