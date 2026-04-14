# MouseTester.xyz

**Free Online Mouse Testing Tools**

[mousetester.xyz](https://mousetester.xyz) | [中文介绍](./README.zh-CN.md)

---

## What is MouseTester.xyz?

MouseTester.xyz is a free, browser-based mouse testing toolkit built for gamers, designers, IT professionals, and anyone who cares about mouse performance.

No downloads. No installs. No sign-ups. Just open the site and start testing.

All tests run entirely in your browser using standard Web APIs — your input data never leaves your machine.

---

## Testing Tools

### Mouse Button Test

Test all 5 mouse buttons (left, right, middle, back, forward), scroll wheel, and sensor jitter with instant visual feedback. The interactive diagram highlights each button the moment you press it — the fastest way to confirm everything is registering correctly.

### CPS Test (Clicks Per Second)

Measure how quickly you can click across configurable time intervals from 1 to 60 seconds. The test tracks your raw click count, average CPS, and peak CPS — perfect for benchmarking jitter clicking, butterfly clicking, and drag clicking techniques.

### Double Click Test

Detect switch bouncing, the most common mouse defect. When a switch degrades, a single press can register as two clicks. The tool measures the time gap between successive click events and flags intervals below a configurable threshold, helping you decide if your switch needs replacement.

### Polling Rate Test

Your mouse's polling rate determines how often it reports its position to the computer, measured in Hz. This test captures raw event timestamps as you move the mouse and calculates the actual report rate, so you can verify whether your mouse truly delivers the 500 Hz or 1000 Hz it advertises.

### DPI Test

DPI (dots per inch) controls how far your cursor moves relative to physical mouse movement. This tool lets you move a known physical distance and compares the expected pixel displacement against the actual result, revealing your true DPI and any deviation from the configured value.

### Coming Soon

- **Latency Test** — Measure click-to-response delay
- **Drag Test** — Evaluate drag precision and smoothness
- **Scroll Test** — Analyze scroll speed and step consistency

---

## Who Is This For?

| Audience | Why |
|---|---|
| **Competitive Gamers** | Verify polling rate and DPI before tournaments. Eliminate hardware variables from the equation. |
| **Designers & Creators** | Ensure consistent cursor behavior for pixel-accurate work in Photoshop, Figma, Illustrator, etc. |
| **IT Professionals** | A standardized, repeatable test suite that runs on any machine with a browser — no install, no config. |
| **Everyday Users** | Quickly confirm double-click issues, skipping, or other mouse problems before deciding on a repair or replacement. |

---

## Key Features

- **100% Browser-based** — Works on Windows, macOS, Linux, and ChromeOS
- **Zero Install** — No downloads, plugins, or special permissions required
- **Privacy First** — All data stays on your device, nothing is uploaded
- **Multi-language** — Available in 8 languages (EN, ZH, JA, KO, DE, FR, ES, PT)
- **Responsive** — Works on any screen size
- **Dark Mode** — Full dark mode support

---

## Tech Stack

- [Next.js](https://nextjs.org) (App Router)
- [React 19](https://react.dev)
- [Tailwind CSS 4](https://tailwindcss.com)
- [TypeScript](https://www.typescriptlang.org)
- Route-based i18n (`/en`, `/zh`, `/ja`, `/ko`, `/de`, `/fr`, `/es`, `/pt`)

---

## License

© 2026 MouseTester.xyz. All rights reserved.
