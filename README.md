# surea11y

This is the command entry point for [@surea11y/cli](https://github.com/SureA11y/cli#readme), the SureA11y command-line WCAG accessibility scanner.

## Usage

```sh
npx surea11y scan ./index.html
npx surea11y scan https://example.com/
```

The full options are in the [@surea11y/cli README](https://github.com/SureA11y/cli#readme).

## Which package do I need?

| I want to… | Install |
|---|---|
| Add accessibility checks to **Playwright** tests | `@surea11y/core` and [`@surea11y/playwright`](https://github.com/SureA11y/playwright#readme) |
| …**Puppeteer** | `@surea11y/core` and [`@surea11y/puppeteer`](https://github.com/SureA11y/puppeteer#readme) |
| …**Selenium** | `@surea11y/core` and [`@surea11y/selenium`](https://github.com/SureA11y/selenium#readme) |
| …**Cypress** | `@surea11y/core` and [`@surea11y/cypress`](https://github.com/SureA11y/cypress#readme) |
| …**WebdriverIO** | `@surea11y/core` and [`@surea11y/webdriverio`](https://github.com/SureA11y/webdriverio#readme) |
| Assert in **Jest or Vitest** component tests | `@surea11y/core` and [`@surea11y/test-matchers`](https://github.com/SureA11y/test-matchers#readme) |
| Scan static HTML from a **terminal or CI pipeline** | [`@surea11y/cli`](https://github.com/SureA11y/cli#readme) |
| Run the engine against **a DOM I already have** | `@surea11y/core` |
| **Build my own tool** on the engine (a CLI, an extension, a dashboard, a report generator) | `@surea11y/core`, with [`docs/BUILDING_ON_CORE.md`](https://github.com/SureA11y/core/blob/main/docs/BUILDING_ON_CORE.md) |

## License

MIT
