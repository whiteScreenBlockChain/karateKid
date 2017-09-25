material got from https://hyperledger.github.io/composer/installing/development-tools.html

Script details

https://hyperledger.github.io/composer/assets/img/developer-tools-commands.png

This diagram explains the order in which the scripts can be run.

Downloading Fabric

Issue from the fabric-tools directory ./downloadFabric.sh

Starting Fabric

Issue from the fabric-tools directory ./startFabric.sh

Stop Fabric

Issue from the fabric-tools directory ./stopFabric.sh

Create Hyperledger Composer Profile

Issue from the fabric-tools directory ./createComposerProfile.sh

Note: this creates a Hyperledger Composer profile specifically to connect to the development fabric you've already started.

Teardown Fabric

Issue from the fabric-tools directory ./teardownFabric.sh

sample manipulation : https://hyperledger.github.io/composer/tutorials/developer-guide.html
git clone https://github.com/hyperledger/composer-sample-networks.git
cp -r ./composer-sample-networks/packages/basic-sample-network/  ./my-network