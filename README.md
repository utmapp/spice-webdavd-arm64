# SPICE webdavd for ARM64

The source is taken from phodav-2.5 and converted into a Visual Studio 2019 project to support building for ARM64.

# Usage

1. Install [vspkg][1] with VS integrations
2. `.\vcpkg\vcpkg install glib:arm64-windows`
3. Install [WiX v3.14.0.4118][2] or higher and [WiX Extension][3]
4. Open `spice-webdavd.sln` and build

[1]: https://github.com/microsoft/vcpkg
[2]: https://wixtoolset.org/releases/v3-14-0-4118/
[3]: https://marketplace.visualstudio.com/items?itemName=WixToolset.WixToolsetVisualStudio2019Extension
