# Porcupine Wake-Word Detection
This is a fork of the open source project [Porcupine](https://github.com/Picovoice/Porcupine)

## How to build on Mac
### Prerequisites
You will need:
* Homebrew  - Ref: https://brew.sh/

### Setup
Follow the below steps to setup everything needed
```bash
brew install portaudio
brew install python@3
pip3 install pyaudio
pip3 install numpy
pip3 install requests

# This repository is ~3GB, git clone may take a while
git clone git@github.com:sunkarah/Porcupine.git
```

### Running the application
Follow the below steps to run the application
```sbt
python3 demo/python/porcupine_demo.py --keyword_file_paths resources/keyword_files/alexa_mac.ppn --callback_url http://localhost:8080/capture
```
