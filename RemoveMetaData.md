
```
Install exiftool:

sudo apt-get install libimage-exiftool-perl

To read photo metadata:

exiftool /tmp/my_photo.jpg

To erase photo metadata:

exiftool -all= /tmp/my_photo.jpg

Before:

ExifTool Version Number         : 8.60
File Name                       : my_photo.jpg
Directory                       : /tmp
File Size                       : 3.0 MB
File Modification Date/Time     : 2013:02:24 12:08:10-08:00
File Permissions                : rw-rw-r--
File Type                       : JPEG
MIME Type                       : image/jpeg
Exif Byte Order                 : Big-endian (Motorola, MM)
Orientation                     : Unknown (0)
Y Cb Cr Positioning             : Centered
X Resolution                    : 72
Y Resolution                    : 72
Resolution Unit                 : inches
Modify Date                     : 2013:02:24 11:25:27
Make                            : Samsung
Camera Model Name               : Galaxy Nexus
Exif Version                    : 0220
Flashpix Version                : 
Color Space                     : sRGB
Components Configuration        : Y, Cb, Cr, -
Compressed Bits Per Pixel       : 0
Exif Image Width                : 1944
Exif Image Height               : 2592
Date/Time Original              : 2013:02:24 11:25:27
Create Date                     : 2013:02:24 11:25:27
Exposure Time                   : 1/354
F Number                        : 2.8
Exposure Program                : Aperture-priority AE
ISO                             : 50, 0, 0
Shutter Speed Value             : 1/353
Aperture Value                  : 2.6
Brightness Value                : 0
Exposure Compensation           : 0
Max Aperture Value              : 2.6
Subject Distance                : 0 m
Metering Mode                   : Multi-spot
Light Source                    : Daylight
Flash                           : No Flash
Focal Length                    : 3.4 mm
Flash Energy                    : 0
Exposure Index                  : undef
Sensing Method                  : One-chip color area
Scene Type                      : Directly photographed
Custom Rendered                 : Custom
Exposure Mode                   : Auto
White Balance                   : Auto
Digital Zoom Ratio              : 1
Scene Capture Type              : Standard
Contrast                        : Normal
Saturation                      : Normal
Sharpness                       : Normal
Subject Distance Range          : Unknown
Image Unique ID                 : OAEL01
GPS Time Stamp                  : 19:25:27
GPS Date Stamp                  : 2013:02:24
Compression                     : JPEG (old-style)
Thumbnail Offset                : 2143
Thumbnail Length                : 10941
Image Width                     : 1944
Image Height                    : 2592
Encoding Process                : Baseline DCT, Huffman coding
Bits Per Sample                 : 8
Color Components                : 3
Y Cb Cr Sub Sampling            : YCbCr4:2:0 (2 2)
Aperture                        : 2.8
GPS Date/Time                   : 2013:02:24 19:25:27Z
Image Size                      : 1944x2592
Shutter Speed                   : 1/354
Thumbnail Image                 : (Binary data 10941 bytes, use -b option to extract)
Focal Length                    : 3.4 mm
Light Value                     : 12.4

After:

ExifTool Version Number         : 8.60
File Name                       : my_photo.jpg
Directory                       : /tmp
File Size                       : 2.9 MB
File Modification Date/Time     : 2013:02:24 12:21:39-08:00
File Permissions                : rw-rw-r--
File Type                       : JPEG
MIME Type                       : image/jpeg
Image Width                     : 1944
Image Height                    : 2592
Encoding Process                : Baseline DCT, Huffman coding
Bits Per Sample                 : 8
Color Components                : 3
Y Cb Cr Sub Sampling            : YCbCr4:2:0 (2 2)
Image Size                      : 1944x2592

References:
```
