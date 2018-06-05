# Centos 7 kickstart image generator
This script download latest CentOS minimal iso image and generate automate installation image
* config - folder contains configs
* images - folder contain generated images

You need to run this as root

Password for `root` is `root`

```
yum install -y git wget && \
rm -rf centos-kickstart-image-generator && \
git clone https://github.com/diego-vieira/centos-kickstart-image-generator.git && \
cd centos-kickstart-image-generator && \
./generator.sh
```
