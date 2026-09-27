# user-generator

A small command‑line tool that generates 3‑4 character usernames and checks if they are free on TikTok or X (formerly Twitter).

## Usage

```bash
python app.py
```

You will be prompted to choose a platform (`t` for TikTok, `x` for X) and the number of usernames to generate.

## Features

* Random 3‑4 character usernames (mix of rare letters, vowels, digits)
* Parallel checks (20 workers by default)
* Supports both TikTok and X

## Installation

```bash
pip install -r requirements.txt
```

## License

MIT
