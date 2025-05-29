# Contribution Guide

Thank you for wanting to contribute to the Apple Passwords extension compatibility list! Your observations are invaluable to the community.

## How to Contribute

1. **Fork** the repository.
2. **Clone** the forked repository to your local machine.
3. Create a new branch for your changes: `git checkout -b my-compatibility-contribution`
4. Open the `COMPATIBILITY.md` file.
5. **Add a new row to the compatibility table** or modify an existing row if you have new information or a correction.
    * **Ensure the information is as precise as possible.** When adding or updating an entry, please fill out all columns carefully:
        * **Operating System** (e.g., `macOS Sequoia 15.5`, `Windows 11 23H2`, `macOS Sonoma 14.4`)
        * **Browser** (e.g., `Google Chrome`, `Microsoft Edge`, `Brave Browser`, `Arc`, `Mozilla Firefox`)
        * **Browser Engine** (e.g., `Chromium`, `Gecko`, `WebKit` - if known)
        * **Browser Version** (the exact version number, e.g., `137.0.7151.56`)
        * **Extension Version** (the exact version of the Apple Passwords extension, e.g., `3.0.10`)
        * **Install** (`✅`, `⚠️`, `❌`, `❓` - using the legend, indicates if the extension successfully installs)
        * **Auto-fill** (`✅`, `⚠️`, `❌`, `❓` - using the legend, indicates if the auto-fill functionality works)
        * **Issues / Notes / Solutions** (Clearly describe any problems encountered, steps to reproduce them, or solutions/workarounds found. For example: "Auto-fill cannot be enabled," "Login forms do not detect saved passwords," "Resolved by reinstalling the extension.")
        * **Date Tested** (format `YYYY-MM-DD`)
        * **Contributor** (`@your_github_username`)

6. **Save** your modifications.
7. **Commit** your changes with a clear and concise message. Good examples:
    * `git commit -m "Add compatibility for Windows 11 - Chrome"`
    * `git commit -m "Update compatibility for macOS Sequoia - SigmaOS (Auto-fill fix)"`
8. **Push** your branch to your forked repository: `git push origin my-compatibility-contribution`
9. Open a **Pull Request (PR)** towards the `main` branch of the original repository. In the PR description, summarize your changes and any relevant context.

## Directives

* **Precision**: Provide information as accurately and completely as possible. Include exact versions of the operating system, browser, and extension.
* **Clarity**: If you are reporting an issue, describe the steps to reproduce it. If you have a solution or workaround, describe it clearly.
* **Objectivity**: Keep your comments factual and objective.
* **Formatting**: Please respect the existing table formatting in `COMPATIBILITY.md`. Ensure new rows align correctly with the columns.
* **Legend Adherence**: Use the `✅`, `⚠️`, `❌`, `❓` symbols consistently as defined in the legend for the "Install" and "Auto-fill" columns.

Thank you for helping us build a comprehensive resource for the community!
