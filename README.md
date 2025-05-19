# FreeCAD-thumbnailer
Files and instructions to configure the thumbnail view of FreeCAD files in GNU/Linux Operating Systems (Free Desktop Environments), for those users who run the portable version (AppImage)

### Building the deb file (optional there is a pre-made one)

```bash
git clone https://github.com/alfrix/FreeCAD-thumbnailer.git freecad-thumbnailer
dpkg-deb --build --root-owner-group freecad-thumbnailer
```
   
### Installation on Debian-based distributions

```
sudo dpkg -i freecad-thumbnailer.deb
```
