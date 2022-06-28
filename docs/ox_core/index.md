---
title: Getting started
sidebar_position: 1
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

:::caution

This resource is **not production ready**. Breaking changes are guaranteed, and support is limited.  
Documentation may fall behind and be rendered obsolete.

:::

## Setup

We **strongly** recommend using Git to help with version control and separating your own changes from the original source code.  
Refer to [GitHub's guide to setting up Git](https://docs.github.com/en/get-started/quickstart/set-up-git#setting-up-git). You can also download a Git GUI client, such as [GitKraken](https://www.gitkraken.com/), to improve your workflow and more easily maintain changes.

### Dependencies

- [oxmysql](https://github.com/overextended/oxmysql/)
- [ox_lib](https://github.com/overextended/ox_lib/)
- [ox_inventory](https://github.com/overextended/ox_inventory)

### Optional dependencies

- [npwd](https://github.com/project-error/npwd)

### Installation

<Tabs>
<TabItem value="1" label="Recommended">

- [Download](https://www.nodejs.org/) and install the LTS version of Node.js 16.
- Open a terminal, command prompt, etc. and navigate to your resources folder.
- Execute the following commands

```
npm install --location=global pnpm
git clone https://github.com/overextended/ox_core.git
cd web
pnpm i
pnpm build
```

</TabItem>
<TabItem value="2" label="Lazy">

- Download a tagged [release](https://github.com/overextended/ox_core/releases).

</TabItem>
</Tabs>


## Convars

| Name | Default | Replicated |
|------|------------|---------|
| ox:primaryIdentifier | fivem | false