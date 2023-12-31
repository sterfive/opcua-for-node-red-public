@opcua/for-node-red  (Preview Version)

__this product is currently provided as a beta version.__


This node is the second next-generation OPCUA Node for NodeRED built by Sterfive, the company that develops the [NodeOPCUA](https://node-opcua.github.io/) stack.

Ir brings the following OPCUA Client features. 
- **Read**   - read one or more UAVariables.
- **Write**  - write one or more UAVariables.
- **Browse**  - browse a UANode for references and child nodes.
- **Monitor** - monitor a UAVariable for changes.
- **MonitorEvents** - monitor a UAObject for events.
- **Call** - call a method passing input arguments and getting output arguments.
- **Explore** - explore the OPCUA server address space subtree and get information about nodes and references as JSON structure.
 

The community edition works with one connection to one OPCUA server and can handle up to 100 simultaneous operations per node. 

The professional edition works with multiple connections to multiple OPCUA servers and has no limitation on the number of simultaneous operations per node, except the one imposed by the OPCUA server itself.

It has been designed with the following goals in mind:

- easy to use, easy to configure; no deep OPCUA knowledge required.
- provide visual tools to pick up nodeId by browsing the OPCUA server.
- handle nodes address with either nodeId or browse path, or both. 
- works well with complex OPCUA servers, exposing complex data structures (extension objects).
- arbitrary number of nodes sharing the same connection
- support for multiple connections to multiple OPCUA servers.
- automatically handle transaction optimization by grouping or splitting operations based on actual OPCUA server capabilities.
- automatically handle reconnections in case of network failure, in a way that works.
- use Client sessions sparingly on the OPCUA server side.
- handle automatically OPCUA server certificate management.
- explore and monitor complex UAObject structures in the address space with ease.

## Getting Started 

The easiest way to install the nodes is to use the Manage palette option in the Node-RED editor menu. In the Install tab, you can search for the @opcua/for-node-red package and click `install`. Once the installation is complete the nodes are available.

Alternatively, you can install the nodes in your `Node-RED` configuration folder inside the `.node-red`` directory:

```console
cd ~/.node-red
npm install @opcua/for-node-red
```

The nodes will be available after a restart of the Node-RED application.


### how to use

see the [documentation](./DOC.md) guide for more information



## Getting access to the professional edition

- send your request to contact@sterfive.com to claim access to the professional edition 
 
 
## Copyright and Licence

Copyright (c) Sterfive SAS 2017-2023, under [proprietary licence](./LICENSE.md).

