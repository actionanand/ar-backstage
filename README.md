# [Backstage](https://backstage.io)

This is your newly scaffolded Backstage App, Good Luck!

To start the app, run:

```sh
yarn install
yarn dev
```

********************************
# My Practical overview

## What is Backstage?

> Backstage is an open platform for building **Developer Portals** that create, manage, and explore software from a single UX layer. **Backstage** was **developed** initially **at Spotify** as an internal tool and then open-sourced in 2020. [more...](https://www.getport.io/blog/backstage-all-you-need-to-know-about-this-developer-portal#:~:text=Read%20more-,What%20is%20Backstage?,then%20open%2Dsourced%20in%202020.)

* [Internal Developer Platform](https://internaldeveloperplatform.org/developer-portals/backstage/#:~:text=What%20is%20backstage.io?,use%20in%20the%20Kubernetes%20universe.)
* [dily.dev AI](https://app.daily.dev/search?id=b385ac08-a99b-11ee-a1cb-42010a007e0c)
* [What the Heck is Backstage Anyway?](https://engineering.atspotify.com/2020/03/what-the-heck-is-backstage-anyway/)

## How to create backstage app?

```bash
npx @backstage/create-app
```

### Versions I used

* Version of `@backstage/create-app` available at this time is `0.5.8`
* My linux distro - `Ubuntu 20.04 LTS`.
* `Node` version - `20.10.0` (Used `nvm` to manage multiple node versions)
* `Yarn` version - `1.22.21`
* `Python` version - `3.11.5` (used `conda`). [More...](https://www.rosehosting.com/blog/how-to-install-miniconda-on-ubuntu-22-04/)
* `gcc` version - `12.1.0`

I installed `gcc` through `conda` to avoid compatibility issue (between other packages). [More...](https://github.com/rstudio/reticulate/issues/1282)

```bash
conda install -c conda-forge gcc=12.1.0
```

PS: `backstage.io` to work as we expected, `python` and `gcc` are very much necessary. And using `kali linux` is not recommended as we're unable to run `sudo apt install build-essential` or `sudo apt-get -y install gcc`. These commands will help us install `gcc` in our linux debian distro. But thanks to `conda`, we're still able to install it. So it's up to you 😊

