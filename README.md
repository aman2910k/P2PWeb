# P2PWeb
To execute p2pwb
1.	Make (do make from inside src folder)
2.	./p2psh 
3.	Commands for p2psh
PEER <peer-hostname> <peer-port>: Peers to another p2pweb node whose hostname
and port is given. After peering process, they exchange previously known metadatas
with each other. They exchange new learned announcements as they learn them.
PUBLISH <filename>: Publishes a file into p2pweb. Filename doesn’t include spaces
for the sake of simplicity.
UNPUBLISH <hash>: Unpublish a file with given hash published previously by this
node.
SHOW_PEERS: Print a table of peer endpoints.
SHOW_METADATA: Print a table of metadata and endpoint information stored by this
node.
SHOW_PUBLISHED: Print a table of metadata information currently being published
by this node.
