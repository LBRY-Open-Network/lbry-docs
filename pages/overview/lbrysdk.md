While the blockchain is the innovation that makes LBRY _possible_, the [Data Network](https://spec.lbry.com#data) is the layer that actually makes the blockchain _useful_.

At this level:

- [Metadata](https://spec.lbry.com#metadata) stored in the blockchain is interpreted and validated.
- [Data referenced by metadata](https://spec.lbry.com#data) is accessed and distributed via a peer-to-peer network.
- [Identities](https://spec.lbry.com#channels) are created, signed, and validated.

Data network operations are provided by the [lbrysdk](https://github.com/lbryio/lbry-sdk). This SDK also provides local wallet functionality and a set of APIs to facilitate building applications.

### Additional Resources

- The [Specification](https://spec.lbry.com "Specification") contains a comprehensive specification of data network operations.
- [Resources](/resources) has further documentation on the LBRY SDK, including its APIs.
- [Build](/build) teaches you how to create your own app.
- [Contribute](/contribute) guides you on how to improve the protocol itself.
