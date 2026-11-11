# LabiCast third-party source distributions

This public repository provides complete corresponding third-party source code, free of charge and without registration. It contains no LabiCast SDK or application source code, credentials, or private build inputs.

## FDK AAC

- Upstream: https://android.googlesource.com/platform/external/aac/
- Exact revision: `52095a61ef8bda4beb5eb1861ff81c117681c9c9`
- [Complete original source archive](fdk-aac/52095a61ef8bda4beb5eb1861ff81c117681c9c9/aosp-aac-52095a6.tar.gz)
- [Complete license](fdk-aac/52095a61ef8bda4beb5eb1861ff81c117681c9c9/NOTICE.txt)
- [Source metadata and SHA-256](fdk-aac/52095a61ef8bda4beb5eb1861ff81c117681c9c9/SOURCE.json)
- Archive SHA-256: `cfa55827c05bc0d2ec17cf4f61383849c137f6a52c05b2e36f58c5b258bf6dc5`

The source archive is unmodified and includes the full upstream source, not only decoder files. Our receiver links only the decoder-related modules: libAACdec, libPCMutils, libFDK, libSYS, libMpegTPDec, libSBRdec, libArithCoding, libDRCdec and libSACdec. This repository does not grant AAC patent rights; the full upstream license remains controlling.

Published revision directories are retained and are not replaced when a newer dependency revision is introduced. Applications additionally pin downloads to the exact Git commit and archive SHA-256.

## 中文说明

本仓库免费提供蜡笔投屏所使用的第三方组件对应源码，无需登录或注册。FDK 源码归档保持上游完整原件，附完整许可、来源版本和 SHA-256。接收端仅集成解码模块；源码归档不参与运行时播放。旧版源码目录持续保留。许可条件以原文为准，本仓库不授予 AAC 专利许可。

## Reproducible archive

The reproducible subdirectory normalizes only tar/gzip container metadata; it preserves every source byte and file mode. The complete original archive above remains available unchanged.

- [Complete normalized source](fdk-aac/52095a61ef8bda4beb5eb1861ff81c117681c9c9/reproducible/aosp-aac-52095a6.tar.gz)
- Normalized archive SHA-256: `9ffb501131744143e1e937ff37514a3233c151f1daf480a1cbf9ca44352c6d11`
- Source-file manifest SHA-256: `2f7d1d1d00844b81ad92f657e58e70b4aa203b6f78076d9e9739b302a24b9267`
