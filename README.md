# AUR

AUR packages I maintain except https://aur.archlinux.org/packages/?K=r6eve&SeB=m

These packages have some problems. The solution is out there.

## Usage

```bash
cd ${pkgname}
makepkg -s
pacman -U ${pkgname}-${pkgver}-${arch}.pkg.tar.zst
```
