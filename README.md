# releases
<p align="center"><img alt="Axis Linux" src="https://user-images.githubusercontent.com/61242573/118399404-43c30480-b65d-11eb-9c81-82fccb9cf14e.png"/></p>

<h3 align="center">Axis Linux releases</h3>

<h4 align="center">This is where you can find <a href="https://github.com/axislinux/releases/releases">releases</a> of Axis Linux</h4>

<p align="center"><img alt="powered-by-electricity" src="https://forthebadge.com/images/badges/powered-by-electricity.svg"/></p>

<p align="center">
  <img alt="license" src="https://img.shields.io/github/license/axislinux/axis-live?style=for-the-badge"/>
  <img alt="latest-release" src="https://img.shields.io/github/v/release/axislinux/releases?include_prereleases&style=for-the-badge"/>
</p>

---

## About

Creator: [XXCoreRangerX](https://github.com/XXCoreRangerX) (mail@xxcore.pl)

## What does each file do
| File | Meaning |
| ------------- | ------------- |
| axislinux-XXXX.XX.XX-x86_64.iso | The installation file |
| axislinux-XXXX.XX.XX-x86_64.iso.sig | The signature of the `iso` |
| axislinux-XXXX.XX.XX-x86_64.iso.sha512sum | The checksum of the `iso` |

## How to check the ISO integrity
**Make sure to download all the release files (`ISO`, `SIG` and `sha512sum`) and that they are in the same directory.**

1. Add the key to gpg 
```console
gpg --recv-keys A182D760A59FDFDD
```

2. Then, verify gpg key of the file
```console
gpg --verify axislinux-XXXX.XX.XX-x86_64.iso.sig
```
3. Lastly, check sha512 checksum
```console
sha512sum axislinux-XXXX.XX.XX-x86_64.iso
```

## License
This project is licensed under the [MIT license](https://github.com/axislinux/axis-live/blob/master/LICENSE).
