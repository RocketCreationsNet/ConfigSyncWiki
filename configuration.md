---
description: Learn how to configure the plugin
---

# Configuration

## Scheduler

The scheduler is a task that is automatically scheduled to sync every file every 5 minutes. You can enable and disable it from the configuration file.

## MySQL

The mysql section contains all the data of the database storage.\
As explained in the configuration, the main server is the one where the files are copied from

## Files

The file section is a list of files to sync. It requires the following schema:

```yaml
files:
  Plugin:
    - "file.yml"
```

Instead of the file name you can just put `*` to sync all the files of a plugin.
