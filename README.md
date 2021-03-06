# esx_waterlost

<p align="center">
  <a href="https://github.com/brouznouf/fivem-mysql-async/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License">
  </a>
</p>

> You can also read this in [Portuguese](https://github.com/vWernay/esx_perderitens/blob/master/README.ptbr.md).

`esx_waterlost` is a resource for [FiveM](https://fivem.net) which detects if the player is in the water and remove the items you want.

[![Showcase](https://yt-embed.herokuapp.com/embed?v=vCr-2LJdliA)](https://youtu.be/vCr-2LJdliA)

## Installation

1. Make sure your server artifacts ([windows](https://runtime.fivem.net/artifacts/fivem/build_server_windows/master)
   or [linux](https://runtime.fivem.net/artifacts/fivem/build_proot_linux/master)) are up to date.
2. Extract the latest zip file at [releases](https://github.com/vWernay/esx_waterlost/releases) in your resources
   folder.
3. Add `ensure esx_waterlost` in your `server.cfg`.
4. Adjust the [configuration](#configuration) of the resource in the `config.lua`.

## Configuration

* **locale** - The language desired.
* **Money** - Set `true` if you want the player to lose all money when they into the water or `false` if you don't want.
* **BlackMoney** - Set `true` if you want the player to lose all Black Money/Dirty Money when they into the water or `false` if you don't want.
* **Items** - The items you want the player to lose when they into the water.
    * **give_burn** - Give item after falling into the water? If yes, put the `item` to be given, if not, put` false`.

## Dependencies

* [es_extended-v1.1/v1.2-final](https://github.com/esx-framework/es_extended/tree/v1-final)
