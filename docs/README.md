# IP Fetch

Tool to get geographical location of an ip address or a domain and mark it in a world map in the terminal

![screenshot](/docs/screenshot.webp)

## About

This tool fetches the details about an ip address from an api and displays the location of the target in the world map and other details are printed on a sidebar. It is written in rust and tui is used as UI.

## Usage

```
ip-fetch <TARGET>
```

Target can be an ipv4 or ipv6 address or the url.

Press any key to quit

### Example

From Ip address

```
ip-fetch 8.8.8.8
```

From domain

```
ip-fetch dns.google.com
```

Get details about your ip

```
ip-fetch /
```

## Build

Clone repository

```
git clone https://github.com/youaremagic/ip-fetch
```

Change directory

```
cd ip-fetch
```

Build and run release version in one step

```
cargo run --release -- <TARGET>
```
