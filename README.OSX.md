# README (for OSX)

```shell
brew install cdrtools
wget -O cloud-localds https://github.com/canonical/cloud-utils/raw/main/bin/cloud-localds
sed -i 's/genisoimage/mkisofs/g' cloud-localds
chmod +x cloud-localds
```
