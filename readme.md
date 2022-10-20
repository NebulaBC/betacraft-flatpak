# Betacraft Launcher for flatpak

to build this and install it on your machine run `flatpak-builder --user --install --force-clean build co.betacraft.Betacraft.yml`  

or alternatively to package this in a .flatpak format for distribution run:  
```
flatpak-builder --repo=repo --force-clean build co.betacraft.Betacraft.yml
flatpak build-bundle ./repo betacraft.flatpak co.betacraft.Betacraft
```
and then to install the bundle as an end user, just run:
```
flatpak install betacraft.flatpak
```
