# Dock [![Build Status](https://api.cirrus-ci.com/github/probonopd/cyber-dock.svg)](https://cirrus-ci.com/github/probonopd/cyber-dock)

![](https://user-images.githubusercontent.com/2480569/95664567-6d590200-0b49-11eb-9e3e-2acf51f66fef.png)

## Dependencies

On Arch Linux:

```shell
sudo pacman -S gcc cmake qt5-base qt5-quickcontrols2 kwindowsystem
```

On FreeBSD:

```
sudo pkg install -y curl zip pkgconf cmake qt5-qmake qt5-buildtools qt5-quickcontrols2 kf5-kwindowsystem
```


## Build and Install

```
mkdir build
cd build
cmake ..
make
sudo make install
```

## License

This project has been licensed by GPLv3.
