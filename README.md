# 3HPM Nuvio Wizard v2026 - browser-based setup tool 2026

> **3HPM Nuvio Wizard is a web-based setup helper for Nuvio that streamlines debrid integration, builds scraper manifest URLs, and prepares Comet configuration in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/taylorryan1995/nuvio-wizard-manifest-tool?style=flat-square)](https://github.com/taylorryan1995/nuvio-wizard-manifest-tool)

---

<p align="center">
  <a href="https://taylorryan1995.github.io/nuvio-wizard-manifest-tool/">
    <img src="https://img.shields.io/badge/Download-3HPM%20Nuvio%20Wizard%20Latest-brightgreen?style=for-the-badge" alt="Download 3HPM Nuvio Wizard">
  </a>
</p>

> **[Direct Download - 3HPM Nuvio Wizard v2026](https://taylorryan1995.github.io/nuvio-wizard-manifest-tool/)**

---

[Download Latest Build](https://taylorryan1995.github.io/nuvio-wizard-manifest-tool/)

---

## Overview

3HPM Nuvio Wizard is a browser-first setup utility built to make Nuvio Connected Services easier to configure. It helps assemble scraper manifest URLs, generate Comet configuration details, and keep the resulting setup data concise enough to move between deployments without extra friction.

Since it is delivered as a static web app, you can open it in a browser and get started without installing a full local application. The workflow is intended for users who want a cleaner way to prepare manifests and configuration while avoiding the inclusion of sensitive values in the manifest output itself.

---

## What it does

- Builds scraper manifest URLs for Nuvio-related setups
- Produces Comet configuration output
- Fits the Nuvio Connected Services workflow
- Operates as a browser-based setup helper
- Keeps generated output small and easy to reuse
- Uses Base64 encoding where needed for packaged values
- Runs as a static web app
- Does not embed API keys in the manifest

---

## Getting started

1. Download or clone the repository:
   - `git clone https://github.com/taylorryan1995/nuvio-wizard-manifest-tool.git
2. Serve the project through a web server or deploy it as a static site.
3. Open the primary HTML entry point in your browser.

If you are using the GitHub Pages build, open the latest published link directly and start from there.

---

## How to use it

1. Launch the wizard in your browser.
2. Provide the Nuvio and debrid values needed for your setup.
3. Generate the scraper manifest URL.
4. Check the Comet configuration output.
5. Copy the produced values into the destination service or workflow.

Example workflow:
- Prepare the manifest URL first
- Confirm the configuration values
- Reuse the generated output when the same setup needs to be applied again

---

## Configuration notes

In most cases, configuration is managed from the browser interface instead of a local settings file. For custom or self-hosted deployments, any editable values generally live in the HTML and JavaScript assets that make up the static web app.

Example structure:
- Input fields for service values
- Encoded output for reusable configuration
- Manifest generation logic in the client-side app

---

## Requirements

- A modern web browser
- Static hosting or local file serving for the HTML app
- Network access if your setup depends on online Nuvio or debrid services
- Enough browser storage for standard session data and generated output

---

## FAQ

**How do I get updates?**  
Use the latest release or the published web build whenever new changes are available.

**Where do I change configuration values?**  
Adjust them in the browser inputs, or edit the static app files if you are maintaining a custom deployment.

**What if the output does not look right?**  
Check the entered values, confirm the required services are available, and regenerate the manifest or configuration.

**Can I reuse the generated output?**  
Yes. The tool is designed to keep output compact so it can be copied and reused across compatible setups.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
