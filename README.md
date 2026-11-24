# Helen's Picture Viewer — Fire TV photo collection viewer

## Current test version: V2 / 1.1.0

**Fire Stick Downloader (short verified link):** https://is.gd/HelensTV2

Type `https://is.gd/HelensTV2` in the Downloader URL box. This redirects to the V2 APK below.

**[Download V2 Fire Stick APK directly](https://raw.githubusercontent.com/Shawnkrug/helens-picture-viewer-downloads/main/releases/HelensPictureViewer-FireStick-v2-TEST.apk)**

- File: `HelensPictureViewer-FireStick-v2-TEST.apk`
- Bytes: 249601
- SHA-256: `654b108f7651f2e0a5d415123a4ccaabeb6cdec22dc076a8cd7ed2f4d59c342b`
- Android-based Amazon Fire OS test sideload; NOT Vega OS; test-signed with debug certificate; no physical device QA completed
- If Android refuses to update V1 due changed test signing certificate, uninstall V1 first.

### How to use
1. On an Android-based Fire Stick, use AFTVnews Downloader to download the **V2** APK using the direct link above and install it.
2. Launch Helen's Picture Viewer. Scan the QR with iPhone/iPad Camera while on the same trusted Wi-Fi.
3. On the local Safari page, choose the entire photo collection and tap the picture where you want to start.
4. Tap **Send Collection to TV** once; wait until all photos are received. TV will not rapidly cycle during upload.
5. TV shows your chosen starting picture. Press Fire Stick remote **Left/Right** to move exactly one picture at a time; **Select** toggles slideshow, **Back** displays the QR.
6. Available TV storage, rather than a 20-picture circular buffer, limits collection size. Transfer is local over HTTP with an ephemeral QR pairing token. Photos are temporary and cleared on TV app restart.

### Older version
[V1 APK, retained for rollback](https://raw.githubusercontent.com/Shawnkrug/helens-picture-viewer-downloads/main/releases/HelensPictureViewer-FireStick-v1-TEST.apk). V1 holds only 20 images and should not be used for complete collections.

iPhone native companion V2 exists as an unsigned IPA in the owner's private Google Drive; the Safari QR interface works without installing the IPA.
