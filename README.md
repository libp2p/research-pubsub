pubsub
======

> Discussions and Planning about getting PubSub on IPFS/libp2p

# tl;dr;

PubSub, or Publish-Subscribe, is an area of research in distributed systems that enables applications to propagate information throughout the network in a structured manner, with or without guarantees like: order, delivery, efficiency, fault tolerance and so on.

PubSub will enable that distributed dynamic content applications on top of IPFS to have submilisecond updates accross the network, enabling them to have a realtime like UX.

# Roadmap
- [Main issue about pubsub roadmap and TODOs](https://github.com/libp2p/pubsub/issues/9)
- [ ] [Literature review](https://github.com/libp2p/pubsub/issues/4)
- [ ] [PubSub use cases study](https://github.com/libp2p/pubsub/issues/6)
- [ ] Prototype 1 - Fullfill the interface expectations, propagation of messages through the network
- [ ] Tree Forming

# Discussions

- [Previous discussions on ipfs/notes](https://github.com/ipfs/notes/issues?q=is%3Aissue+is%3Aopen+label%3Apubsub)
- [IPFS Workshop Notes](https://github.com/ipfs/2016-Q3-Workshop/issues/17#issuecomment-235006729)

# PubSub Research Review (papers, books, talks, lectures, etc)

### Papers

- Compreensive PubSub Reading list - https://ipfs.io/ipfs/QmNinWNHd287finciBwbgovkAqEBQKvnys1W26sY8uupc5
- [Epidemic Broadcast Trees](http://www.gsd.inesc-id.pt/~ler/docencia/rcs1617/papers/srds07.pdf)
- [HyParView: a membership protocol for reliable gossip-based broadcast](http://asc.di.fct.unl.pt/~jleitao/pdf/dsn07-leitao.pdf)
- [GoCast: Gossip-enhanced Overlay Multicast for Fast and Dependable Group Communication](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.75.4811)

### Books

### Lectures

### Talks

### Slides

- [XL Publish Subscribe Systems](http://gossple2.irisa.fr/~akermarr/LSDS-EPFL-5-new.pdf)

### Terms

There is an [IPFS Glossary](https://github.com/ipfs/glossary), a work in progress, which should have definitions for terms used in pubsub. If you are consistently running into terms that you do not know the meaning of, please open an issue on that repository and we can work on a definition that will help you (and others!) going forward.
