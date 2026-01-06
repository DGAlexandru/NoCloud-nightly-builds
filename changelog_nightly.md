## NoCloud nightly (2026-01-06T12:03:03.543Z)
### Breaking Changes

- **Vendor.NoCloud**: Renaming MockRobot to MockNoCloudRobot [`46ebee0`](https://github.com/DGAlexandru/NoCloud/commit/46ebee005f7721491f687b3a763b84c64786b03a)
- Merge AutoEmptyDockAutoEmptyControlCapability into AutoEmptyDockAutoEmptyIntervalControlCapability [`74b0b3b`](https://github.com/DGAlexandru/NoCloud/commit/74b0b3b267c3f798b01a588a83aa8f00cfb384e1)

### Features

- **Vendor.Dreame**: Migrating from Quirks to Capability: MopGapControl (LacuneMopScalable) and MopTwistFrequency (MeticulousTwist) [`7141fc1`](https://github.com/DGAlexandru/NoCloud/commit/7141fc1022145a5145892d02658c51cad7d3e9c0)
- **Core**: Migrating "Twist Robot for better Mopping" from Quirks to Capability [`9317b37`](https://github.com/DGAlexandru/NoCloud/commit/9317b377af1a49a5ef5eadeefc5e1dc8406ab60c)
- **Core**: Adding the option to just cross the Carpet (besides not tacking any action or avoiding it / lifting or detaching the mop pads) [`7b0c48f`](https://github.com/DGAlexandru/NoCloud/commit/7b0c48f687d8ad3ec5813b3933d437315dd13a9d)
- **Vendor.Dreame**: MopDockMopWashTemperatureControlCapability [`1d1dbf9`](https://github.com/DGAlexandru/NoCloud/commit/1d1dbf9161f7c35b540ec0053778c2a3383239c5)
- **Core**: MopDockMopWashTemperatureControlCapability [`085e694`](https://github.com/DGAlexandru/NoCloud/commit/085e6947930a2c4d7f2067ab5993762b25867688)
- **UI**: Adding some custom obstacle icons [`848f0f9`](https://github.com/DGAlexandru/NoCloud/commit/848f0f927b544749838d3446e544861f5c7b08cf)
- **NTPClient**: Use busybox2 when available [`20f317f`](https://github.com/DGAlexandru/NoCloud/commit/20f317f28d8940148fa0a6b77766ef98a3ac9502)
- **Core**: Create a dedicated CameraLightControlCapability [`b4d921f`](https://github.com/DGAlexandru/NoCloud/commit/b4d921fdc6575dfe4453b7b58febdd3494338f2b)
- **Vendor.Dreame**: Migrate code to use the dedicated CameraLightControlCapability [`ae1034e`](https://github.com/DGAlexandru/NoCloud/commit/ae1034e661bd5c710f84c231e344f174c62f8ed0)
- **Vendor.Dreame**: Migrate code to use the dedicated MopExtensionControlCapability [`17f56df`](https://github.com/DGAlexandru/NoCloud/commit/17f56df2393cb2f50b4dd3e5de8b6736f87f7b6e)
- **Core**: Create a dedicated MopExtensionControlCapability [`6d18b20`](https://github.com/DGAlexandru/NoCloud/commit/6d18b209ec4dcd554c1cd7353653e16dbd11a1a0)

### Fixes

- **Vendor.RoboRock**: Code migration incomplete from the forked repository [`1e1bab4`](https://github.com/DGAlexandru/NoCloud/commit/1e1bab4323b12057a643c3a8f6c298088587921e)
- **UI**: Migration of MopDockMopWashTemperatureControl to dockListItems [`1547a58`](https://github.com/DGAlexandru/NoCloud/commit/1547a58efe5ccebaa0ba5ed61c27ba1b0f16f061)
- **Miio**: Fix a rare BUG that was crashing the miio process [`c77dc43`](https://github.com/DGAlexandru/NoCloud/commit/c77dc43a97e81607fc4321cf28060f4377c5bd21)
- **Vendor.Dreame**: Minor change for newer firmwares [`0e2dbbb`](https://github.com/DGAlexandru/NoCloud/commit/0e2dbbbafcbfa3c6d3518eb92ada48d274e8a1f5)
- **Vendor.Dreame**: Add another new model ID for L10SProUltraHeat [`563f969`](https://github.com/DGAlexandru/NoCloud/commit/563f9699fdee575ff93dd1cb147e13dd2ff55fc7)
- **Vendor.RoboRock**: No-Op - handle two more events [`0e898a9`](https://github.com/DGAlexandru/NoCloud/commit/0e898a985307e7b8e90dedcfb0a139b4079e93d9)
- **Vendor.Dreame**: Track emptying state of auto empty dock [`bd103b3`](https://github.com/DGAlexandru/NoCloud/commit/bd103b3774707b78619347ccaa85fce4c00c1582)
- **UI**: Fix NoCloudSplash showing scrollbars with some specific browser window dimensions [`214d17e`](https://github.com/DGAlexandru/NoCloud/commit/214d17eaa5a0d5b2d8e0935c7cd9511a112ea4ed)
- **UI**: Show AppBar SubHeaders only when there are items for it [`48476ec`](https://github.com/DGAlexandru/NoCloud/commit/48476ecc53a00b827511f49a3c25c8cc5c2b77e4)
- **Core**: Remove localhost IP from default config [`8e67dc9`](https://github.com/DGAlexandru/NoCloud/commit/8e67dc9cca1d0d9c3739b6a0b02d4b93b9cd1f6c)
- **Vendor.Viomi**: Remove redundant emitMapUpdated on map reset [`5c035e4`](https://github.com/DGAlexandru/NoCloud/commit/5c035e48d0cc2a30648cbc58b59ac7429579a2b9)
- **WebServer**: We should not poll the state while fetching the map [`60ff4cc`](https://github.com/DGAlexandru/NoCloud/commit/60ff4ccb910c6349cabafdb33084496850eb3175)
- **UI**: Adding some feedback when saving Virtual Restrictions (on map) [`894387b`](https://github.com/DGAlexandru/NoCloud/commit/894387bd17e34cced53f21e6f2005f0a4fd0b72a)
- **Code**: Use the same naming for customOrderSupported (rename from customOrderSupport) [`57ccae5`](https://github.com/DGAlexandru/NoCloud/commit/57ccae5f3cfc591a7dde99aa6a192459146d095d)
- **Code**: Process timestamp of CurrentStatisticsCapability in a compatible type for OpenAPI validation [`54c3cbc`](https://github.com/DGAlexandru/NoCloud/commit/54c3cbc00521c957bb5589b9bf1d2614cc7ffdec)
- **Code**: Use the same naming for customOrderSupported (rename from customOrderSupport) [`2749474`](https://github.com/DGAlexandru/NoCloud/commit/27494748854712a9358e1c2f0cb39a1783e26600)

### Refactoring

- **Vendor.Dreame**: Optimize "VacuumThenMop" option [`6f195b4`](https://github.com/DGAlexandru/NoCloud/commit/6f195b4c3d81c92811800065820ecf48f18f46a4)
- **MQTT**: Simplify segment ID validation [`7b8a1bc`](https://github.com/DGAlexandru/NoCloud/commit/7b8a1bc99bb85940370d67cb4f9b4f699db8fe74)
- **Core**: Optimization: move map polling logic into NoCloudRobot base class [`72fd097`](https://github.com/DGAlexandru/NoCloud/commit/72fd09785fcc8dbc51332504d4e1dbcee781f285)
- **Core**: Use native crypto: randomUUID instead of uuid external module [`7be3843`](https://github.com/DGAlexandru/NoCloud/commit/7be384306bbc2585f9f856a91271c44270d6a005)
- **BuildTools**: Use current latest AJV NodeJs module for FrontEnd in DevDependency [`16f1316`](https://github.com/DGAlexandru/NoCloud/commit/16f131649dd66073e5d9bbd34e7da2cce050d93e)
- **BuildTools**: Optimize UPX compression async function; adding some file error handling. [`4a49052`](https://github.com/DGAlexandru/NoCloud/commit/4a490529b62bfe2b99a0580447cab12cdc1c3ddd)
- **BuildCode**: Use current latest @yao-pkg/pkg  & @DGAlexandru/UPX versions [`f008a20`](https://github.com/DGAlexandru/NoCloud/commit/f008a2002cf11827c3515db37c903058ae970663)

### Chores

- **BuildTools**: Fixing ESLint warnings - groups not sorted, mainly [`063f9e1`](https://github.com/DGAlexandru/NoCloud/commit/063f9e18c6eedc1edaafd97b7f8734e186884cc4)
- **BuildTools**: Migrating NightlyBuilds from "master" branch to "main" branch, to be in sync with GitHub recommendations [`4d334a3`](https://github.com/DGAlexandru/NoCloud/commit/4d334a3da0230c8146b7d1ffaa5ce405d681d40e)
- **BuildTools**: False positive indentation problem - commented code [`ae86a13`](https://github.com/DGAlexandru/NoCloud/commit/ae86a136712acd5f5d58012fce881f91971d2f7b)
- **BuildTools**: False positive indentation problem - commented code [`b9948fe`](https://github.com/DGAlexandru/NoCloud/commit/b9948fe8b5da8d80ca4642a745926acfb3a6bf47)
- **BuildTools**: GitHub fix - Code Lint - indentations [`1dbc48d`](https://github.com/DGAlexandru/NoCloud/commit/1dbc48d215815bee7a511f4145ee1df4743c0ff6)
- **Assets**: Improved icon for "Robot with extensions" [`a62adf6`](https://github.com/DGAlexandru/NoCloud/commit/a62adf68686030bddcd9d0da3d6843b720757360)
- Some cleaning: "return await" [`0f281c8`](https://github.com/DGAlexandru/NoCloud/commit/0f281c823a1fdfb3503afa67225c2e3d0033af9d)
- Rename variable in Dreame files to match the name used in other vendors [`df3b5db`](https://github.com/DGAlexandru/NoCloud/commit/df3b5dbb755a23d25e22bdecc352ecd20a9fd064)
- **Build**: Cleanup of NodeJS v20 [`732b743`](https://github.com/DGAlexandru/NoCloud/commit/732b7430bf8d86c79d7e3d56090788d318868264)
- **Build**: Upgrade (officially) to NodeJS v22 [`175b311`](https://github.com/DGAlexandru/NoCloud/commit/175b311b4bc20ca2dec4a7fea6cdaf65cca64503)
- New GitHub Workflow to "manually" allow package JSON files to be updated for new NodeJs packages. [`0c9262c`](https://github.com/DGAlexandru/NoCloud/commit/0c9262ce77ff33ca73563bc82ee4828b732407d8)
