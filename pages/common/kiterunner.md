# kiterunner

> A tool for discovering API endpoints and performing brute-force API attacks.
> Some subcommands such as `scan` and `brute` have their own usage documentation.
> More information: <https://github.com/assetnote/kiterunner>.

- Perform a brute-force attack using a specified wordlist:

`kr brute {{url}} -w {{path/to/wordlist}}`

- Scan an API using a kite file:

`kr scan {{url}} -A {{path/to/file.kite}}`

- Preform an actively scanning attack:

`kr scan {{url}} -w {{path/to/wordlist}}`

- Convert a normal payload to a kite file for faster performance:

`kr kb compile {{path/to/payload_file}} --out-file {{path/to/output_file.kite}}`

- Get comprehensive information about Kitebuilder's supported types and schema:

`kr kb info`

- Display help for a subcommand:

`kr {{brute|scan|kb}} --help`
