# ruby
- Installs dependencies
- Installs rvm config file
- Installs rvm
- Installs ruby
- Installs bundler


## Role Variables

### Required Variables
| Variable | Description |
|----------|-------------|
|`ruby_user`| The user in whose home dir we install rvm |
|`ruby_version`| The version of ruby to install |

### Optional Variables
| Variable | Description |
|----------|-------------|
|`ruby_bin_path`| The path to the ruby binaries |
|`ruby_bundle_exec`| The full command used to run gems of the project |
|`ruby_env_PATH`| The PATH env var modified to contain the rvm bin dir |
|`ruby_install_path`| The path where we install ruby |
|`ruby_rvm_path`| The path where we install rvm |

See `defaults/main.yml` for default values for these variables.


## License
BSD
