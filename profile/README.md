<p align="center">
  <img src="https://raw.githubusercontent.com/batchstream/.github/main/profile/assets/banner.svg" alt="BatchStream — One data layer. Many stores." width="100%">
</p>

<p align="center">
  <a href="https://github.com/batchstream/sink#quickstart"><strong>Quickstart</strong></a> &nbsp;·&nbsp;
  <a href="https://github.com/batchstream/sink/blob/main/docs/README.md">Documentation</a> &nbsp;·&nbsp;
  <a href="https://github.com/batchstream/sink-go">Go client</a> &nbsp;·&nbsp;
  <a href="https://github.com/batchstream/sink/releases">Releases</a> &nbsp;·&nbsp;
  <a href="https://batchstream.io">batchstream.io</a>
</p>

### Shared storage, simpler applications.

We build open-source data infrastructure. Our core project, **[Sink](https://github.com/batchstream/sink)**, gives applications one gRPC API to read, write, merge, and query documents across **MongoDB, Elasticsearch, and OpenSearch**.

| Batch by default | Keep native power | Choose your delivery |
| :--- | :--- | :--- |
| Combine small operations into bounded batches. Share connections and control load per store. | Use native queries, explicit JSON/BSON encoding, and atomic Lua merges. | Apply changes synchronously or accept them through a durable Kafka queue. |

### Start with Sink

Bring up a local stack and run an end-to-end check with Docker Compose and Make:

```sh
git clone https://github.com/batchstream/sink.git
cd sink
make quickstart
```

[Explore the architecture →](https://github.com/batchstream/sink/blob/main/docs/architecture.md) &nbsp; [Try the Go client →](https://github.com/batchstream/sink-go#quick-start)

### Built to be checked

Our **[public qualification suite](https://github.com/batchstream/sink-production-suite)** exercises real storage backends, fault recovery, and client/server contracts using synthetic data and disposable infrastructure.

<p>
  <sub>Open source · MIT licensed · <a href="https://github.com/batchstream/sink/blob/main/CONTRIBUTING.md">Contributions welcome</a> · <a href="https://github.com/batchstream/sink/issues">Issues &amp; ideas</a></sub>
</p>
