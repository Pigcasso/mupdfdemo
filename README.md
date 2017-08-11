# mupdfdemo
这个旧版的 MuPDF Android 预览库。
MuPDF项目组： http://mupdf.com/
这个项目不包含 jni 源码，我把项目克隆到本地后，重新build，生成了 *.so 文件。
```
.
├── AndroidManifest.xml
└── jniLibs
    ├── armeabi-v7a
    │   └── libmupdf_java32.so
    └── x86
        └── libmupdf_java32.so
```
你也可以自行克隆到本地`git clone --recursive git://git.ghostscript.com/mupdf-android-viewer-old.git`自行完成上面的操作。
