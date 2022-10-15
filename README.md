# The Pomegranate Router

## Abstract

*TPR is an anonymous, decentralized routing protocol. Its purpose is to route a message from Alice to Bob, without Charlotte being able to read the message or discover both parties at the same time. It does not depend directly on encryption for keeping the data secure in transit, and only uses it to protect the identity of the endpoint and validate the identity of the nodes. It routes the message in chunks and the server must rebuild the message once it arrives. Thus, it is needed to use different techniques for making it resilient, like error correction and hash functions. TPR focuses on fragmented and decentralized networks similar to blockchains, and this plus other features render TPR virtually invulnerable to predecessor attacks. TPR provides many of the benefits of Quick UDP Internet Connection (QUIC) while having the reliability of a traditional TCP/IP connection, with the only inconvenience of the higher latency because of the nodes.*

# The full paper
The PDF is on the repo, enjoy. I also included the ODT, feel free to fork the repo and modify it. Later on you can your name to the cover and issue a PR (except if there's an *et al*, that means this went too wild and there was no space for more names).

# License

The paper is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit https://creativecommons.org/licenses/by-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

The code will be licensed under the Mozilla Public License 2.0. To view a copy of this license, visit https://www.mozilla.org/en-US/MPL/2.0/.