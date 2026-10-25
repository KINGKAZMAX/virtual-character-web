# Virtual Character

Public web release: <https://kingkazmax.github.io/virtual-character-web/>

This repository contains compiled website assets and the GitHub Pages deployment workflow.
Application source stays in a separate private repository.
API keys and XiaoZhi device credentials stay on the server.

`release-manifest.json` lists the source revision, public origins, files, and SHA-256 checksums.
The workflow joins the numbered archive chunks, verifies every checksum, and deploys the extracted website.
The website uses hash routes so navigation works on GitHub Pages.

The application is based on [Project AIRI](https://github.com/moeru-ai/airi), licensed under MIT.
Character assets retain their separate license terms in the application review page.
XiaoZhi voice is for learning demos under the accepted service agreement.
