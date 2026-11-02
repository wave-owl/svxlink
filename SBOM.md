# Source SBOM

**Initial source snapshot, not a release report.** Source commit `cba03b33a0b1e83c124da3ab30cff39c7d430ffa` predates the tooling commit. Future release reports use exact published tags.

Source repository inventory only; completeness is UNKNOWN. Syft inventories tracked source/package manifests. Gitlinks and declared vendored/model evidence are inspected at immutable pins. CMake declarations are conditional requirements, not resolved installations. This is NOT proof of operating-system packages, static-link closure, build-time resolution, or the contents of release binaries.

Generation: **success**

## Source identity

wave-owl/svxlink `cba03b33a0b1e83c124da3ab30cff39c7d430ffa`

- sbom:role: source-root
- sbom:git-commit: cba03b33a0b1e83c124da3ab30cff39c7d430ffa
- sbom:git-tree: dd8ecd16e28cdba220b7c2f961cb6ef6052755ef
- sbom:source-repository: https://github.com/wave-owl/svxlink
- sbom:release-tags: []

## Generation errors

None.

## Components and unresolved licenses

| Component | Version | Role | License |
| --- | --- | --- | --- |
| wave-owl/svxlink | cba03b33a0b1e83c124da3ab30cff39c7d430ffa | source-root | unresolved |
| SIGC | unresolved | conditional-build-requirement | unresolved |
| LADSPA | unresolved | conditional-build-requirement | unresolved |
| Speex | unresolved | conditional-build-requirement | unresolved |
| Opus | unresolved | conditional-build-requirement | unresolved |
| OGG | unresolved | conditional-build-requirement | unresolved |
| GSM | unresolved | conditional-build-requirement | unresolved |
| ALSA | unresolved | conditional-build-requirement | unresolved |
| OpenSSL | unresolved | conditional-build-requirement | unresolved |
| Threads | unresolved | conditional-build-requirement | unresolved |
| DL | unresolved | conditional-build-requirement | unresolved |
| Threads | unresolved | conditional-build-requirement | unresolved |
| RT | unresolved | conditional-build-requirement | unresolved |
| Qt6Core | unresolved | conditional-build-requirement | unresolved |
| Qt6Gui | unresolved | conditional-build-requirement | unresolved |
| Qt6Widgets | unresolved | conditional-build-requirement | unresolved |
| Qt6Network | unresolved | conditional-build-requirement | unresolved |
| Qt5Core | unresolved | conditional-build-requirement | unresolved |
| Qt5Gui | unresolved | conditional-build-requirement | unresolved |
| Qt5Widgets | unresolved | conditional-build-requirement | unresolved |
| Qt5Network | unresolved | conditional-build-requirement | unresolved |
| Qt4 | unresolved | conditional-build-requirement | unresolved |
| Qt6Core | unresolved | conditional-build-requirement | unresolved |
| Qt6Gui | unresolved | conditional-build-requirement | unresolved |
| Qt6Widgets | unresolved | conditional-build-requirement | unresolved |
| Qt6Network | unresolved | conditional-build-requirement | unresolved |
| Qt5Core | unresolved | conditional-build-requirement | unresolved |
| Qt5Gui | unresolved | conditional-build-requirement | unresolved |
| Qt5Widgets | unresolved | conditional-build-requirement | unresolved |
| Qt5Network | unresolved | conditional-build-requirement | unresolved |
| Qt4 | unresolved | conditional-build-requirement | unresolved |
| PkgConfig | unresolved | conditional-build-requirement | unresolved |
| PkgConfig | unresolved | conditional-build-requirement | unresolved |
| PkgConfig | unresolved | conditional-build-requirement | unresolved |
| PkgConfig | unresolved | conditional-build-requirement | unresolved |
| PkgConfig | unresolved | conditional-build-requirement | unresolved |
| PkgConfig | unresolved | conditional-build-requirement | unresolved |
| PkgConfig | unresolved | conditional-build-requirement | unresolved |
| PkgConfig | unresolved | conditional-build-requirement | unresolved |
| ${LIBFIND_PACKAGE_ARGS} | unresolved | conditional-build-requirement | unresolved |
| PkgConfig | unresolved | conditional-build-requirement | unresolved |
| Doxygen | unresolved | conditional-build-requirement | unresolved |
| GSM | unresolved | conditional-build-requirement | unresolved |
| Speex | unresolved | conditional-build-requirement | unresolved |
| Popt | unresolved | conditional-build-requirement | unresolved |
| GSM | unresolved | conditional-build-requirement | unresolved |
| Qt6Core | unresolved | conditional-build-requirement | unresolved |
| Qt6Gui | unresolved | conditional-build-requirement | unresolved |
| Qt6Widgets | unresolved | conditional-build-requirement | unresolved |
| Qt6Network | unresolved | conditional-build-requirement | unresolved |
| Qt6Core5Compat | unresolved | conditional-build-requirement | unresolved |
| Qt5Core | unresolved | conditional-build-requirement | unresolved |
| Qt5Gui | unresolved | conditional-build-requirement | unresolved |
| Qt5Widgets | unresolved | conditional-build-requirement | unresolved |
| Qt5Network | unresolved | conditional-build-requirement | unresolved |
| Qt4 | unresolved | conditional-build-requirement | unresolved |
| Qt6LinguistTools | unresolved | conditional-build-requirement | unresolved |
| Qt5LinguistTools | unresolved | conditional-build-requirement | unresolved |
| Popt | unresolved | conditional-build-requirement | unresolved |
| GCrypt | unresolved | conditional-build-requirement | unresolved |
| Popt | unresolved | conditional-build-requirement | unresolved |
| TCL | unresolved | conditional-build-requirement | unresolved |
| GSM | unresolved | conditional-build-requirement | unresolved |
| GSM | unresolved | conditional-build-requirement | unresolved |
| Popt | unresolved | conditional-build-requirement | unresolved |
| Popt | unresolved | conditional-build-requirement | unresolved |
| GCrypt | unresolved | conditional-build-requirement | unresolved |
| GCrypt | unresolved | conditional-build-requirement | unresolved |
| Popt | unresolved | conditional-build-requirement | unresolved |
| GSM | unresolved | conditional-build-requirement | unresolved |
| TCL | unresolved | conditional-build-requirement | unresolved |
| DL | unresolved | conditional-build-requirement | unresolved |
| CURL | unresolved | conditional-build-requirement | unresolved |
| GCrypt | unresolved | conditional-build-requirement | unresolved |
| RtlSdr | unresolved | conditional-build-requirement | unresolved |
| Threads | unresolved | conditional-build-requirement | unresolved |
| GPIOD | unresolved | conditional-build-requirement | unresolved |
| Conditional source requirements declared by src/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/async/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/async/audio/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/async/core/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/async/cpp/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/async/demo/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/async/qt/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/avr/siglev/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/doc/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/doc/man/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/doc/qteluserdocs/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/echolib/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/include/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/locationinfo/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/misc/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/pyproject.toml | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/qtel/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/qtel/qtel.pro | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/qtel/translations/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/contrib/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/contrib/module_remote_relay/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/contrib/module_site_status/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/contrib/module_tclsstv/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/contrib/module_txfan/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/contrib/svxserver/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/contrib/svxserver/systemd/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/devcal/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/digital/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/modules/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/modules/dtmf_repeater/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/modules/echolink/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/modules/frn/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/modules/help/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/modules/metarinfo/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/modules/parrot/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/modules/propagation_monitor/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/modules/selcallenc/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/modules/tcl/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/modules/tcl_voice_mail/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/modules/template/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/modules/trx/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/reflector/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/remotetrx/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/scripts/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/siglevdetcal/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/svxlink/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/svxlink/contrib/AnnounceLogic/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/svxlink/contrib/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/svxlink/contrib/SipLogic/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/systemd/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/svxlink/trx/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| sigc++ | unresolved | conditional-build-runtime-requirement | unresolved |
| GSM | unresolved | conditional-build-runtime-requirement | unresolved |
| ALSA | unresolved | conditional-build-runtime-requirement | unresolved |
| OpenSSL | unresolved | conditional-build-runtime-requirement | unresolved |
| Threads | unresolved | conditional-build-runtime-requirement | unresolved |
| Speex/Opus/OGG/LADSPA optional; further CMake feature dependencies | unresolved | conditional-build-runtime-requirement | unresolved |
| actions/checkout | v4 | Syft source/package discovery | unresolved |
| github/codeql-action/analyze | v3 | Syft source/package discovery | unresolved |
| github/codeql-action/init | v3 | Syft source/package discovery | unresolved |
| tracked-source/.github/workflows/codeql-analysis.yml | unresolved | Syft source/package discovery | unresolved |

License evidence paths/hashes, source manifests, model hashes and conditional
CMake declarations are recorded in SBOM.cdx.json. Declared upstream pins do not
prove vendored equivalence. No dependency installation or build was performed.
