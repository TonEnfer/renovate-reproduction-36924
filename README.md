# 36924

Reproduction for https://github.com/renovatebot/renovate/discussions/36924

## Current behavior

Renovate only updates the SDK version specified in global.json, but does not update the workload version.
See https://github.com/TonEnfer/renovate-reproduction-36924/pull/3/files - the value in the `version` field has been increased, but the value in the `workloadVersion` field has remained the same

## Expected behavior

The value in the `workloadVersion` field has been increased