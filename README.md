# capability-secret-use-scram-sha256

Atomic authority package for `secret/use-scram-sha256`.

- imports: `#{:scram-sha256}`
- effects: `#{:secret :crypto}`
- default policy: `:approval-required`
- provider status: `contract-only`

Importing this package does not grant runtime authority. Tamaki must
request it explicitly and Kototama must admit the sealed envelope.

```sh
clojure -M:test
```
