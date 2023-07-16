# @toinane/electron-forge-maker-nsis

## How to use

In your forge.config.ts file:

```typescript
import { MakerNSIS } from '@toinane/electron-forge-maker-nsis';

// This is the options you can set from app-builder-lib
// import { PackagerOptions } from 'app-builder-lib';

const config: ForgeConfig = {
  makers: [new MakerNSIS({ options: PackagerOptions })]
};

export default config;
```

### Options

You can set all options avalaible from `PackagerOptions` from `app-builder-lib`. See [Github documentation](https://github.com/electron-userland/electron-builder/blob/master/packages/app-builder-lib/src/packagerApi.ts#L9).

See also [Electron-builder documentation](https://www.electron.build/configuration/configuration#configuration).
