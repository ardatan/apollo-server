# Change Log

### Upcoming

- Deprecate schemaTag option, add preferred graphVariant option [PR #295](https://github.com/apollographql/apollo-platform-commercial/pull/295)

### vNEXT (Currently `alpha` tag)

- Add lifecycle hooks: `onUnregisteredOperation`, and `onForbiddenOperation`. [PR #158](https://github.com/apollographql/apollo-platform-commercial/pull/158) [PR #251](https://github.com/apollographql/apollo-platform-commercial/pull/251) [PR #TODO](https://github.com/apollographql/apollo-platform-commercial/pull/TODO)
- Prevent the polling timer from keeping the event loop active [PR #223](https://github.com/apollographql/apollo-platform-commercial/pull/223)
- Update error message for operations that are not in the operation registry. [PR #170](https://github.com/apollographql/apollo-platform-commercial/pull/170)

### 0.2.2

- Update `README` image.

### 0.2.1

- Don't enable logging if `debug` was explicitly set to `false` even if `dryRun` is set to `true`. [PR #159](https://github.com/apollographql/apollo-platform-commercial/pull/159)

### 0.2.0

- Per-tag operation manifests can now be fetched for each tag that has a schema and registered operations. [PR #135](https://github.com/apollographql/apollo-platform-commercial/pull/135)
- Manifest storage path structure updated to `/${graphId}/${storageSecret}/${schemaTag}/manifest.v2.json`. The storage secret is fetched automatically using your API key. No longer uses schema hash. [PR #116](https://github.com/apollographql/apollo-platform-commercial/pull/116)
- Metrics on forbidden and registered operations are now reported to Engine [PR #132](https://github.com/apollographql/apollo-platform-commercial/pull/132)

### 0.1.0

- `apollo-server-plugin-operation-registry`
- Update operation registry plugin to use manifest v2 [#32](https://github.com/apollographql/apollo-platform-commercial/pull/32)
