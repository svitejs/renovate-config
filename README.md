# renovate config

## usage

Add this to `.github/renovate.json`
```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>svitejs/renovate-config"]
}
```

## settings

see [config file](./default.json) and [renovate docs](https://docs.renovatebot.com)

Summary:
- runs on every 4th of the month
- batches minor+patch updates
- includes lockfile maintenance
- ignores engines and peerDependencies
