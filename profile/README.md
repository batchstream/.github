<p align="center">
  <img src="https://raw.githubusercontent.com/batchstream/.github/main/profile/assets/banner.svg" alt="BatchStream — One data layer. Many stores." width="100%">
</p>

<p align="center">
  <a href="https://github.com/batchstream/weir#build-and-run"><strong>Get started</strong></a> &nbsp;·&nbsp;
  <a href="https://github.com/batchstream/weir/tree/main/docs">Documentation</a> &nbsp;·&nbsp;
  <a href="https://github.com/batchstream/weir-go">Go SDK</a> &nbsp;·&nbsp;
  <a href="https://github.com/batchstream/weir-charts">Helm chart</a> &nbsp;·&nbsp;
  <a href="https://github.com/batchstream/weir-tests">System tests</a>
</p>

### Shared storage, simpler applications.

We build open-source data infrastructure. Our core project, **[Weir](https://github.com/batchstream/weir)**, combines concurrent database requests into bounded batches for **MongoDB, Elasticsearch, and OpenSearch**.

| Batch by default | Keep native power | Bound every resource |
| :--- | :--- | :--- |
| Concurrent single-record writes become native MongoDB `bulkWrite` and Search `_bulk` calls over a small set of connections shared per Store. | Use typed reads and mutations, Lua transforms, and native backend commands. | Static queue, batch, stream, and message limits bound memory. Full queues apply backpressure. |

### Start with Weir

Build the server from source with Go, then point it at your stores:

```sh
git clone https://github.com/batchstream/weir.git
cd weir
go build -o bin/weir ./cmd/weir
cp config/weir.reference.yaml weir.yaml
```

[Explore the architecture →](https://github.com/batchstream/weir/blob/main/docs/architecture.md) &nbsp; [Try the Go SDK →](https://github.com/batchstream/weir-go#connect-and-read)

### Built to be checked

**[weir-tests](https://github.com/batchstream/weir-tests)** runs independent blackbox integration tests, soak tests, and paired direct-versus-Weir throughput comparisons on owned fixtures, using only the published SDK and protocol.

### Also from BatchStream

**[Sink](https://github.com/batchstream/sink)** gives applications one gRPC API across the same stores, with optional Kafka-backed asynchronous delivery. See also its [Go client](https://github.com/batchstream/sink-go) and [qualification suite](https://github.com/batchstream/sink-production-suite).

<p>
  <sub>Open source · MIT licensed · <a href="https://github.com/batchstream/weir/blob/main/CONTRIBUTING.md">Contributions welcome</a> · <a href="https://github.com/batchstream/weir/issues">Issues &amp; ideas</a></sub>
</p>
