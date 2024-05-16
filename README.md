<p align="center">
    <h1 align="center">✨ ScoopType ✨</h1>
</p>

<p align="center">
    <a href="README.md">English</a> |
    <a href="README-CN.md">简体中文</a> |
    <a href="https://github.com/abgox/ScoopType">Github</a> |
    <a href="https://gitee.com/abgox/ScoopType">Gitee</a>
</p>

<p align="center">
    <a href="https://github.com/abgox/ScoopType/blob/main/LICENSE">
        <img src="https://img.shields.io/github/license/abgox/ScoopType" alt="license" />
    </a>
    <a href="https://img.shields.io/github/repo-size/abgox/ScoopType.svg">
        <img src="https://img.shields.io/github/repo-size/abgox/ScoopType.svg" alt="code size" />
    </a>
    <a href="https://github.com/abgox/ScoopType">
        <img src="https://img.shields.io/badge/created-2024--1--10-blue" alt="created" />
    </a>
</p>

---

## Introduce

-   Provide friendly prompts and verification when writing app manifests.

---

-   [What is Scoop?](https://github.com/ScoopInstaller/Scoop)
-   [What is App-Manifests in Scoop?](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)

## How to use

-   When writing an app manifest, adding the following attributes can get prompts and validations from the editor.

    > Recommend using [vscode](https://code.visualstudio.com)

    -   The first way: Add this property directly in json file.
        ```json
        "$schema": "https://abgox.github.io/ScoopType/schema/en-US-min.json",
        ```
    -   The second way: It can be added in the vscode configuration file (settings.json), which will apply to all matching json files.

        -   If you're not using vscode, you'll need to look up the official configuration method for the editor you're using

        ```json
        "json.schemas": [
                {
                    "url": "https://abgox.github.io/ScoopType/schema/en-US-min.json",
                    "fileMatch": [
                        "bucket/**/*.json",
                        "deprecated/**/*.json"
                    ]
                }
            ]
        ```

    -   The second way is recommended. It isn't intrusive on the original json file.

-   Url (Remove the `-min` from the file name, which means the uncompressed file.)

    -   `https://abgox.github.io/ScoopType/schema/zh-CN-min.json`

    -   `https://abgox.github.io/ScoopType/schema/en-US-min.json`

## Demo

![Demo](https://abgop.netlify.app/ScoopType/demo.gif)
