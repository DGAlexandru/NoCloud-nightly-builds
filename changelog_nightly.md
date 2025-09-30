## NoCloud nightly (2025-09-30T07:59:54.099Z)

### Features

- **Core**: Create a dedicated CameraLightControlCapability [`b4d921f`](https://github.com/DGAlexandru/NoCloud/commit/b4d921fdc6575dfe4453b7b58febdd3494338f2b)
- **Vendor.Dreame**: Migrate code to use the dedicated CameraLightControlCapability [`ae1034e`](https://github.com/DGAlexandru/NoCloud/commit/ae1034e661bd5c710f84c231e344f174c62f8ed0)
- **Vendor.Dreame**: Migrate code to use the dedicated MopExtensionControlCapability [`17f56df`](https://github.com/DGAlexandru/NoCloud/commit/17f56df2393cb2f50b4dd3e5de8b6736f87f7b6e)
- **Core**: Create a dedicated MopExtensionControlCapability [`6d18b20`](https://github.com/DGAlexandru/NoCloud/commit/6d18b209ec4dcd554c1cd7353653e16dbd11a1a0)

### Fixes

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

- **BuildTools**: False positive indentation problem - commented code [`b9948fe`](https://github.com/DGAlexandru/NoCloud/commit/b9948fe8b5da8d80ca4642a745926acfb3a6bf47)
- **BuildTools**: GitHub fix - Code Lint - indentations [`1dbc48d`](https://github.com/DGAlexandru/NoCloud/commit/1dbc48d215815bee7a511f4145ee1df4743c0ff6)
- **Assets**: Improved icon for "Robot with extensions" [`a62adf6`](https://github.com/DGAlexandru/NoCloud/commit/a62adf68686030bddcd9d0da3d6843b720757360)
- Some cleaning: "return await" [`0f281c8`](https://github.com/DGAlexandru/NoCloud/commit/0f281c823a1fdfb3503afa67225c2e3d0033af9d)
- Rename variable in Dreame files to match the name used in other vendors [`df3b5db`](https://github.com/DGAlexandru/NoCloud/commit/df3b5dbb755a23d25e22bdecc352ecd20a9fd064)
- **Build**: Cleanup of NodeJS v20 [`732b743`](https://github.com/DGAlexandru/NoCloud/commit/732b7430bf8d86c79d7e3d56090788d318868264)
- **Build**: Upgrade (officially) to NodeJS v22 [`175b311`](https://github.com/DGAlexandru/NoCloud/commit/175b311b4bc20ca2dec4a7fea6cdaf65cca64503)
- New GitHub Workflow to "manually" allow package JSON files to be updated for new NodeJs packages. [`0c9262c`](https://github.com/DGAlexandru/NoCloud/commit/0c9262ce77ff33ca73563bc82ee4828b732407d8)
