# cssn
The cloud storage network supported by 5G based-in block chain

CSSN Technical Characteristics
===
1.1 Super Nodes
---
* In order to ensure the stable and efficient operation of the blockchain storage network, CSSN adopts a node layering mechanism. As a regional autonomous node, a super node is responsible for the management of edge nodes in the network. In order for the super node to better manage the core network and system function tasks, `the CSSN optimizes the super node to better support the 5G module extension.`

1.2 Edge node
---
* `The CSSN edge node distributes the intensive tasks of the super node`, reduces the corresponding time and bandwidth cost of the super node, and satisfies the high concurrent service of the user for massive data storage under the decentralized architecture model. As a source of massive storage data of the CSSN network, the CSSN edge node can be any terminal device with network and computing capabilities. The super node guarantees the edge node to ensure that the edge node provides efficient, reliable and trustworthy CSSN mass storage service processing. Blockchain network storage service.

1.3 Storage Node
---
* The storage node uses EC erasure code block storage, and the user data is hashed on the storage node, and `the K+2 redundancy strategy is adopted to ensure that the user data node is damaged in less than 3 data blocks`. It can be read normally, ensuring high availability of user data.

1.4 Erasure Code data protection algorithm
---
 * `CSSN storage node uses Cauchy matrix to implement redundant encryption of storage nodes`.


