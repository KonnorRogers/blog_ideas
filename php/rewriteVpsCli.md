Rewrite vps_cli / vps_setup in php

MAIN REASON:
  Learning php

Secondary reason:
  Currently non extensible and requires a constant update to the repo to install
  additional packages. Allow users to create a .vps-packages.yaml files to store

  IE:

```yaml
# npm packages
npm:
  command: npm install --global
  packages:
    gatsby-cli
    solargraph
    etc...
```

This will then run:

```bash
npm install --global gatsby-cli solargraph etc...
```
