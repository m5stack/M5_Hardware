# M5Stack KiCad Library

**The libraries in this repository are intended to be used with KiCad version 7.**

Each footprint library is stored as a directory with the .pretty suffix. The footprint files are .kicad_mod files within. And 3D model files are stored in the ``3D/M5Stack.3dshapes/`` folder.

### Contributing

If you want to contribute, please consider sending us a Pull Request (PR).

### 3D Models

We provide some 3D models to help you with your project inside the ``3D/M5Stack.3dshapes/`` folder.

To use the files, you need to create an environment variable pointing to this ``KiCad`` folder path.

* Open ``Preferences`` -> ``Configure Paths...``
* Create the new variable:
    * Name: ``KICAD_M5STACK``
    * Path: ``/path/to/this/KiCad``
* Then 3D models can be referenced as: ``${KICAD_M5STACK}/3D/M5Stack.3dshapes/model_name.step``

### About KiCad

KiCad is a Cross-Platform and Open Source Electronics Design Automation Suite. See [KiCad EDA](https://kicad.org/) for more information.
