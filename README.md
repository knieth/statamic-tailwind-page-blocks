<!-- statamic:hide --><p align="center"><img src="https://statamic.com/assets/branding/Statamic-Logo-Rad.png" width="100" alt="Statamic Logo" /></p>
<h1 align="center">
  Statamic Starter Kit: Tailwind Page Blocks
</h1>

![Statamic 3.2+](https://img.shields.io/badge/Statamic-3.2+-FF269E?style=for-the-badge&link=https://statamic.com)
<!-- /statamic:hide -->

## Features
- Pages Blocks structure, pick the TailwindUI component you want.
- Clean & modern typography using [Inter](https://rsms.me/inter/)
- Beautifully responsive
- Built with [TailwindCSS](https://tailwindcss.com)
- Itty bitty [Alpine.js](https://github.com/alpinejs/alpine) for interactions

## Screenshot

![screencapture-statamic-tailwind-page-blocks-test-2022-07-28-14_04_48](https://user-images.githubusercontent.com/17942162/181432315-9b0342f0-c389-480f-aec3-d27f2176a1ab.png)

## Quick Start

### 1. Make a new user

The above installers should prompt you to make a user, but you can also run `php please make:user`. You'll want it to be a `super` so you have access to everything.

### 2. Recompile the CSS (optional)

The [TailwindCSS](https://tailwindcss.com/) included in this kit is compiled with [PurgeCSS](https://purgecss.com/) to reduce filesize on any unused classes and selectors. If you want to modify anything, just recompile it.

```
npm i && npm run dev
```

To compile for production again:

```
npm run production
```

### 3. Do your thing!

If you're using [Laravel Valet](https://laravel.com/docs/valet) (or similar), your site should be available at `http://my-site.test`. You can access the control panel at `http://my-site.test/cp` and login with your new user. Open up the source code, follow along with the [Statamic 3 docs](https://statamic.dev), and enjoy!

## Contributing

Contributions are always welcome, no matter how large or small. Before contributing, please read the [code of conduct](https://github.com/statamic/cms/wiki/Code-of-Conduct).
