@opcua/for-node-red  (Preview Version)

:rotating_light: this product is currently provided as beta version. 


This node is the second next generation OPCUA Node for NodeRED build by Sterfive, the company that develops the [NodeOPCUA](https://node-opcua.github.io/) stack.

Ir brings the following OPCUA Client features 
- Read
- Write
- Browse
- Monitor
- Call

The community edition works with one connection to one OPCUA server and can hanldes up to 100 simulatenous operation per nodes. 

The professional edition works with multiple connections to multiple OPCUA servers and have no limitation on the number of simultaneous operations per nodes, exxcept the one imposed by the OPCUA server itself.

It has been designed with the following goals in mind:

- easy to use, easy to configure; no deep OPCUA knowledge required.
- provide visual tools to pick up nodeId by browsing the OPCUA server
- handle nodes address with either nodeId or browse path, or both. 
- works well with complex OPCUA servers, exposing complex data structures (extension objects)
- arbitraty number of node sharing the same connection
- support for multiple connections to multiple OPCUA servers.
- handles automatically transactions optimisation by grouping or splitting operations based on actual OPCUA server capabilities.
- handles automatically reconnections in case of network failure, in a way that works
- do not consume Client session unexpectedly on the OPCUA server side.
- handles automatically OPCUA server certificate management

## Getting Started 

To install the node execute the following command inside the `.node-red`` directory:

```console
npm install @opcua/for-node-red
```

### how to use

see the [documentation](./DOC.md) guide for more information



## Getting access to the professional edition

- send your request to contact@sterfive.com to claim access to the professional edition 
 
 
## Copyright and Licence

Copyrigth (c) Sterfive SAS 2017-2023, under [proprietary licence](./LICENSE.md).

