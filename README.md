# Astro Analytics 📈

_A collection of Astro components for popular web analytics tools_

Supported services:
* [x] ![Fathom Logo](docs/fathom.webp) Fathom
  * [Website](https://usefathom.com)
  * [Live Demo](https://app.usefathom.com/demo)
* [x] ![Google Analytics Logo](docs/ga.webp) Google Analytics
  * [Website](https://developers.google.com/analytics)
* [x] ![Metrical Logo](docs/metrical.webp) Metrical
  * [Website](https://metrical.xyz)
  * [Live Demo](https://app.metrical.xyz/demo)
* [x] ![Plausible Logo](docs/plausible.webp) Plausible
  * [Website](https://plausible.io)
  * [Live Demo](https://plausible.io/plausible.io)
  * [GitHub](https://github.com/plausible/analytics)
* [x] ![Plausible Logo](docs/simpleanalytics.webp) Simple Analytics
  * [Website](https://simpleanalytics.com/)
  * [Live Demo](https://simpleanalytics.com/simpleanalytics.com)
* [x] ![Umami Logo](docs/umami.webp) Umami
  * [Website](https://umami.is)
  * [Live Demo](https://app.umami.is/share/8rmHaheU/umami.is)
  * [GitHub](https://github.com/umami-software/umami)
* [x] ![Amplitude Logo](docs/amplitude.webp) Umami
  * [Website](https://amplitude.com/)
  * [Live Demo](https://analytics.amplitude.com/login/my-demo)
  * [GitHub](https://github.com/amplitude)
* [ ] ![Matomo Logo](docs/matomo.webp) Matomo
  * [Website](https://matomo.org)
  
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
<Fathom site="ABCDEF" src="https://youdomain.com/script.js" /> (if no src is set it will fallback to https://cdn.usefathom.com/script.js)
<GoogleAnalytics id="UA-156492295-1" />
<Metrical app="j5gZ1K26a" />
<Plausible domain="yourdomain.com" src="https://youdomain.com/yoursript.js" /> (if no src is set it will fallback to https://plausible.io/js/script.js)
<SimpleAnalytics />
<Umami id="4fb7fa4c-5b46-438d-94b3-3a8fb9bc2e8b" src="https://your-umami-app.com/umami.js" />
```
