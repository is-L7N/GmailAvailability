# Gmail Username Availability Checker

This tool checks the availability of a Gmail username by simulating part of the Google signup process.

## Features

- Verifies whether a specific Gmail username is available.
- Mimics a real browser using randomized User-Agent headers.
- Uses secure cookie generation.
- Designed for privacy and non-intrusive checks.

## Usage

```bash
python GmailAvailability.py
```

Enter the email or username when prompted (e.g., `example` or `example@gmail.com`).

### Output

- If available: `{"available": True}`
- If not available: `{"available": False}`
- If failed: `{'__Host-GAPS': False, 'TL': False, 'message': 'bad get cookies'}`

## Developer

[![Author](https://img.shields.io/badge/Author-L7N-blue?style=for-the-badge&logo=github)](https://github.com/is-L7N)
[![Telegram](https://img.shields.io/badge/Telegram-PyL7N-2CA5E0?style=for-the-badge&logo=telegram)](https://t.me/PyL7N)
[![GitHub](https://img.shields.io/badge/GitHub-is--L7N-181717?style=for-the-badge&logo=github)](https://github.com/is-L7N)
