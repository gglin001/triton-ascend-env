# triton-ascend-env

env for building `triton-ascend` and `AscendNPU-IR`

## get cann toolkit

- https://www.hiascend.com/developer/download/community/result?module=cann
  `Ascend-cann-toolkit_8.5.0.alpha002_linux-x86_64.run`
  `Ascend-cann-toolkit_8.5.0.alpha002_linux-aarch64.run`

```bash
chmod +x Ascend-cann-toolkit_8.5.0.alpha002_linux-aarch64.run
./Ascend-cann-toolkit_8.5.0.alpha002_linux-aarch64.run --extract=Ascend-cann-toolkit_8.5.0.alpha002_linux-aarch64
pushd ~/Downloads/Ascend-cann-toolkit_8.5.0.alpha002_linux-aarch64/run_package
./Ascend-BiSheng-toolkit_aarch64.run --extract=Ascend-BiSheng-toolkit_aarch64
./CANN-compiler-8.5.t8.0.b060-linux.aarch64.run --extract=CANN-compiler-8.5.t8.0.b060-linux.aarch64
popd
popd
```
