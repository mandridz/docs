---
id: cli-files-delete
title: Delete file
slug: /cli/commands/files/delete
sidebar_label: delete
---

# Delete file

Delete a file in the remote storage using resource file `<resourcePath>`

### Usage

{% code fullWidth="false" %}
```
spctl files delete <resourcePath> [OPTIONS]
```
{% endcode %}

### Arguments

| **Name**       | **Description**         |
| -------------- | ----------------------- |
| `resourcePath` | Path to a resource file |

### Options

| **Name, shorthand** | **Default**     | **Description**                |
| ------------------- | --------------- | ------------------------------ |
| `--config`          | `./config.json` | Path to the configuration file |
