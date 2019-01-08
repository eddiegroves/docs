# curl

https://curl.haxx.se/

## Installation

| MacOS               | Windows              |
| ------------------- | -------------------- |
| `brew install curl` | `scoop install curl` |

## Tips

### Downloading

| Action               | Options               |
| -------------------- | --------------------- |
| Download a file      | `-o, --output <file>` |
| Use server file name | `-O, --remote-name`   |

### View response headers

`-i, --include`

### No proxy

`--noproxy "localhost"`

### Follow redirects

`-L, --location`

### MITM Proxy

`--cacert <file>` or via `CURL_CA_BUNDLE` environment variable.
