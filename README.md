# Bevy Retrograde

[![Crates.io](https://img.shields.io/crates/v/bevy_retrograde.svg)](https://crates.io/crates/bevy_retrograde)
[![Docs.rs](https://docs.rs/bevy_retrograde/badge.svg)](https://docs.rs/bevy_retrograde)
[![Build Status](https://github.com/katharostech/bevy_retrograde/actions/workflows/rust.yaml/badge.svg)](https://github.com/katharostech/bevy_retrograde/actions/workflows/rust.yaml)
[![lines of code](https://tokei.rs/b1/github/katharostech/bevy_retrograde?category=code)](https://github.com/katharostech/bevy_retrograde)
[![Katharos License](https://img.shields.io/badge/License-Katharos-blue)](https://github.com/katharostech/katharos-license)

<div align="center">
    <em>( Screenshot of <a href="https://katharostech.com/post/bounty-bros-on-web">Bounty Bros.</a> game made with Bevy Retrograde and <a href="https://github.com/katharostech/skipngo">Skip'n Go</a> )</em>
</div>

![bounty bros game screenshot](./doc/bounty_bros.png)

[skipngo]:  https://github.com/katharostech/skipngo

Bevy Retrograde is an opinionated plugin pack for the [Bevy][__link0] game engine with tools to help you make 2D games!

Bevy Retrograde is not specific to pixel-art games, but it does include some features that would be particularly useful for pixel games. The ultimate goal is to act as an extension to Bevy that gives you common tools necessary to make a 2D game such as map loading, physics, UI, save-data, etc. Not all of the features we want to add are implemented yet, but we will be expanding the feature set as we developer our own game with it.


## License

Bevy Retrograde LDtk is licensed under the [Katharos License][__link1] which places certain restrictions on what you are allowed to use it for. Please read and understand the terms before using Bevy Retrograde for your project.


## Development Status

Bevy Retrograde is in early stages of development. The API is not stable and may change dramatically at any time. We have just made a major update, migrating from Bevy 0.5 and a custom

See also [Supported Bevy Version](#supported-bevy-version) below.


## Features & Examples

Check out our [examples][__link2] list to see how to use each Bevy Retrograde feature:

 - Supports web and desktop out-of-the-box
 - [LDtk][__link3] map loading and rendering using [`bevy_ecs_ldtk`][__link4]
 - An integration with the [RAUI][__link5] UI library for building in-game user interfaces and HUD
 - Physics and collision detection powered by [Rapier][__link6] with automatic generation of convex collision shapes from sprite images
 - Text rendering of bitmap fonts in the BDF format
 - A simple but effective sound playing API


## Supported Bevy Version

| bevy | bevy_retrograde |
| --- | --- |
| 0.7 | 0.3 |
| 0.6 |  |
| 0.5 | 0.1, 0.2 |

**`Cargo.toml`:**


```toml
bevy = { version = "0.7", default-features = false }
bevy_retrograde = "0.3.0"
```



 [__link0]: https://bevyengine.org
 [__link1]: https://github.com/katharostech/katharos-license
 [__link2]: https://github.com/katharostech/bevy_retrograde/tree/master/examples#bevy-retro-examples
 [__link3]: https://ldtk.io
 [__link4]: https://crates.io/crates/bevy_ecs_ldtk/0.3.0
 [__link5]: https://crates.io/crates/RAUI
 [__link6]: https://rapier.rs/

