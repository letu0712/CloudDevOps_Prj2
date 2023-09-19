# CD12352 - Infrastructure as Code Project Solution
# [TuLX]

## Spin up instructions
./create.sh myudagram udagram.yml udagram-parameters.json 
./create.sh mynetwork network.yml network-parameters.json

## Tear down instructions
./update.sh myudagram udagram.yml udagram-parameters.json 
./update.sh mynetwork network.yml network-parameters.json

## Other considerations
./delete.sh myudargam
./delete.sh mynetwork

## Endpoint URL website
http://udacity-s3-tulx-bucket.s3-website-us-east-1.amazonaws.com
