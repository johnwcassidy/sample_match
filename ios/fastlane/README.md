fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios certs_dev_setup

```sh
[bundle exec] fastlane ios certs_dev_setup
```

Generate and store development provisioning profiles and certs in keychain

### ios certs_dev

```sh
[bundle exec] fastlane ios certs_dev
```

Read and store development provisioning profiles and certs in keychain

### ios certs_appstore_setup

```sh
[bundle exec] fastlane ios certs_appstore_setup
```

Generate and store appstore provisioning profiles and certs in keychain

### ios certs_appstore

```sh
[bundle exec] fastlane ios certs_appstore
```

Read and store appstore provisioning profiles and certs in keychain

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
