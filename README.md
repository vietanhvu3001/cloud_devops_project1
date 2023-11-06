# Project URL
http://server-webap-qj3ujsoigdyx-165128071.us-east-1.elb.amazonaws.com/
# Create
./create.sh network network.yaml network-params.json
./create.sh server udagram.yml udagram-parameters.json
# Update
./update.sh network network.yaml network-params.json
./update.sh server udagram.yml udagram-parameters.json
# Delete
./delete.sh network
./delete.sh server
