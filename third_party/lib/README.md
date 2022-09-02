# Static libraries for Google RTC Audio Processing

Note: the following 5 libraries should be contained in this directory.

## Main libraries

- libgoogle_rtc_audio_processing.a
- libgoogle_rtc_audio_processing_tuning.a

Built by RI-2019.2 Xtensa toolchain provided by Intel.
Binaries are shared among chrome-internal repositories.

## SDK libraries for linkage

- libc++.a
- libc++abi.a
- libc++experimental.a

Provided in RI-2019.2 toolchain.
Please copy them to this diretory if you have RI-2019.2 toolchain.
