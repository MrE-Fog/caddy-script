## :whale: caddy-script
Caddy installation script

[![Build Status](https://github.com/vintagesucks/caddy-script/workflows/Build/badge.svg)](https://github.com/vintagesucks/caddy-script/actions) [![Dependabot](https://badgen.net/badge/Dependabot/enabled/green?icon=dependabot)](https://dependabot.com/) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/a0b0746d7a9f4a9db9fe7ae0d1fd775b)](https://www.codacy.com/app/vintagesucks/caddy-script) [![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-round)](#contributors)

#### Features
- [x] Install Caddy v2.2.1
- [x] Install PHP 7.4
- [x] Install MariaDB
- [x] Register Caddy as a service with systemd
- [x] Configure Caddyfile with file_server, gzip, zstd, php_fastcgi
- [x] Install WordPress [optional]

#### Tested on
- Ubuntu 18.04
- Ubuntu 20.04

#### Usage
`bash <(curl -s https://raw.githubusercontent.com/vintagesucks/caddy-script/v2/main.sh)`

You'll be asked for your timezone, an email and the domain/ip to use.

#### Help
You can read the [Caddy Documentation](https://caddyserver.com/docs/) if you need more information about Caddy.

#### Acknowledgements
- [Validating an IP Address in a Bash Script](https://www.linuxjournal.com/content/validating-ip-address-bash-script) by Mitch Frazier

## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/all-contributors/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
| [<img src="https://avatars0.githubusercontent.com/u/13335308?v=4" width="100px;" alt="Nikolas Evers"/><br /><sub><b>Nikolas Evers</b></sub>](https://nikol.as)<br />[💻](https://github.com/vintagesucks/caddy-script/commits?author=vintagesucks "Code") [🚧](#maintenance-vintagesucks "Maintenance") | [<img src="https://avatars3.githubusercontent.com/u/1649452?v=4" width="100px;" alt="Per Søderlind"/><br /><sub><b>Per Søderlind</b></sub>](https://soderlind.no)<br />[🐛](https://github.com/vintagesucks/caddy-script/issues?q=author%3Asoderlind "Bug reports") [💻](https://github.com/vintagesucks/caddy-script/commits?author=soderlind "Code") |
| :---: | :---: |
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
