# ProviderFinder

Python API for finding streaming and purchase provider for a movie in your country.

## Install

```bash
pip install ProviderFinder
```

## Usage

```python
from ProviderFinder import ProviderFinder

p = ProviderFinder()

film_info = p.get_providers('pulp fiction', year=1994, locale='AU', language='en')
```

## Locales and Languages

Locales

```python
{
		'Argentina': 'AR',
		'Austria': 'AT',
		'Australia': 'AU',
		'Belgium': 'BE',
		'Brazil': 'BR',
		'Canada': 'CA',
		'Chile': 'CL',
		'Colombia': 'CO',
		'Czech Republic': 'CZ',
		'Denmark': 'DK',
		'Ecuador': 'EC',
		'Estonia': 'EE',
		'Finland': 'FI',
		'France': 'FR',
		'Germany': 'DE',
		'Greece': 'GR',
		'Hungary': 'HU',
		'India': 'IN',
		'Indonesia': 'ID',
		'Ireland': 'IE',
		'Italy': 'IT',
		'Japan': 'JA',
		'Latvia': 'LV',
		'Lithuania': 'LT',
		'Malaysia': 'MY',
		'Mexico': 'ME',
		'Netherlands': 'NL',
		'New Zealand': 'NZ',
		'Norway': 'NO',
		'Peru': 'PE',
		'Philippines': 'PH',
		'Poland': 'PL',
		'Portugal': 'PT',
		'Romania': 'RO',
		'Russia': 'RU',
		'Singapore': 'SG',
		'South Africa': 'ZA',
		'South Korea': 'KR',
		'Spain': 'ES',
		'Sweden': 'SE',
		'Switzerland': 'CH',
		'Thailand': 'TH',
		'Turkey': 'TR',
		'United Kingdom': 'GB',
		'United States': 'US',
		'Venezuela': 'VE',
}
```

Languages
```python
{
		'English': 'en',
		'Spanish': 'es',
		'German': 'de',
		'French': 'fr',
		'Portugeuse': 'pt',
		'Czech': 'cs',
		'Finnish': 'fi',
		'Greek': 'el',
		'Hungarian': 'hu',
		'Italian': 'it',
		'Japanese': 'jp',
		'Korean': 'ko',
		'Polish': 'pl',
		'Romanian': 'ro',
		'Russian': 'ru',
		'Turkish': 'tr',
}
```
