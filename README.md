# PallyCon DRM CLI Packager
PallyCon DRM CLI Packager is a command line interface (CLI) based content packaging tool used for PallyCon Multi-DRM service.
It can package MP4 video and/or M4A audio files into five different types of content below.

1. DASH: A method of applying PlayReady and Widevine Modular DRM by packaging streaming contents with MPEG-DASH CENC standard.
2. HLS: A method of applying FPS (FairPlay Streaming) DRM by packaging HLS-AES streaming contents.
3. CMAF: Applying PlayReady, Widevine, and FairPlay DRM by packaging contents with CMAF(Common Media Application Format) type.
4. NCG: Content encryption by Inka Entworks' proprietary NCG (Netsync Content Guard) DRM for downloading or progressive download scenario.
5. HLS-NCG: HLS content packaging with SAMPLE-AES clear key protected by NCG DRM.
6. WisePlay: A method of applying Huawei's WisePlay DRM by packaging streaming contents with MPEG-DASH CENC standard, primarily used for protecting premium content on Huawei mobile devices and platforms.

- [Guide document](https://pallycon.com/docs/en/multidrm/packaging/cli-packager/)
- [Helpdesk for technical support](https://pallycon.zendesk.com)
