<p align="center">
<img src="https://user-images.githubusercontent.com/1490/119319975-f8b77b80-bc72-11eb-8633-ed338f88f67a.png" alt="" width="600" />
</p>

# Artillery Examples

This repo contains examples of how to use various features in Artillery. Every example is self-contained and can be run as-is without external dependencies (other than those in `package.json`).

## Example test definitions

- [using-data-from-csv](./using-data-from-csv) - using data from an external CSV file in vuser scenarios
- [http-set-custom-header](./http-set-custom-header) - set an HTTP header in a `beforeRequest` hook
- [socket-io](./socket-io) - testing a Socket.io service
- [websockets](./websockets) - testing a WebSocket service
- [track-custom-metrics](./track-custom-metrics) - track custom metrics (counters and histograms)

## Plugins and extensions

- [artillery-plugin-hello-world](./artillery-plugin-hello-world) - a "hello world" plugin
- [artillery-plugin-expect](./artillery-plugin-expect) - use `artillery-plugin-expect` to run both load and functional tests

## Starter kits

- [starter-kit](./starter-kit) - @cfryerdev's Artillery starter kit - an example of how a few different bits fit together

# Contributing

Would you like to share an example showing how to use a feature in Artillery with the community? Send us a PR 💜

# License

All code in this repo is licensed under the terms of the [MPL2 license](https://www.mozilla.org/en-US/MPL/2.0/FAQ/).
