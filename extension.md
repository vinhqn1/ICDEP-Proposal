# Extension

## How can we add additional features to the protocol without breaking previous functionality?

An extension would be to add the capability for having metadata with each packet. This metadata could be altered at every node that the packet passes through to give the client and server more information about their traffic.

This metadata extension would fulfill the needs of the last two listed extensions:
- Send to any individual on the whole UW campus
- Specify whether contents are ASCII text, Unicode text, or binary values
- Keep a record of what nodes the card has passed through.

The client would be able to dictate what type of data is in the contents of the packet in the metadata for the server to understand.
Whenever a packet passes through a node, the node could add its information to the metadata which would create a list of nodes that the packet has passed through.

To be able to send to any individual on the whole UW campus, there needs to be an address system to be able to direct the packet to the person. In the in class example, packets are simply addressed to a single person which all of the nodes know. A more complex address system would need to be implemented, perhaps with location information like having building and room number. 
