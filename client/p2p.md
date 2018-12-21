# P2P Architecture
- The p2p Architcture of p2p-social will require 2 componants : 
  - **Post Delivery** : Post delivery should use ipfs, with actual files (images, videos) as seperate ipfs hashes. This way repeat posts of the same content will not be duplicated, and more peers will be availiable for the posts.
  - **Post Discovery** : A system will be required to request new posts of a certain user on the network. The system to be used here remains to be chosen.
- Posts are stored on user devices, in addition to this storage, a database exists on the users device indicating: 
  - the public key of the author
  - the posts ipfs hash
  - the date of publication


é