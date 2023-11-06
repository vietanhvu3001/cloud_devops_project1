./create.sh network network.yaml network-params.json
./create.sh server server.yaml server-params.json

./update.sh network network.yaml network-params.json
./update.sh server server.yaml server-params.json

./delete.sh network
./delete.sh server