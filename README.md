# High Risk System Module

## Description

Kill players in the wild by picking up equipment dropped by each other, and the killed players will randomly drop the equipped items on their bodies



## Requirements

High Risk module requires:

- AzerothCore v4.0.0+


## Installation

```
1) Simply `git clone` the module under the `modules` directory of your AzerothCore source or copy paste it manually.
2) Import the SQL manually to the right Database (auth, world or characters) or with the `db_assembler.sh` (if `include.sh` provided).
3) Re-run cmake and launch a clean build of AzerothCore.
```

## Edit the module's configuration (optional)

If you need to change the module configuration, go to your server configuration directory (where your `worldserver` or `worldserver.exe` is), copy `my_module.conf.dist` to `my_module.conf` and edit that new file.


## Credits

* [Lushen](https://github.com/RealLushen) : He put together this script
* [acidmanifesto](https://github.com/acidmanifesto) : Removed unused variables
* [Bench](https://github.com/heyitsbench) : Thanks bro for patching the module
* AzerothCore: [repository](https://github.com/azerothcore) - [website](http://azerothcore.org/) - [discord chat community](https://discord.gg/PaqQRkd)