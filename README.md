# Global Data Repository

This repository contains JSON files with essential global information, including Country Codes, Currencies, and Time Zones.

## Files

### 1. CountryCode.json

- **Description:** Contains country information including code, name, dial code, and flag.
- **Format:** JSON
- **Sample Entry:**
  ```json
  {
      "name": "Afghanistan",
      "dial_code": "+93",
      "code": "AF",
      "flag": "https://twemoji.maxcdn.com/2/svg/1f1e6-1f1eb.svg",
  }


### 2. currency.json

- **Description:** Provides data on international currencies. Here are two categories of currencies Fiat and Crypto.
- **Format:** JSON
- **Sample Entry:**
  ```json
  "fiat": [
        { "id": "AFA", "text": "Afghan Afghani (AFA)" },
  ]

  "crypto" : [
        { "id": "BTC", "text": "Bitcoin (BTC)" },
  ]

### 3. timeZone.json

- **Description:** Includes information about time zones across the globe.
- **Format:** JSON
- **Sample Entry:**
  ```json
  {
      "name": "America/Eirunepe",
      "description": "Acre Time",
      "offset": -300
  }
