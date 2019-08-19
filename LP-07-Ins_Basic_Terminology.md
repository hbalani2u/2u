### 7. Instructor Do: Basic Terminology (10 mins)

Students will learn basic, common terminology that will enable them to navigate the blockchain space.

**Files:**

* [slides x-y]()

Navigate to the slides and define common terms:

#### Hash

* Explain that a "hash" is a unique fingerprint of a piece of data. A hash function is one way, which means that you cannot reverse a hash.
  However, it is easy to check if a hash is valid. If you wanted to send an important piece of data that you wanted to make sure made it
  to the other side without modifications, you could include the hash of the file as well.
  The person on the otherside could run the same hash function, and if they get the same result, they know it is a bit for bit copy.\

* Elaborate that if you were to change a single bit in a hash function's input, you would get a completely different hash.
  This allows for something called "data integrity" which is a very important part of internet and data security as well as blockchain technology.

#### Signature

* Explain that a signature is just that, a digital signature that proves ownership over a piece of data.
  Once a file/message is signed, you can verify its signature later. If the signed message is modified, the signature will be invalidated.

* This means that if you were to sign a document, and the document was modified after, it would be obvious and you would know the data was altered
  since the signature would no longer validate.

#### Wallet

* A digital wallet is simply a set of "keys" to your funds that are on the blockchain. This means that with a wallet, you can create and send
  transactions, as well as view your balance. You can also sign messages with your digital wallet to prove ownership.

* A digital wallet is much like the debit cards in your own wallet, you use them to access funds in your account.
  Only in this case, the card is now a key, and the bank is now the blockchain.

#### Transaction

* Explain that a transaction is simply a signed message that authorized a movement of funds between two parties.

* It is essentially "I sign off on the movement of X amount of value from account A to account B" -- now that it is signed off, nobody can modify it.

#### Node

* A node is a participant in the blockchain network that keeps a copy of the blockchain ledger locally. Nodes go through every transaction and verify the signatures.
  If the signatures are not valid, it considers the block invalid and tosses it out. This way, any invalid transactions are discarded by the whole network.

* If you wanted to send a transaction, you would send it to a node to keep in its "memory pool" to be recorded into the final ledger later. Nodes propagate
  new transactions to other nodes for tracking as well, until a miner or block producer comes along to finalize it.

* Nodes are enforcing all of the rules of the blockchain, thus they are a very important part of the maintainance of the network.

#### Miner/Block producer

* A miner/block producer is a special type of node that is working to solve computations in order to finalize transactions.

* Miners take the pending transactions from the nodes they are connected to and put them into a block. Each miner races against each other to perform
  this process first, and the miner that successfully creates a block first will be rewarded by the network for its work.

Reassure the students that we will dive deeper into the mechanisms in which nodes and miners communicate with each other, as well as the full lifecycle of a transaction, from creation, to finality within the blockchain.
