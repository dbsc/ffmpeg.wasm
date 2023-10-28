# ffmpeg.wasm
This is a fork that removes the usage of blob URLs when loading ffmpeg. This is because otherwise ffmpeg may fail to load if the Content Security Policy (CSP) of the document where ffmpeg.wasm is loaded does not allow blob URLs.
