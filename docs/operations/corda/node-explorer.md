# Node explorer

[The Corda Node Explorer](https://docs.corda.net/node-explorer.html) is a standalone JavaFX application.

With the Corda Node Explorer, you can:

* Find other nodes that are connected to the network.
* View your node's vault and transaction data.
* Execute cash transactions between parties on the network.

## Install the Corda Finance CorDapp on your node

In order to connect to your node using the Node Explorer, you will need Corda's default Finance CorDapp to be installed on the node that you want to explore. This enables basic cash issuance and payment transactions.

1. Download the Corda Finance CorDapp JARs:
    - [Contracts](https://ci-artifactory.corda.r3cev.com/artifactory/corda-releases/net/corda/corda-finance-contracts/4.1/corda-finance-contracts-4.1.jar)
    - [Workflows](https://ci-artifactory.corda.r3cev.com/artifactory/corda-releases/net/corda/corda-finance-workflows/4.1/corda-finance-workflows-4.1.jar)

2. [Install](/operations/corda/installing-a-cordapp) the Corda Finance CorDapp contracts and workflows on your node.

## Install and run the Node Explorer

1. Install Java 8 on your machine. See [Set-up instructions](https://docs.corda.net/getting-set-up.html#set-up-instructions).

2. Download `corda-tools-explorer-4.1.jar`:

``` sh
wget https://ci-artifactory.corda.r3cev.com/artifactory/corda-releases/net/corda/corda-tools-explorer/4.1/corda-tools-explorer-4.1.jar
```

3. Run the Node Explorer:

``` sh
java -jar corda-tools-explorer-4.1.jar
```

## Connect to your node

In the Node Explorer UI, provide the RPC hostname and port, and your node credentials.

See [View node access and credentials](/platform/view-node-access-and-credentials).

::: tip See also

* [Tools](/operations/corda/tools)
* [Installing a CorDapp](/operations/corda/installing-a-cordapp)

:::