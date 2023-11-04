# Intelops Frontend

Stay future-ready with our market-first SaaS 2.0 solution that simplifies cloud-native technology,
enhances software supply chain security, and empowers businesses to scale for growth.

## Getting started

To make it easy for you to get started with GitHub, here's a list of recommended next steps.

## Table of Contents

- [Intelops](#Intelops)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [Demo](#demo)
  - [Features](#features)
  - [Installation](#installation)
  - [Common UI Installation](#common-ui-installation)
    - [Personal Access Token](#generate-personal-access-token)
    - [Publish Common UI Module](#publish-common-ui-package)
    - [How to use Common UI Module](#use-common-ui-package)
  - [Support](## Support)
  - [Support](## Support)
  - [Authors and acknowledgment](#authors-and-acknowledgment)
  - [Contributing](#contributing)
  - [License](#license)

## About

Stay future-ready with our market-first SaaS 2.0 solution that simplifies cloud-native technology,
enhances software supply chain security, and empowers businesses to scale for growth.

## Demo

https://alpha.intelops.app/login

## Features

List the key features and functionalities of your project. You can use bullet points for this.

- Optimizor
- Capten
- Management

## Installation

Provide step-by-step instructions on how to install and set up your project. You can include code snippets or commands if needed.

    1. git clone git@github.com:intelops/intelops-frontend.git
    2. cd intelops-frontend
    3. yarn install
    4. yarn run dev

## Common UI Installation
    1. npm login (from intelops front end root directory)

	2. Pls add the following in .npmrc @intelops:registry=https://npm.pkg.github.com/

	3. Mention version in package.json "@intelops/intelops_ui": "1.0.3"

### Personal Access Token

    How to Generate a personal access token:

    To authenticate with GitHub Package Registry, you'll need a personal access token.

    1. Login to intelops github account 
    2. Go to your GitHub settings, navigate to "Developer settings",
    3. Then "Personal access tokens." Generate a new token with the write:packages scope.

### Publish Common UI Module

    1. Create a .npmrc file inside the root directory of Common ui Repo 
        Repo Link : https://github.com/intelops/ui-templates-common-repo
    2. add the below two lines in npmrc file 
        registry=https://npm.pkg.github.com
        auth_token={Personal access token created using intelops private github account}
    3. If any new changes need to be published, update the package version in package.json file 
    4. open terminal and type npm login then enter
    5 Provide your private github user name and password (access token)
    6. Once after successfull login , execute npm publish command

### How to use Common UI Module

    1. Create a .npmrc file inside the root directory of Common ui Repo 
       Repo Link : https://github.com/intelops/ui-templates-common-repo
    2. add the below two lines in npmrc file 
       registry=https://npm.pkg.github.com
       auth_token={Personal access token created using intelops private github account}
    3. add the below package in intelops front end package.json file like below
       "@intelops/intelops_ui": "0.0.2"
    4. then install the package using npm install or yarn install
       npm install @intelops/intelops_ui@latest or 
       yarn add @intelops/intelops_ui@latest --registry=https://npm.pkg.github.com
    5. once after package installation, please make sure the latest version of 
       common ui package is installed under node_modules folder  


## Support

Tell people where they can go to for help. It can be any combination of an issue tracker, a chat room, an email address, etc.

## Contributing

State if you are open to contributions and what your requirements are for accepting them.

For people who want to make changes to your project, it's helpful to have some documentation on how to get started. Perhaps there is a script that they should run or some environment variables that they need to set. Make these steps explicit. These instructions could also be useful to your future self.

You can also document commands to lint the code or run tests. These steps help to ensure high code quality and reduce the likelihood that the changes inadvertently break something. Having instructions for running tests is especially helpful if it requires external setup, such as starting a Selenium server for testing in a browser.

## Authors and acknowledgment

Show your appreciation to those who have contributed to the project.

## License

For open source projects, say how it is licensed.
 