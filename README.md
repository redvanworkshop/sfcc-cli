![Logo](docs/img/logo.png "Logo")

SFCC CLI
---

> Command Line Interface for Salesforce Commerce Cloud Sandbox Development

![demo](https://sfcc-cli.s3.amazonaws.com/demo.gif?v=1.1.0)


Introduction
---

Make developing for Salesforce Commerce Cloud work with any IDE on MacOS, Windows, and Linux.

- [X] Easily Manage Multiple Clients & Instances
- [X] Watch for code changes and upload in background ( without being prompted for passwords )
- [X] Support for SFRA JS & CSS Compilers
- [X] Support for Eclipse Build Processes
- [X] Log Viewing with Advanced Search & Filter Capabilities


Developer Overview
---

#### Commands

* [`sfcc setup`](docs/cmd-setup.md) - Setup SFCC Development
* [`sfcc list`](docs/cmd-list.md) - List Configured SFCC Clients
* [`sfcc delete`](docs/cmd-delete.md) - Delete Config for Client
* [`sfcc watch`](docs/cmd-watch.md) - Watch for Changes and Push Updates
* [`sfcc log`](docs/cmd-log.md) - View Logs with Advanced Search & Filter Capabilities
* [`sfcc remote`](docs/cmd-remote.md) - Remote Control for your Sandbox Storefront
* [`sfcc help`](docs/cmd-help.md) - Get Help when you need it

#### Additional Information

* [IDE Setup](docs/ide-setup.md)
* [Troubleshooting](docs/troubleshooting.md)


Install
---

#### Requirements

- [X] [Node v10+](https://nodejs.org/en/download/)

#### Install via NPM

```bash
npm install -g sfcc-cli --no-optional
sfcc setup
```

#### Install via Clone

```bash
cd ~
git clone https://github.com/redvanworkshop/sfcc-cli.git
cd sfcc-cli
npm install -g --no-optional
sfcc setup
```

_Inspired by [dw-cli](https://github.com/mzwallace/dw-cli). Custom Built for RVW Employees._
