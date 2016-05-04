# Tredly CLI

Version 0.1.0
Apr 29 2016

This is a software package to provide remote access to Tredly Host. You can find out more information about Tredly at **[http://tredly.com](http://tredly.com)**

## Installation

Requires tredly-api 0.1.0 **[https://github.com/tredly/tredly-api](https://github.com/tredly/tredly-api)**

1. Install **Node.js**
2. Install **npm**
3. Run `sudo npm link`

## Usage

Tredly CLI is remote access command line client for tredly-api 0.1.0 **[https://github.com/tredly/tredly-api](https://github.com/tredly/tredly-api)**. You can find out more information about tredly commands at [Tredly Documentation](https://github.com/tredly/tredly-host/blob/master/README.md)

It also provides additional commands for remote access:

- `tredly connect` - use this command to connect to remote Tredly Host.
- `tredly push container` - use this command from your project directory (which contains Tredlyfile) to push the project to remote Tredly Host and create/update container. The command accept the same parameters as `tredly create container`. See [Tredly Documentation](https://github.com/tredly/tredly-host/blob/master/README.md)


## Contributing

We encourage you to contribute to Tredly. Please check out the [Contributing documentation](https://github.com/tredly/tredly-cli/blob/master/CONTRIBUTING.md) for guidelines about how to get involved.

## License

Tredly API is released under the [GNU General Public License v3](http://www.gnu.org/licenses/gpl-3.0.en.html).
