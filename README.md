# Issues

Elixir simple example project.
Fetches and displays first `n` issues of a github project.

## Run

1. `$ mix escript.build`
2. `$ ./issues <user> <project> [ count | 4 ]`

### Example
`$ ./issues elixir-lang elixir 10`

Output:
```
number | created_at           | title
-------+----------------------+--------------------------------------------------------------------------------
11706  | 2022-03-16T10:48:35Z | `:for` creates compile-time dependencies when defining protocol implementations
11714  | 2022-03-20T11:34:37Z | Check compile-time dependencies on macros
11715  | 2022-03-21T09:14:09Z | Bring build_embedded: Mix.env() == :prod back to mix new or deep copy syminks
11720  | 2022-03-24T09:15:08Z | Attach Task information on Task.await and other exits
11744  | 2022-04-07T08:49:00Z | Possible bug in compiler emitted warnings about incompatibles types in guard
11753  | 2022-04-10T16:34:11Z | Automatically perform NFC + additions for identifiers
11755  | 2022-04-11T15:56:18Z | Disable debug info and docs chunks by default during tests
11763  | 2022-04-18T16:28:34Z | feat: allow app environment values to contain spaces
11785  | 2022-04-27T12:09:16Z | inet_gethost.exe path error
11788  | 2022-05-01T05:46:19Z | Add ExUnit.rerun/1 to rerun tests.
```
