![gogs-brand](https://user-images.githubusercontent.com/2946214/146899259-6a8b58ad-8d6e-40d2-ab02-79dc6aadabbf.png)

[![GitHub Workflow Status](https://img.shields.io/github/checks-status/gogs/gogs/main?logo=github&style=for-the-badge)](https://github.com/gogs/gogs/actions?query=branch%3Amain) [![Discord](https://img.shields.io/discord/382595433060499458.svg?style=for-the-badge&logo=discord)](https://discord.gg/9aqdHU7) [![Sourcegraph](https://img.shields.io/badge/view%20on-Sourcegraph-brightgreen.svg?style=for-the-badge&logo=sourcegraph)](https://sourcegraph.com/github.com/gogs/gogs) ![Builder](https://img.shields.io/badge/Builder-supported-orange?style=for-the-badge&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAAIGNIUk0AAHomAACAhAAA%2BgAAAIDoAAB1MAAA6mAAADqYAAAXcJy6UTwAAAClUExURfFlIgAAAPFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIvFlIv%2F%2F%2F6tHwToAAAA2dFJOUwAAE1UmNGp5KF18JxsaW3t4NjxiYD8NU3R3dWtpdmUwA1JhVxxack4VXDElSkhHAgQvaAxDQn3%2Fja4AAAABYktHRDZHv4jRAAAAB3RJTUUH6AITDys2vDm3kwAAAKZJREFUGNNdz40OgiAQAOCrKE0LKK2AIu1PJS016%2F1fLX50a93G3e7bOA4AgPEEwWgI3U9nng8mBpgHXgiLZU86Y0JX6yjebC3ps2NciP1BHpPU3oQTE0KeY8nl5WrhRniWF0We8UBZ0DPupiaU4B7cs6H3B%2F4PIFPRAIpwXKZpiTlxQytJOXs8GaeyslAjZRYTQqHabQZNG81eUdv0XzS5e386130BpAcM0x6aUgoAAAAldEVYdGRhdGU6Y3JlYXRlADIwMjQtMDItMTlUMTU6NDM6NTMrMDA6MDDckriDAAAAJXRFWHRkYXRlOm1vZGlmeQAyMDI0LTAyLTE5VDE1OjQzOjUzKzAwOjAwrc8APwAAACh0RVh0ZGF0ZTp0aW1lc3RhbXAAMjAyNC0wMi0xOVQxNTo0Mzo1MyswMDowMPraIeAAAAAASUVORK5CYII%3D&color=%23F16522)

[简体中文](README_ZH.md)

## 🔮 Vision

The Gogs (`/gɑgz/`) project aims to build a simple, stable and extensible self-hosted Git service that can be set up in the most painless way. With Go, this can be done with an independent binary distribution across all platforms that Go supports, including Linux, macOS, Windows and ARM-based systems.

## 📡 Overview

- Please visit [our home page](https://gogs.io) for user documentation.
- Please refer to [CHANGELOG.md](CHANGELOG.md) for list of changes in each releases.
- Want to try it before doing anything else? Do it [online](https://try.gogs.io/gogs/gogs)!
- Having trouble? Help yourself with [troubleshooting](https://gogs.io/docs/intro/troubleshooting.html) or ask questions in [Discussions](https://github.com/gogs/gogs/discussions).
- Want to help with localization? Check out the [localization documentation](https://gogs.io/docs/features/i18n.html).
- Ready to get hands dirty? Read our [contributing guide](.github/CONTRIBUTING.md).
- Hmm... What about APIs? We have experimental support with [documentation](https://github.com/gogs/docs-api).

## 💌 Features

- User dashboard, user profile and activity timeline.
- Access repositories via SSH, HTTP and HTTPS protocols.
- User, organization and repository management.
- Repository and organization webhooks, including Slack, Discord and Dingtalk.
- Repository Git hooks, deploy keys and Git LFS.
- Repository issues, pull requests, wiki, protected branches and collaboration.
- Migrate and mirror repositories with wiki from other code hosts.
- Web editor for quick editing repository files and wiki.
- Jupyter Notebook and PDF rendering.
- Authentication via SMTP, LDAP, reverse proxy, GitHub.com and GitHub Enterprise with 2FA.
- Customize HTML templates, static files and many others.
- Rich database backend, including PostgreSQL, MySQL, SQLite3 and [TiDB](https://github.com/pingcap/tidb).
- Have localization over [31 languages](https://crowdin.com/project/gogs).

## 💾 Hardware requirements

- A Raspberry Pi or $5 Digital Ocean Droplet is more than enough to get you started. Some even use 64MB RAM Docker [CaaS](https://www.docker.com/blog/containers-as-a-service-caas/).
- 2 CPU cores and 512MB RAM would be the baseline for teamwork.
- Increase CPU cores when your team size gets significantly larger, memory footprint remains low.

## 💻 Browser support

- Please see [Semantic UI](https://github.com/Semantic-Org/Semantic-UI#browser-support) for specific versions of supported browsers.
- The smallest resolution officially supported is **1024*768**, however the UI may still look right in smaller resolutions, but no promises or fixes.

## 📜 Installation

Make sure you install the [prerequisites](https://gogs.io/docs/installation) first.

There are 6 ways to install Gogs:

- [Install from binary](https://gogs.io/docs/installation/install_from_binary.html)
- [Install from source](https://gogs.io/docs/installation/install_from_source.html)
- [Install from packages](https://gogs.io/docs/installation/install_from_packages.html)
- [Ship with Docker](https://github.com/gogs/gogs/tree/main/docker)
- [Try with Vagrant](https://github.com/geerlingguy/ansible-vagrant-examples/tree/master/gogs)

### Deploy to cloud

- [Cloudron](https://www.cloudron.io/store/io.gogs.cloudronapp.html)
- [Sandstorm](https://github.com/cem/gogs-sandstorm)
- [sloppy.io](https://github.com/sloppyio/quickstarters/tree/master/gogs)
- [YunoHost](https://github.com/YunoHost-Apps/gogs_ynh)
- [DPlatform](https://github.com/DFabric/DPlatform-Shell)
- [LunaNode](https://github.com/LunaNode/launchgogs)
- [alwaysdata](https://www.alwaysdata.com/en/marketplace/gogs/)

### Tutorials

- [Private Git Web Portal in Raspberry PI With Gogs](https://peppe8o.com/private-git-web-portal-in-raspberry-pi-with-gogs/)
- [How To Set Up Gogs on Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-gogs-on-ubuntu-14-04)
- [Run your own GitHub-like service with the help of Docker](https://blog.hypriot.com/post/run-your-own-github-like-service-with-docker/)
- [Dockerized Gogs git server and alpine postgres in 20 minutes or less](https://garthwaite.org/docker-gogs.html)
- [Host Your Own Private GitHub with Gogs](https://eladnava.com/host-your-own-private-github-with-gogs-io/)
- [使用 Gogs 搭建自己的 Git 服务器](https://blog.mynook.info/post/host-your-own-git-server-using-gogs/) (Chinese)
- [阿里云上 Ubuntu 14.04 64 位安装 Gogs](https://my.oschina.net/luyao/blog/375654) (Chinese)
- [Installing Gogs on FreeBSD](https://www.codejam.info/2015/03/installing-gogs-on-freebsd.html)
- [How to install Gogs on a Linux Server (DigitalOcean)](https://www.youtube.com/watch?v=deSfX0gqefE)

## 📦 Software, service and product support

- [Fabric8](http://fabric8.io/) (DevOps)
- [Jenkins](https://plugins.jenkins.io/gogs-webhook/) (CI)
- [Puppet](https://forge.puppet.com/modules/Siteminds/gogs) (IT)
- [Synology](https://www.synology.com) (Docker)
- [Syncloud](https://syncloud.org/) (App Store)

## 🙇‍♂️ Acknowledgments

<p>This project is proundly supported by:</p>
<p>
  <a href="https://www.digitalocean.com/">
    <img src="https://opensource.nyc3.cdn.digitaloceanspaces.com/attribution/assets/SVG/DO_Logo_horizontal_blue.svg" width="201px">
  </a>
</p>

Other acknowledgments:

- Thanks [Egon Elbre](https://twitter.com/egonelbre) for designing the original version of the logo.
- Thanks [Crowdin](https://crowdin.com/project/gogs) for sponsoring open source translation plan.
- Thanks [MonoVM](https://monovm.com/linux-vps/) for sponsoring VPS services.
- Thanks [Buildkite](https://buildkite.com) for sponsoring open source CI/CD plan.

## 👋 Contributors

- See [contributors page](https://github.com/gogs/gogs/graphs/contributors) for top 100 contributors.
- See [TRANSLATORS](conf/locale/TRANSLATORS) for public list of translators.

## ⚖️ License

This project is under the MIT License. See the [LICENSE](https://github.com/gogs/gogs/blob/main/LICENSE) file for the full license text.
