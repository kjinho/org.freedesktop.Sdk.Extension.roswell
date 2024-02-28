# org.freedesktop.Sdk.Extension.roswell

This is an extension to the Freedesktop SDK that provides access
to [roswell](https://github.com/roswell/roswell) for Common Lisp
development.

## Installation

```sh
git clone https://github.com/kjinho/org.freedesktop.Sdk.Extension.roswell.git
cd org.freedesktop.Sdk.Extension.roswell
flatpak run org.flatpak.Builder --user --install --force-clean build-dir org.freedesktop.Sdk.Extension.roswell.yaml
```

Remember to add ```roswell``` to the environment variable ```FLATPAK_ENABLE_SDK_EXT```:

```sh
export FLATPAK_ENABLE_SDK_EXT=roswell
```

## Removal
```sh
flatpak remove org.freedesktop.Sdk.Extension.roswell
```