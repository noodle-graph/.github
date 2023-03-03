# Noodle 🍜

***Architecture diagram that maintains itself.***

Noodle is an open-source project designed to simplify the process of understanding and visualizing complex system architectures.
It offers automated architecture diagram generation, graph filtering, user-friendly UI features, and a friendly CLI, making it easy to deploy and use.
Additionally, Noodle is reliant on the best source of truth, which is the code itself, by linking to the source code of the relationships.

<img src="https://github.com/noodle-graph/monorepo/blob/master/docs/img/basicExampleGraph.png" width="400" alt="example"/>

[![Node.js CI](https://github.com/noodle-graph/monorepo/actions/workflows/node.js.yml/badge.svg)](https://github.com/noodle-graph/monorepo/actions/workflows/node.js.yml)
[![Node.js Package](https://github.com/noodle-graph/monorepo/actions/workflows/npm-publish.yml/badge.svg)](https://github.com/noodle-graph/monorepo/actions/workflows/npm-publish.yml)

---

## Quick start

### 1. Install

```bash
npm install --location=global @noodle-graph/cli
```

### 2. Add [Noodle comments](https://github.com/noodle-graph/monorepo/blob/master/packages/scanner/README.md#noodle-comment)

[Simple example](https://github.com/noodle-graph/monorepo/blob/master/examples/basic/someService/index.js)

### 3. Create [config file](https://github.com/noodle-graph/monorepo/blob/master/packages/cli/README.md#scan-config-file)

[Simple example](https://github.com/noodle-graph/monorepo/blob/master/examples/basic/noodle.json)

### 4. `noodle run --open`

## Contributing

See [CONTRIBUTING.md](https://github.com/noodle-graph/monorepo/blob/master/CONTRIBUTING.md)
