# jvrc_mj_description

JVRC1 model files for MuJoCo

The package will install the files in this directory so that [mc_mujoco](https://github.com/rohanpsingh/mc_mujoco) can pick them up automatically.

Install
-------

```bash
mkdir build
cd build
cmake ../
make && sudo make install
```

CMake options
-------------

- `SRC_MODE` if `ON` the files loaded by mujoco will point to the source rather than the installed files (default `OFF`)
