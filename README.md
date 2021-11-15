# dmk_high_speed_cam_ros

## Documentation

You can find an online version of the included user documentation here:

https://www.theimagingsource.com/documentation/tiscamera/
## Building tiscamera

The following commands will build and install our software with default settings.

```
git clone https://github.com/TheImagingSource/tiscamera.git
cd tiscamera
# only works on Debian based systems like Ubuntu
sudo ./scripts/install-dependencies.sh --compilation --runtime
mkdir build
cd build

# With ARAVIS:
cmake -DBUILD_ARAVIS=ON ..
# Without ARAVIS
cmake -DBUILD_ARAVIS=OFF ..

make
sudo make install
```
