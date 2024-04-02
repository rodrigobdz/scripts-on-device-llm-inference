# Scripts for On-Device LLM Inference

Code to accompany the [tutorial](https://developers.google.com/mediapipe/solutions/genai/llm_inference/android) to run LLM inference on-device.

Repository contains adapted scripts and additional documentation.

## Requirements

- [adb](https://developer.android.com/tools/adb)

- [Add](https://stackoverflow.com/a/34532364) `$ANDROID_HOME/platform-tools` to your `PATH`

## Installation

- Download the `gemma-2b-it-gpu-int4.bin` model and place in the root directory

## Usage

- Push the local model to the Android device

  ```sh
  ./script/push <LOCAL_PATH_TO_MODEL>
  ```

## Contributing

Please read [contributing.md](contributing.md) for details on the guidelines for this project.

## Credits

- Scripts follow [rodrigobdz/styleguide-sh](https://github.com/rodrigobdz/styleguide-sh)
- Linter configuration files imported from [rodrigobdz/linters](https://github.com/rodrigobdz/linters)
- Readme is based on [rodrigobdz/minimal-readme](https://github.com/rodrigobdz/minimal-readme)

## License

[The Unlicense](license)
