Minegasm is a Minecraft (Java Edition) Forge mod that uses connected sex toys to enhance the gameplay experience. This mod is intended to be used only by consenting adults.

## Download

| Minecraft  | Forge                                                                                            | Java | JAR file                                                                                                                                                       |
|------------|--------------------------------------------------------------------------------------------------|------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **1.20**.1 | [47.1.0](http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.20.1.html)       | 17   | [minegasm-0.4.0-1.20.1-Forge-47.1.0.jar](https://github.com/RainbowVille/minegasm/releases/download/v0.4.0/minegasm-0.4.0-1.20.1-Forge-47.1.0.jar)             |
| **1.19**.4 | [45.1.0](http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.19.4.html)       | 17   | [minegasm-0.4.0-1.19.4-Forge-45.1.0.jar](https://github.com/RainbowVille/minegasm/releases/download/v0.4.0/minegasm-0.4.0-1.19.4-Forge-45.1.0.jar)             |
| **1.18**.2 | [40.2.0](http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.18.2.html)       | 17   | [minegasm-0.4.0-1.18.2-Forge-40.2.0.jar](https://github.com/RainbowVille/minegasm/releases/download/v0.4.0/minegasm-0.4.0-1.18.2-Forge-40.2.0.jar)             |
| **1.17**.1 | [37.1.1](http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.17.1.html)       | 16   | [minegasm-0.4.0-1.17.1-Forge-37.1.1.jar](https://github.com/RainbowVille/minegasm/releases/download/v0.4.0/minegasm-0.4.0-1.17.1-Forge-37.1.1.jar)             |
| **1.16**.5 | [36.2.34](http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.16.5.html)      | 11\* | [minegasm-0.4.0-1.16.5-Forge-36.2.34.jar](https://github.com/RainbowVille/minegasm/releases/download/v0.4.0/minegasm-0.4.0-1.16.5-Forge-36.2.34.jar)           |
| **1.15**.2 | [31.2.57](http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.15.2.html)      | 11\* | [minegasm-0.4.0-1.15.2-Forge-31.2.57.jar](https://github.com/RainbowVille/minegasm/releases/download/v0.4.0/minegasm-0.4.0-1.15.2-Forge-31.2.57.jar)           |
| **1.14**.4 | [28.2.26](http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.14.4.html)      | 11\* | [minegasm-0.4.0-1.14.4-Forge-28.2.26.jar](https://github.com/RainbowVille/minegasm/releases/download/v0.4.0/minegasm-0.4.0-1.14.4-Forge-28.2.26.jar)           |
| **1.13**.2 | [25.0.223](http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.13.2.html)     | 11\* | [minegasm-0.4.0-1.13.2-Forge-25.0.223.jar](https://github.com/RainbowVille/minegasm/releases/download/v0.4.0/minegasm-0.4.0-1.13.2-Forge-25.0.223.jar)         |
| **1.12**.2 | [14.23.5.2859](http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.12.2.html) | 11\* | [minegasm-0.4.0-1.12.2-Forge-14.23.5.2859.jar](https://github.com/RainbowVille/minegasm/releases/download/v0.4.0/minegasm-0.4.0-1.12.2-Forge-14.23.5.2859.jar) |

*) For version 1.12&ndash;1.16, you need to set your Minecraft installation to use Java 11 or later instead of the bundled Java 8.

Old releases can be found on the [release page](./releases).

### Dependencies
1. Intiface Central: [https://intiface.com/central/](https://intiface.com/central/)
2. Minecraft Forge: the versions mentioned on the corresponding Forge column above are the tested versions (newer versions are probably okay) 

## How to Use
1. Make sure you have all the dependencies installed.
2. Download the JAR file and put it in your mods directory. If you don't know where your mods directory is, you can simply open your Minecraft, click the 'Mods' button on the main menu, then click 'Open Mods Folder'.
3. Run the Intiface Central and start the server (`ws://localhost:12345`). For advanced users, it is possible to use an Intiface server on a different endpoint by specifying it in the Minegasm config file.
4. Turn on the device.
5. Start Minecraft and connect to a world. If everything works properly, you should see a message stating that Minegasm is connected to your device when you enter the world. If the connection fails, go back to Intiface Central and make sure that the Server Status shows that the server is running. To force Minegasm to retry to connect, leave the world and then re-enter.
6. Have fun!

For more detailed instructions, please see the [setup page](./setup).

## Known Issues
* There is currently a bug in some versions of the Minecraft launcher that prevents the use of newer Java runtimes: [https://bugs.mojang.com/browse/MCL-18306](https://bugs.mojang.com/browse/MCL-18306). This affects the mods for the Minecraft versions before 1.17 as Minegasm requires at least Java 11. If you encounter this issue, a workaround is to delete `JavaCheck.jar` shipped with the launcher.
* In-game config menu is missing for 1.13, 1.17, 1.18, 1.19, and 1.20. The mod can still be configured manually by editing the config file.
* The mod has only undergone limited testing in multiplayer mode and it might not work with some mods.

Make sure to check out our [issue tracker](https://github.com/RainbowVille/minegasm/issues?q=is%3Aissue+is%3Aopen+label%3Abug) for all the known issues and their status. The [troubleshooting page](./troubleshoot) provides suggestions of things to do if you encounter any issues.

## Supported Devices
In theory, this mod should be compatible with any devices on this list: [IoST Index – Vibrators with Buttplug.io Support](https://iostindex.com/?filter0ButtplugSupport=4&filter1Features=OutputsVibrators)

It has been confirmed by the developers to work with:
- [Lovense Edge](https://www.lovense.com/r/qvl9jn) (prostate massager)
- [Lovense Hush](https://www.lovense.com/r/zrzb5e) (butt plug)
- [Lovense Max 2](https://www.lovense.com/r/n4x2bh) (male masturbator)
- [Lovense Domi 2](https://www.lovense.com/r/khhgol?t=m1) (wand)

## Configuration
Minegasm is configurable through the `Mods > Config` screen, as well as by manually editing the `minegasm-client.toml` config file.
The [config page](./config) explains this in further details.

## Gameplay modes

| Mode      | Description                                                                                                                                                  |
|-----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| NORMAL    | The toy will vibrate when you attack other entities, mine, or gain XP.                                                                                       |
| MASOCHIST | The toy will vibrate when you're hurt or dying.                                                                                                              |
| HEDONIST  | The toy will vibrate on all events defined in other modes, except dying (this is replaced, instead, by having the toy vibrate when you're full and healthy). |
| CUSTOM    | The toy will vibrate depending on the intensity levels configured by the user.                                                                               |

## Support
In principle, we do not provide any dedicated (technical) supports. If you need any assistance, you can use the [discussion page](https://github.com/RainbowVille/minegasm/discussions). Alternatively, you can join our [Discord server](https://discord.gg/Kc7ueWC) and ping `@RSwoop` in the `#minegasm` channel, but please be advised that he might not always be able to help you.

If you have any suggestions or found any bugs, please post them to our [issue tracker](https://github.com/RainbowVille/minegasm/issues) on GitHub. Please try to be as descriptive as possible and include your `debug.log` (please remove any references to your username first if that matters). The `debug.log` file is typically under the `logs` directory of your minecraft instance. In the vanilla installation on Windows, it is typically on `<drive>:\Users\<username>\AppData\Roaming\.minecraft`.

The status of confirmed bugs and planned future enhancements are available on our [project board](https://github.com/RainbowVille/minegasm/projects/1).

## Credits
- `Lone_Destroyer` for the logo
- `qdot` and `BlackSphereFollower` for the buttplug library
