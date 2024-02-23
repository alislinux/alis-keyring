# About なにこれ
GnuPG Keyrings for Alis.

## How to build a package

#### 1. Import GPG key
```bash
gpg --keyserver keyserver.ubuntu.com --recv-key 36F612F2
```

#### 2. Clone PKGBUILD repository
```bash
git clone https://github.com/alislinux/alis-pkgbuild.git
```

#### 3. Build a package
```bash
cd univalent-pkgbuild/univalent-keyring
makepkg -s
```

#### Option: Install on your pasocom
```bash
sudo pacman -U univalent-keyring-YYYYMMDD-R-any.pkg.tar.zst
```
