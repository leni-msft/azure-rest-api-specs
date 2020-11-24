## Ruby

These settings apply only when `--ruby` is specified on the command line.

```yaml
package-name: azure_mgmt_testrp
package-version: 2020-11-01-privatepreview
azure-arm: true
```

### Tag: package-2020-11-01-privatepreview and ruby

These settings apply only when `--tag=package-2020-11-01-privatepreview --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

```yaml $(tag) == 'package-2020-11-01-privatepreview' && $(ruby)
namespace: Microsoft.TestRp
output-folder: $(ruby-sdks-folder)/testrp
```
