# vespa-robot

Configuração inicial da primeira versão do Vespa Tank Bot

## Setup

### VS Code

* VsCode Extension: vsciot-vscode.vscode-arduino
* VsCode Extension: ms-vscode.cpptools-extension-pack
* Arduino Cli: https://arduino.github.io/arduino-cli/0.21/installation/#download

### Placa Vespa

Url para download das placas e bibliotecas

```sh
arduino-cli core update-index --additional-urls https://dl.espressif.com/dl/package_esp32_index.json

arduino-cli core search esp32 --additional-urls https://dl.espressif.com/dl/package_esp32_index.json
 > esp32:esp32

arduino-cli core install esp32:esp32 --additional-urls https://dl.espressif.com/dl/package_esp32_index.json
```

### Arduino Scketch

Inicialize um projeto arduino

```sh
arduino-cli sketch new .
```

### Vespa Libraries

Instale a biblioteca de dependência da Vespa.

```sh
arduino-cli lib install vespa
```
