# Custom Emulated Hue Integration

This Home Assistant integration replaces the core `emulated_hue` integration and adds the functionality to expose entities via [Home Assistant's voice assistants expose](https://my.home-assistant.io/redirect/voice_assistants/expose), while removing the functionality to expose via `configuration.yaml`.

- Based on the [integration_blueprint](https://github.com/ludeeus/integration_blueprint).

## Features

- Expose entities via Home Assistant's voice assistants expose.
- Removes the need to configure entity exposure via `configuration.yaml`.

## TODO

- Completely remove YAML configuration and make this configurable via the GUI (config flow).

## Development

This project includes a development container to help you get started quickly. To develop, use the script located at `./scripts/develop` to start a local Home Assistant instance.

## License

This project is licensed under the MIT License.

## Installation

To install this integration via HACS (Home Assistant Community Store), follow these steps:

1. Go to HACS in your Home Assistant instance.
2. Click on "Integrations".
3. Click on the three dots menu in the top right corner and select "Custom repositories".
4. Add the repository URL and select the category as "Integration".
5. Find the new custom repository in the list and click "Install".

For more detailed instructions, refer to the [HACS documentation](https://hacs.xyz/docs/installation/manual).
