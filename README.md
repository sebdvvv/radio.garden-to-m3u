<p align="center">
  <img src="docs/assets/logo.png" alt="radio.garden_to_m3u logo" width="200"
  style = "border-radius: 10%;"/>
</p>

<h1 align="center">Radio.garden to M3U</h1>

<p align="center">
  <strong>Generate an M3U playlist from radio.garden public API data</strong>
</p>

<p align="center">
  <a href="#pre-requisites">Pre-requisites</a> •
  <a href="#installation">Installation</a> •
  <a href="#license">License</a> •
  <a href="#disclaimer">Disclaimer</a> •
  <a href="#acknowledgements">Acknowledgements</a>
</p>

<p align="center">
  <a href="https://discord.gg/7qK8sfEq2q">
    <img src="https://img.shields.io/discord/1068543728274382868?color=7289da&label=Support&logo=discord&logoColor=7289da&style=for-the-badge" alt="Discord">
  </a>
  <a href="https://www.python.org/">
    <img src="https://img.shields.io/github/languages/top/ovosimpatico/radio.garden-to-m3u?logo=python&logoColor=yellow&style=for-the-badge" alt="Language">
  </a>
  <a href="https://github.com/ovosimpatico/radio.garden-to-m3u/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/ovosimpatico/radio.garden-to-m3u?style=for-the-badge" alt="License">
  </a>
</p>


## Pre-requisites

- Python

## Installation

1. Clone the repository

```bash
git clone https://github.com/ovosimpatico/radio.garden-to-m3u.git
```

2. Run the script

```bash
python main.py --country COUNTRY --state STATE
```

The m3u file will be created in the same directory as the script, as radio.m3u. It can be used on any player that supports m3u playlists, such as VLC or MPV.

Examples:

```bash
python main.py --country "Brazil" --state "SP"
```

```bash
python main.py --country "United States" --state "LA"
```

```bash
python main.py --country "Bulgaria"
```

## License

This project is licensed under the Affero General Public License v3.0. See the [LICENSE](LICENSE) file for details.

## Disclaimer

This project is not affiliated with radio.garden in any way. It uses the public API provided by the website to create a m3u playlist.

## Acknowledgements

- [radio-garden-openapi](https://github.com/jonasrmichel/radio-garden-openapi)