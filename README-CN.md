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

## 介绍

-   给 Scoop 应用清单(App-Manifests)的编写提供友好的提示和校验

---

-   [什么是 Scoop ？](https://github.com/ScoopInstaller/Scoop)
-   [什么是 Scoop 中的应用清单(App-Manifests) ？](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)

## 使用

-   在编写应用清单时，添加以下属性就可以获得来自编辑器的提示和校验

    > 推荐使用 [vscode](https://code.visualstudio.com)

    ```json
    "$schema": "https://raw.githubusercontent.com/abgox/ScoopType/main/schema/zh-CN-min.json"
    ```

-   URL

    -   移除文件名中的 `-min`，就是未压缩文件

    -   `https://raw.githubusercontent.com/abgox/ScoopType/main/schema/zh-CN-min.json`

    -   `https://raw.githubusercontent.com/abgox/ScoopType/main/schema/en-US-min.json`

## Demo

![Demo](https://abgop.netlify.app/ScoopType/demo.gif)
