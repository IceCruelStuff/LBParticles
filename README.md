LBParticles
===========

A simple plugin for adding particles to your PocketMine-MP server.

## Installation
Download the latest build from **[Poggit CI](https://poggit.pmmp.io/ci/IceCruelStuff/LBParticles)**.

## Commands:

| Command | Sub Command | User | Params | Description |
|:-------:|:-----------:|:----:|:------:|:-----------:|
|`lbparticles`|`give`|`<name>`|`LavaParticleEffect, PortalParticleEffect, RainbowParticleEffect, RedstoneParticleEffect`| Spawns a player's particle |
|`lbparticles`|`remove`|`<name>`|    | Removes a player's particles |

## API

This plugin can be also accessed by its API.

```php
$LBParticles = Server::getInstance()->getPluginManager()->getPlugin('LBParticles');

// Give a particle
$LBParticles->giveParticle($user, $particle);

// Remove a particle
$LBParticles->removeParticle($user);
```
