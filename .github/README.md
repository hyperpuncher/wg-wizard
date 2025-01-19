<div align="center">
    <img src="logo.png" alt="logo" width=200 height=200>
    <h1>wg-wizard</h1>
    <p>Simple WireGuard setup script for Debian 🪄</p>
</div>

## Install
```sh
curl -sOL https://github.com/hyperpuncher/wg-wizard/raw/refs/heads/main/wg-wizard
chmod +x wg-wizard
mv wg-wizard /usr/local/bin
```

## Usage
```sh
Usage: wg-wizard [options]

Options:
 -a <client_name>  Add new client
 -r <client_name>  Remove client
 -l                List clients
 -i                Setup wireguard
```
