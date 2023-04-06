# Anti Duplication

## How can we ensure that each card is received once and only once?

To make sure cards are received only one time, there must be protocols in place which dictate the ways the cards can move. 
- It may be a concern that once the index card reaches the target, the target passes it along. In that case, a protocol must be put in place so that the receiver must take in the index card and not be able to send it off. 
- If the concern is that the packet may get lost and never end up at the receiver, then there must be fail-safes for when nodes don't perform their job correctly. 
- If the concern is that multiple of the same packet may get sent to the receiver, then each packet can have a way to be uniquely identified, then there may be a protocol which says to never take in packets with the identification. 
