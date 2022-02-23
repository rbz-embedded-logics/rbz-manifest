## rbz-manifest

# Download Software 🚀
For download software sources:

```
repo init -u https://github.com/rbz-embedded-logics/rbz-manifest.git -b main
repo sync
```
# Configure machine ⚙️
For configure distro and machine:
```
DISTRO=mod-rbz-xwayland MACHINE=machine source rbz-setup-release.sh -b xbuild_mod_imx8m
```
Wher "machine" can be:
  - mod_imx8m_plus
  - mod_imx8m_mini
  - mod_imx8m_nano

# Build full image 🛠️
```
bitbake imx-image-multimedia
```
