## Installation scripts

Utility scripts that install binaries based on the operating system. The script will ask the user for root permission as required by installation.

### Setup

Clone this git repository

```
git clone https://github.com/0xPolygon/install.git
cd install
```

### Bor

#### Install default bor binary

```
./bor.sh
```

#### Install a specific bor version

Simply pass the version tag as the first argument to the installation script. Notice that the script will overwrite existing bor binaries if they exist. Example:

```
./bor.sh 0.2.14-tmp-span-hotfix
```

#### Installing PBSS profiles
```shell
./bor.sh $version $network pbss-$network-$type
```
Where $version is desired version, $network is mainnet or amoy, and $type is defined as sentry or validator as PBSS does not support bootnode or archive.



### Heimdall

#### Install default Heimdall binary

```
./heimdall.sh
```

#### Install a specific Heimdall version

Simply pass the version tag as the first argument to the installation script. Notice that the script will overwrite existing Heimdall binaries if they exist. Example:

```
./heimdall.sh 0.2.19
```
