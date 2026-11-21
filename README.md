# lab-status-data

Public, read-only status snapshot for <https://cauz.is-a.dev/lab>.

`status.json` is regenerated on a home server every minute from an allowlist of public-safe
fields (friendly service names, states, percentages and ages) and checked by a leak guard
before it is pushed. The server only makes outbound connections; nothing here can reach it.

History is intentionally a single commit that is replaced on every update.
