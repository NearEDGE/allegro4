# Allegro 4.4.4 MSVC Modern Windows Build

This fork of Allegro 4.4.4 includes:

- Fix for shutdown hang/exception in the Windows subsystem (QuickFix)
- Fully functional static and dynamic builds for Visual Studio 2022 x86
- Precompiled debug/release binaries and debug symbols
- Precompiled addons: loadpng, jpgalleg, alleggl (build-ready)
- Built against libpng 1.6.43 and zlib 1.3.1

### Static Linking Notes

When linking Allegro statically, also link these system libraries:

ddraw.lib
dxguid.lib
dinput8.lib
dsound.lib
winmm.lib
gdi32.lib
