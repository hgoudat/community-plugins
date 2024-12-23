## API Report File for "@backstage-community/plugin-lighthouse-backend"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { AuthService } from '@backstage/backend-plugin-api';
import { BackendFeature } from '@backstage/backend-plugin-api';
import { CatalogApi } from '@backstage/catalog-client';
import { Config } from '@backstage/config';
import { DiscoveryService } from '@backstage/backend-plugin-api';
import { LoggerService } from '@backstage/backend-plugin-api';
import { PluginTaskScheduler } from '@backstage/backend-tasks';
import { TokenManager } from '@backstage/backend-common';

// @public @deprecated (undocumented)
export interface CreateLighthouseSchedulerOptions {
  // (undocumented)
  auth?: AuthService;
  // (undocumented)
  catalogClient: CatalogApi;
  // (undocumented)
  config: Config;
  // (undocumented)
  discovery: DiscoveryService;
  // (undocumented)
  logger: LoggerService;
  // (undocumented)
  scheduler?: PluginTaskScheduler;
  // (undocumented)
  tokenManager?: TokenManager;
}

// @public @deprecated (undocumented)
export function createScheduler(
  options: CreateLighthouseSchedulerOptions,
): Promise<void>;

// @public
const lighthousePlugin: BackendFeature;
export default lighthousePlugin;

// (No @packageDocumentation comment for this package)
```
