# GaraJão gate

<p align='left'>
  <img alt='License' src='https://img.shields.io/static/v1?label=license&message=MIT&color=d58453&labelColor=555' />
  <img alt='version' src='https://img.shields.io/static/v1?label=version&message=v1.0&color=d58453&labelColor=555' />
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