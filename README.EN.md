# WhisperDesktop in Bosnian

This is a modified version of the WhisperDesktop project, translated and adapted for the needs of journalists at [Radio Televizija Novi Pazar](https://rtvnp.rs). We thank the original author, Const-me, for the excellent work.

## Project Purpose

The WhisperDesktop project is intended for speech recognition and converting it into text. This version has been translated into Bosnian and adapted for easier use by journalists.

## Compilation Instructions

1. Load `WhisperProj.sln` in Visual Studio 2022.
2. In the solution's "Configuration Manager," change "Active solution configuration" to "Release" (mandatory).
3. Right-click on the Solution and select "Build Solution."
4. The compiled files will appear in the `x64\Release` directory.

Required files for operation:
- `Whisper.dll`
- `WhisperDesktop.exe`

Or you can download the [zip](https://github.com/mirsadf/WhisperProj/releases/download/v1.0.0/WhisperDesktop.zip) with the compiled files.

### Model Download

You need to download the V2 model from the following link: [ggml-large-v2.bin](https://huggingface.co/ggerganov/whisper.cpp/blob/main/ggml-large-v2.bin). This file contains the pre-trained model used for speech recognition. The V3 model is not compatible with this version of WhisperDesktop.

## Author Information

Mirsad Fijuljanin, IT Administrator at [Radio Televizija Novi Pazar](https://rtvnp.rs).

## Original Author

The original project was created by Const-me and is licensed under the Mozilla Public License 2.0.

## License

This project is licensed under the Mozilla Public License 2.0. See the LICENSE file for more details.
