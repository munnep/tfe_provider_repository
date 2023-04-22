# tfe_provider_repository

This repositories holds a custom terraform provider to be used by TFE/TFC. 

In this repository we have a provider called `myprovider`

The provider will have the following details which explains the folder structure

```
provider "myprovider" {
}

terraform {
  required_providers {
    myprovider = {
      source = "registry.munnep.com/patrick/myprovider"
      version = "0.1.0"
    }
  }
}
```

Folder structure

```
registry.munnep.com
└── patrick
    └── myprovider
        └── 0.1.0
            └── linux_amd64
                └── terraform-provider-myprovider_v0.1.0_x5

4 directories, 1 file
```

# How to

Please follow the instructions on the following repository [here](https://github.com/munnep/tfe_use_provider_repository) to make use of this central repository


