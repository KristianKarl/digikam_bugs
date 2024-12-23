SUMMARY

When a MP4 video file has a GPS position and it's sidecar file has a different position digikam displays the position of the MP4 file, not it's sidecar file.

STEPS TO REPRODUCE

1.  Metadata settings are: 
   1.1 Behavior tab: Geolocation information = true/enabled
   1.2 Behavior tab: Use ExifTool as backend to read metadata from files = true/enabled
   1.3 Behavior tab: Delegate to ExifTool backend all operations to write metadata to files = true/enabled
   1.4 Sidecars tab: Read and write to sidecar files: true/enabled
       1.4.1 Sidecars tab: Write to XMP sidecar only

2. Add attached location_test.mp4 to an album

3. Change the GPS position using the Geolocation Editor


OBSERVED RESULT

The position of the video file is still displayed as the original. 

EXPECTED RESULT

The displayed position given in 3.

SOFTWARE/OS VERSIONS
Operating System: NixOS 25.05
KDE Plasma Version: 6.2.4
KDE Frameworks Version: 6.8.0
Qt Version: 6.8.0
Kernel Version: 6.6.66 (64-bit)
Graphics Platform: Wayland
Processors: 32 × 13th Gen Intel® Core™ i9-13900KF
Memory: 94.1 GiB of RAM
Graphics Processor: NVIDIA GeForce RTX 3050/PCIe/SSE2

ADDITIONAL INFORMATION

Digikam version: digiKam-8.6.0-20241219T190219-Qt6-x86-64.appimage
Version of exiftool is 13.00
