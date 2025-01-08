## NoCloud nightly (2025-01-08T11:38:17.627Z)
### Breaking Changes

- **vendor.Dreame**: The mop consumable has been removed from Dreame X/L40 (and equivalent) firmware (master branch) [`4d70c71`](https://github.com/DGAlexandru/NoCloud/commit/4d70c71e4a86e51067f2b05e82efdc48acf7f53c)
- Move the sensor consumable type as a subtype of the new type cleaning (master branch) [`0a9e144`](https://github.com/DGAlexandru/NoCloud/commit/0a9e144d81f6cce3c5f4fdc80ae883bfaa199794)

### Features

- **vendor.Dreame**: Adding a new Quirk: Side Brush on Carpet (master branch) [`5f8fe48`](https://github.com/DGAlexandru/NoCloud/commit/5f8fe482ee9308d5e28e91a5200fab374bc346a3)
- **vendor.Dreame**: Adding wheel consumable monitoring (master branch) [`50a2554`](https://github.com/DGAlexandru/NoCloud/commit/50a25545a639699a50b90fafa3cb7c54de2dc9a3)
- **Core**: Adding wheel consumable subtype (master branch) [`0790d4c`](https://github.com/DGAlexandru/NoCloud/commit/0790d4c183d57846487e6e5f3ec65a983d253858)
- **Updater**: Add NullUpdateProvider for good measure (master branch) [`392ffc3`](https://github.com/DGAlexandru/NoCloud/commit/392ffc366487196d08baa303ceac728d0cfa329b)
- **Updater**: Introduce a working version comparison to the nightly update channel (master branch) [`8a33562`](https://github.com/DGAlexandru/NoCloud/commit/8a3356215a4a9289f0dc08c9c133eb18f39ac9ff)
- **UI**: Shuffle the MQTT settings around (master branch) [`0014a4b`](https://github.com/DGAlexandru/NoCloud/commit/0014a4b233ae63755b8438f3740d051b9fe4fcce)
- **MQTT**: Remove obsolete addICBINVMapProperty setting (master branch) [`e91c18a`](https://github.com/DGAlexandru/NoCloud/commit/e91c18abce0fc69434e4bf52b96b1e279d042f1b)
- **MQTT**: Remove obsolete addICBINVMapProperty setting (master branch) [`76dc997`](https://github.com/DGAlexandru/NoCloud/commit/76dc997ea1e23261e57533e2506dce20f6428dfb)
- **vendor.Dreame**: MOVA P10 Pro Ultra (master branch) [`1ba5334`](https://github.com/DGAlexandru/NoCloud/commit/1ba533467a6f39b5337536cffb655af2640cfad7)

### Fixes

- Missing newline at the end of file - Update MqttController.js [`c669daf`](https://github.com/DGAlexandru/NoCloud/commit/c669daf8320b63fcf431ebacfea01d3a68837e31)
- **Code**: Bad indentation / alignment in "Add NullUpdateProvider for good measure" commit [`7daeb9e`](https://github.com/DGAlexandru/NoCloud/commit/7daeb9ebd73b0f7c679e5b29fd95e98b1ce17e8f)
- Typo in "Move the sensor consumable type as a subtype of the new type cleaning" commit [`28f1bbb`](https://github.com/DGAlexandru/NoCloud/commit/28f1bbb941fa1fe094c947dde1f0395a29888f7f)
- Typo in "Move the sensor consumable type as a subtype of the new type cleaning" commit [`847ddb4`](https://github.com/DGAlexandru/NoCloud/commit/847ddb42aa0fd227622f3ba2cdcf7d6af4a7efa8)
- **vendor.Dreame**: Newer Dreame Robots may store obstacle images elsewhere (master branch) [`0fc8ad9`](https://github.com/DGAlexandru/NoCloud/commit/0fc8ad96d6a76f2802de3b8094b660969c15d780)
- **MQTT**: Attempt to fix the reconfigure mutex never being left (main branch) [`74007f1`](https://github.com/DGAlexandru/NoCloud/commit/74007f13bec338c09e782f62de8762ec98fbb482)
