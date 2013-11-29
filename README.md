Description
===========

baseboxes build with packer for use with vagrant.
This repository includes the packer templates to build the basebox.
The build boxes are available through Amazon S3 (see links below).

Requirements
============

* [vagrant](http://vagrantup.com)
* [packer](http://packer.io)
* [virtualbox](https://www.virtualbox.org/)

Boxes
=====

### Ubuntu
#### Ubuntu Saucy Salamander 13.10
##### Ubuntu Saucy Salamander 13.10 Server x86_64 ([ubuntu-13.10-server-amd64.box](https://s3-eu-west-1.amazonaws.com/srt-vagrant-boxes/ubuntu-13.10-server-amd64.box))
* VirtualBox Guest Additions 4.3.2

---

### Debian
#### Debian Wheezy 7.x
##### Debian Wheezy 7.2.0 x86_64 ([debian-7.2.0-amd64.box](https://s3-eu-west-1.amazonaws.com/srt-vagrant-boxes/debian-7.2.0-amd64.box))
* VirtualBox Guest Additions 4.3.2
* Puppet 3.3.2

---

#### Debian Squeeze 6.x
##### Debian Squeeze 6.0.8 x86_64 ([debian-6.0.8-amd64.box](https://s3-eu-west-1.amazonaws.com/srt-vagrant-boxes/debian-6.0.8-amd64.box))
* VirtualBox Guest Additions 4.3.2
* Puppet 3.3.2

---

License and Author
==================

- Author:: Achim Rosenhagen (<a.rosenhagen@ffuenf.de>)

- Copyright:: 2013, ffuenf

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
