## BeagleV Starlight RISC-V Fedora image
This is a respin of Fedora 33 to support the [StarFive JH7100 SoC](https://github.com/starfive-tech/beaglev_doc/blob/main/JH7100%20Data%20Sheet%20V01.01.04-EN%20(4-21-2021).pdf) (RV64GC) and [BeagleV Starlight board](https://github.com/beagleboard/beaglev-starlight).  Find more details in the [BeagleV Starlight getting started guide](https://wiki.seeedstudio.com/BeagleV-Getting-Started/).  Please open issues regarding the Fedora image in [this repository](https://github.com/starfive-tech/beaglev_fedora/issues).

### Download the latest image: 
* **2021-May-16:** [Fedora-riscv64-vic7100-xfce-dev-Rawhide-20210516233526.n.0-sda.raw.zst](https://files.beagle.cc/file/beagleboard-public-2021/images/Fedora-riscv64-vic7100-xfce-dev-Rawhide-20210516233526.n.0-sda.raw.zst)
  * [sha256sum](https://files.beagle.cc/file/beagleboard-public-2021/images/Fedora-riscv64-vic7100-xfce-dev-Rawhide-20210516233526.n.0-sda.raw.zst.sha256sum): `ab916cf46efc57c034aba8f79018a3af70a67d121126cbec271cdc12cdf64f05`
  * Note: [supports XFCE desktop on HDMI](https://github.com/starfive-tech/Fedora_on_StarFive/issues/22#issuecomment-841719888)


### Past images:
* **2021-April-19:** [Fedora-riscv64-vic7100-dev-raw-image-Rawhide-20210419121453.n.0-sda.raw.zst](https://files.beagle.cc/file/beagleboard-public-2021/images/Fedora-riscv64-vic7100-dev-raw-image-Rawhide-20210419121453.n.0-sda.raw.zst)
  * sha256sum: `e3d0df18d2eeb913aafabbb975c7a8803fdae333643a946b20607060e18df0db`


### Latest Fedora image replaced with @Esmil kernel
## Fedora 2021-May-16 which boots starlight branch which is 5.13-rc2 latest fixes from https://github.com/esmil/linux/tree/starlight
* [Fedora-riscv64-vic7100-xfce-dev-Rawhide-20210516233526.n.0-sda-akira.raw.zst](https://drive.google.com/file/d/1jFDkCheXWvjV7lYbEO4FzGpmfU1SukpO/view?usp=sharing)
* sha256sum: `99b4eff485f2a2d8cb21da7ab2518e5e606850108b06df22a17d942a44ded007`
* ![](./img/fedora-5.13.0-rc2-a22fc1-s.png)
