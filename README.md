# Astro Analytics

_A collection of Astro components for popular web analytics tools

Supported services:
* Fathom
* Google Analytics
* Metrical
* Plausible
* Simple Analytics
* Umami
  
## Installation

```bash
npm install astro-analytics
# or
pnpm install astro-analytics
# or
yarn add astro-analytics
```

## Usage

```js
import { Fathom } from 'astro-analytics';
```

```html
<Fathom site="ABCDEF" />
<GoogleAnalytics id="UA-156492295-1" />
<Metrical app="j5gZ1K26a" />
<Plausible domain="yourdomain.com" src="https://youdomain.com/yoursript.js" /> (if no src is set it will fallback to https://plausible.io/js/script.js)
<SimpleAnalytics />
<Umami id="4fb7fa4c-5b46-438d-94b3-3a8fb9bc2e8b" src="https://your-umami-app.com/umami.js" />
```
