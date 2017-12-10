# AirplaneJS

An ADS-B receiver which plots nearby airplanes on a map live.

[![Build status](https://travis-ci.org/watson/airplanejs.svg?branch=master)](https://travis-ci.org/watson/airplanejs)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

## Prerequisites

This software requires an [RTL-SDR USB
dongle](https://www.rtl-sdr.com/buy-rtl-sdr-dvb-t-dongles/) in order
run.

## Usage

```
npx airplanejs
```

This should open your default browser at
[http://localhost:3000](http://localhost:3000).

Alternative approach:

1. Install AirplaneJS globally:
   ```
   npm install airplanejs -g
   ```
1. Run AirplaneJS:
   ```
   airplanejs
   ```

## License

MIT