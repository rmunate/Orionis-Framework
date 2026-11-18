# HTTP framework comparison

| Framework | Interface | Workers | Status | Requests/s | Mean (ms) | p50 (ms) | p95 (ms) | p99 (ms) | Errors |
| --- | --- | ---: | --- | ---: | ---: | ---: | ---: | ---: | ---: |
| litestar | asgi | 1 | ok | 9035.04 | 11.06 | 10.71 | 12.69 | 15.22 | 0 |
| orionis-asgi | asgi | 1 | ok | 26728.28 | 3.74 | 4.00 | 4.75 | 5.37 | 0 |
| fastapi | asgi | 1 | ok | 7848.48 | 12.73 | 12.39 | 14.55 | 15.74 | 0 |
| starlette | asgi | 1 | ok | 11235.78 | 8.89 | 8.52 | 10.53 | 12.18 | 0 |
| orionis-rsgi | rsgi | 1 | ok | 24763.46 | 4.04 | 4.11 | 4.54 | 6.36 | 0 |
| litestar | asgi | 2 | ok | 17757.69 | 5.63 | 5.06 | 6.74 | 7.46 | 0 |
| fastapi | asgi | 2 | ok | 15559.63 | 6.42 | 6.26 | 7.84 | 9.06 | 0 |
| orionis-rsgi | rsgi | 2 | ok | 39460.25 | 2.53 | 2.61 | 3.18 | 3.88 | 0 |
| starlette | asgi | 2 | ok | 20677.90 | 4.83 | 4.75 | 5.80 | 6.45 | 0 |
| orionis-asgi | asgi | 2 | ok | 42116.66 | 2.37 | 2.40 | 3.10 | 3.74 | 0 |
| litestar | asgi | 3 | ok | 19298.46 | 5.18 | 5.00 | 7.00 | 8.14 | 0 |
| orionis-asgi | asgi | 3 | ok | 52353.22 | 1.91 | 1.82 | 3.10 | 3.95 | 0 |
| fastapi | asgi | 3 | ok | 16409.78 | 6.09 | 5.93 | 7.86 | 9.25 | 0 |
| orionis-rsgi | rsgi | 3 | ok | 51475.36 | 1.94 | 1.80 | 3.29 | 4.31 | 0 |
| starlette | asgi | 3 | ok | 22388.96 | 4.46 | 4.50 | 5.89 | 7.08 | 0 |
| orionis-asgi | asgi | 4 | ok | 47754.31 | 2.09 | 1.97 | 3.64 | 4.74 | 0 |
| fastapi | asgi | 4 | ok | 17726.56 | 5.64 | 5.75 | 9.18 | 10.89 | 0 |
| litestar | asgi | 4 | ok | 19881.25 | 5.03 | 5.00 | 7.94 | 9.69 | 0 |
| starlette | asgi | 4 | ok | 24430.06 | 4.09 | 4.06 | 6.60 | 7.59 | 0 |
| orionis-rsgi | rsgi | 4 | ok | 48876.52 | 2.04 | 1.93 | 3.60 | 4.73 | 0 |
