# reg

> Manage the Windows Registry.
> Some subcommands such as `add`, `delete`, `query`, `export` and `import` have their own usage documentation.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/reg>.

- Add a new registry key or value:

`reg add {{key_name}}`

- Delete a registry key or value:

`reg delete {{key_name}}`

- Query the registry for specific keys or values:

`reg query {{key_name}}`

- Export a part of the registry to a file:

`reg export {{key_name}} {{path\to\file.reg}}`

- Import a registry file into the system:

`reg import {{path\to\file.reg}}`

- Copy a registry key to another location:

`reg copy {{source_key}} {{destination_key}}`

- Save a registry key and its subkeys to a hive file:

`reg save {{key_name}} {{path\to\file.hiv}}`

- Display detailed help for a specific subcommand:

`reg {{subcommand}} /?`
