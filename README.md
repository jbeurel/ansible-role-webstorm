## webstorm


Set up [WebStorm](https://www.jetbrains.com/webstorm/).

#### Requirements

None

#### Variables

* `webstorm_version` [default: `2016.3.3`]: [Version](https://confluence.jetbrains.com/display/WI/Previous+WebStorm+Releases) to install
* `webstorm_install_prefix` [default: `/opt`]: Install prefix

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - webstorm
```
