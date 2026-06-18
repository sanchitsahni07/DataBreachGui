# Enigma Breach Checker

A small desktop GUI to check whether an email address appears in known data breaches,
using the [XposedOrNot](https://xposedornot.com/) public API.

## Features

- Simple GUI built with `customtkinter`.
- Looks up an email against the XposedOrNot breach database.
- Displays the list of breaches the address was found in, or a clean result if none.

## Requirements

- Python 3
- `customtkinter`
- `requests`

```bash
pip install customtkinter requests
```

## Usage

```bash
python gui.py
```

Enter an email address and run the check. Results are shown in the window.

## Notes

- Uses the public XposedOrNot API: `https://api.xposedornot.com/v1/check-email/<email>`.
- Network access is required.
- For educational and personal security-awareness use.

## Author

Sanchit Sahni — https://github.com/0xpivot
