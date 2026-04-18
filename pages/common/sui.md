# sui

> The Sui node runner and platform CLI.
> Some subcommands such as `client`, `console`, `move`, `keytool`, `validator`, and `genesis` have their own usage documentation.
> More information: <https://docs.sui.io/references/cli>.

- Connect to a Sui network using the default or existing configuration:

`sui client`

- Open an interactive console for the Sui client:

`sui console`

- Manage Move projects and source code:

`sui move {{build|test|new|...}}`

- Manage cryptographic keys and addresses:

`sui keytool {{generate|import|...}}`

- Manage a Sui validator node:

`sui validator {{make-validator-info|...}}`

- Manage and generate the genesis state for a Sui network:

`sui genesis {{...}}`

- Display help for a specific subcommand:

`sui {{subcommand}} --help`
