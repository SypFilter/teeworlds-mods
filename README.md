# Mods Repository

This repository contains scripts to build server binaries and binaries for mods that source were never published for as many known mods of Teeworlds ecosystem. The repository is also responsible for the storage of map files from unmaintained mods.

## Supported Mods

| **Maintained** | List of supported mods in Teeworlds 0.6.x |
| --- | --- |
| **DDNet** | [Source](https://github.com/ddnet/ddnet) \| [Website](https://ddnet.tw/) |
| **InfClass** | [Source](https://github.com/InfectionDust/teeworlds-infclassr) |
| **MMOTee** | [Source](https://github.com/kurosio/Teeworlds-Mmotee-Old) |
| **ZombPanic** | [Source](https://github.com/teeframe/zombpanic) |

***

| **Unmaintained** | List of supported mods in Teeworlds 0.6.x | 
| --- | --- |
| **Bomb Tag** | [Source](https://github.com/unique-clan/bomb) |
| **Flagball** | [Source](https://github.com/teeframe/flagball) |
| **Football** | [Source](https://github.com/unique-clan/football) |
| **HMH-Monster** | [Source](https://github.com/teeframe/hmh-monster) |
| **Hunter** | [Source](https://github.com/yangfl/teeworlds-hunter) |
| **Killing Floor** | [Source](https://github.com/Siile/KillingFloor) |
| **TeeSmash** | [Source](https://github.com/timazuki/TeeSmash) |
| **TeeWare** | [Source](https://github.com/headshot2017/teeware-mod) |
| **zCatch** | [Source](https://github.com/ddnet/zcatch) |

***

| **Maintained** | List of supported mods in Teeworlds 0.7.x | 
| --- | --- |
| **MMOTee** |[Source](https://github.com/MrCosmo666/Teeworlds-MRPG) ***Requires Custom Client** |

***

| **Unmaintained** | List of supported mods in Teeworlds 0.7.x | 
| --- | --- |
| **Nodes** | [Source](https://github.com/teeworldsnetwork/nodes) \| [Website](https://nodes.teeworlds.dev/)  ***Requires Custom Client** |

## Binary Mods

For these mods, there are binaries that were published by their creators without the source. You can download them directly from this repository.

| **Binary Mods** | List of binary mods in Teeworlds 0.6.x | 
| --- | --- |
| **Battlefield** | (https://www.teeworlds.com/forum/viewtopic.php?id=9178) |
| **zChaos** | (https://www.teeworlds.com/forum/viewtopic.php?id=9682) |

***

| **Binary Mods** | List of binary mods in Teeworlds 0.7.x | 
| --- | --- |
| **LumLvl** |  (https://www.teeworlds.com/forum/viewtopic.php?id=12849) |

## Installing Dependencies

First you must install the necessary dependencies on your system. You can run this script to install the necessary dependencies for compiling the mods (Scripts are made assuming you are running **Ubuntu 20.04**).

```
wget https://raw.githubusercontent.com/teeframe/mods-repository/main/resources/default-dependencies.sh  -O - | sh
```

## Compiling Mods (Teeworlds 0.6.x)

Now you just need to execute the compile script for your desired mod:

```
wget https://raw.githubusercontent.com/teeframe/mods-repository/main/0.6.x/MOD_FOLDER_NAME/compile.sh  -O - | sh
```

## Compiling Mods (Teeworlds 0.7.x)

Now you just need to execute the compile script for your desired mod:

```
wget https://raw.githubusercontent.com/teeframe/mods-repository/main/0.7.x/MOD_FOLDER_NAME/compile.sh  -O - | sh
```
