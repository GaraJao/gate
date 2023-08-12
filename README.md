<h1 align="center">
    <img alt="preview" src="https://i.imgur.com/Ia7jGrA.png" width="100%">
</h1 align="center">

<p align='center'>
  <img alt='License' src='https://img.shields.io/badge/license-mit-1C1E26?style=for-the-badge&labelColor=1C1E26&color=d58453&' />
  <img alt='version' src='https://img.shields.io/badge/version-1.0-1C1E26?style=for-the-badge&labelColor=1C1E26&color=d58453&' />
</p>

##### Create file `secret.ino` and fill in below parameters

```c
// Code settings (16 chars)
const char *key = "";
const char *iv  = "";

// Wi-fi settings 
const char *SSID = "";
const char *PASS = "";

// API settings
const char *server_name = ""; // Only HTTPS
const char *token       = ""; // Bearer token
const char *gate_id     = ""; // UUID from gate
```

## 📕 Libraries

- [THiNX AESLib](https://github.com/suculent/thinx-aes-lib)
- [RTClib](https://www.arduino.cc/reference/en/libraries/rtclib/)
- [ArduinoJson](https://github.com/bblanchon/ArduinoJson)

## 🛠️ Technologies

- [C++](https://learn.microsoft.com/en-us/cpp/cpp/?view=msvc-170)
- [Arduino IDE](https://www.arduino.cc/en/software)

## 📄 License
MIT © Matheus Bonadio