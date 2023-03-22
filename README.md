# Thien Nguyen Local Tunnel

Thien Nguyen Local Tunnel exposes your localhost to the www for easy testing and sharing! No need to mess with DNS or deploy just to have others test out your changes.

## Quickstart

```
npx tnt 3000
```

## Installation

### Globally

```
npm i -g @thiennguyenpro/thiennguyen-local-tunnel
```

## Usage

When local tunnel is installed globally, just use the `tnt` command to start the tunnel.

```
tnt 3000
```

Your tunnel will be ready immediately with the random endpoint
https://hobby-api.thiennguyen.dev/tunnel/scabrities-rompish


## Custom endpoint
To use your desired endpoint instead of a meaningless random character.
```
tnt 3000 your-custom-endpoint
```
Your tunnel will be ready at https://hobby-api.thiennguyen.dev/tunnel/your-custom-endpoint

