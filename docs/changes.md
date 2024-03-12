# Changes

-   Fixed **_`runTestCases`_** function: This function runs upon hitting the
    hotkey for running and judging the soluion. There used to be a redundant
    compile call for the solution. It's been removed now.
-   Fixed the **_output window's focus_** issue: The output window will no
    longer take focus when it pops up, for example, on compilation errors.
-   Added support for **_placeholders_**. The table below shows the possible
    placeholders and what they will expand to.

    |    Placeholder    |     Expands to      |
    | :---------------: | :-----------------: |
    | `{{problemName}}` | The problem's name  |
    | `{{problemURL}}`  |  The problem's URL  |
    |    `{{time}}`     | Current date & time |
