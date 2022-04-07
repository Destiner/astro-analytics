# Astro Analytics

_A collection of Astro components for popular app analytics providers_

Supported services:
* Google Analytics
* Simple Analytics
* Fathom
* Plausible
* Metrical

## Installation

```bash
npm install astro-analytics
```

## Usage

```js
import { Fathom } from 'astro-analytics';
```

```html
<Fathom site="ABCDEF" />
<GoogleAnalytics id="UA-156492295-1" />
<Metrical app="j5gZ1K26a" />
<Plausible domain="yourdomain.com" />
<SimpleAnalytics />
```
