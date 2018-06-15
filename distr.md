 (Byzantine Fault Tolerant) консенсус в распределенной сети. Про это можно почитать, например, статьи про Tendermint (https://tendermint.com/static/docs/tendermint.pdf), HoneyBadgerBFT (https://eprint.iacr.org/2016/199.pdf) и Hyperledger Fabric (https://arxiv.org/pdf/1709.06921.pdf).

– Peer-to-peer роутинг и distributed hash tables. Можно почитать про Kademlia (https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf) и S/Kademlia для недоверенной сети (http://www.spovnet.de/files/publications/SKademlia2007.pdf). Еще есть https://libp2p.io/, которую есть мысли использовать или реализовать с нуля на Scala.

– Web Assembly, GraalVM и прочие виртуальные машины. Их планируется использовать совместно с верификацией вычислений на недоверенных машинах. Про такую верификацию, например, можно почитать в статье от TrueBit (https://people.cs.uchicago.edu/~teutsch/papers/truebit.pdf)

– Verifiable data structures. Такие структуры данных, которые на запрос могут вместе с результатами выдать доказательство, что недоверенная машина не подменила данные. Статьи: https://www.continusec.com/static/VerifiableDataStructures.pdf и Baloon (https://eprint.iacr.org/2015/007.pdf).

– Поиск по зашифрованным данным. Несколько классных статей: https://people.csail.mit.edu/nickolai/papers/popa-mope-eprint.pdf и https://eprint.iacr.org/2016/591.pdf

– Распределенные системы. Можно посмотреть на Designing Data-Intensive Applications от Martin Kleppmann (https://dataintensive.net/) и блог Aphyr’а (https://aphyr.com/tags/jepsen).

– Zero Knowledge Proofs. Как Alice доказать проверяющему, что Alice знает X, без раскрытия этого самого X. Неплохое введение про zkSNARKs – https://blog.ethereum.org/2016/12/05/zksnarks-in-a-nutshell/.
