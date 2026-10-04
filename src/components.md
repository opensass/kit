# 🧩 Open SASS Components

**Open SASS Components** are a growing collection of UI elements designed to be **modular**, **framework-agnostic**, and **ready for any stack**. All components are built with flexibility in mind and work across **Yew**, **Dioxus**, and **Leptos**.

## 📦 Component Categories

| Category     | Components                                                                           | Status    |
| ------------ | ------------------------------------------------------------------------------------ | --------- |
| Data Display | `Accordion`, `Avatar`, `Badge`, `Card`, `Code`, `ELD`, `Image`, `Table`              | ✅ Stable |
| Data Entry   | `Form`, `Input`, `OTP`, `Radio`, `Select`, `Slider`, `Checkbox`, `Listbox`, `Switch` | ✅ / 🚧   |
| Date & Time  | `Calendar`, `Date`, `Time Input`                                                     | 🚧 TODO   |
| Feedback     | `Alert`, `Skeleton`, `Progress`, `Spinner`, `Toast`, `Tooltip`                       | ✅ / 🚧   |
| Landing Page | `Hero`, `Pride`, `Sushi`                                                             | ✅ Stable |
| Navigation   | `Browser`, `Navbar`, `Sidebar`, `Breadcrumbs`, `Pagination`, `Tabs`                  | ✅ / 🚧   |
| Overlays     | `Drawer`, `Dropdown`, `Modal`, `Popover`                                             | 🚧 TODO   |
| Scroll       | `Scroll`                                                                             | ✅ Stable |
| Structure    | `Divider`, `Spacer`                                                                  | 🚧 TODO   |
| Utilities    | `Autocomplete`, `Kbd`                                                                | 🚧 TODO   |
| Localization | `I18n`                                                                               | ✅ Stable |
| System       | `Theme`                                                                              | ✅ Stable |
| Typography   | `Link`                                                                               | 🚧 TODO   |

## 🚀 Getting Started

To use a component, simply import it via the CLI:

```sh
os add component-name framework-name
```

For example, to add `accordion-rs` to a Yew project:

```sh
os add accordion-rs yew
```

Or to a Dioxus project:

```sh
os add accordion-rs dio
```

Or to a Leptos project:

```sh
os add accordion-rs lep
```

## 🔗 Framework Support

| Component      | Yew | Dioxus | Leptos |
| -------------- | :-: | :----: | :----: |
| `accordion-rs` | ✅  |   ✅   |   ✅   |
| `alert-rs`     | ✅  |   ✅   |   ✅   |
| `avatar-rs`    | ✅  |   ✅   |   ✅   |
| `badge-rs`     | ✅  |   ✅   |   ✅   |
| `browser-rs`   | ✅  |   ✅   |   -    |
| `card-rs`      | ✅  |   ✅   |   ✅   |
| `code-rs`      | ✅  |   ✅   |   ✅   |
| `form-rs`      | ✅  |   ✅   |   ✅   |
| `hero`         | ✅  |   ✅   |   ✅   |
| `i18n-rs`      | ✅  |   ✅   |   ✅   |
| `image-rs`     | ✅  |   ✅   |   ✅   |
| `input-rs`     | ✅  |   ✅   |   ✅   |
| `navbar`       | ✅  |   ✅   |   ✅   |
| `otp-rs`       | ✅  |   ✅   |   ✅   |
| `pride-rs`     | ✅  |   ✅   |   -    |
| `radio-rs`     | ✅  |   ✅   |   ✅   |
| `scroll-rs`    | ✅  |   ✅   |   ✅   |
| `select-rs`    | ✅  |   ✅   |   ✅   |
| `sidebar`      | ✅  |   ✅   |   ✅   |
| `skeleton-rs`  | ✅  |   ✅   |   ✅   |
| `slider-rs`    | ✅  |   ✅   |   ✅   |
| `sushi-rs`     | ✅  |   ✅   |   ✅   |
| `table-rs`     | ✅  |   ✅   |   ✅   |
| `theme-rs`     | ✅  |   ✅   |   -    |
| `Checkbox`     | 🚧  |   🚧   |   🚧   |
| `Listbox`      | 🚧  |   🚧   |   🚧   |
| `Switch`       | 🚧  |   🚧   |   🚧   |
| `Calendar`     | 🚧  |   🚧   |   🚧   |
| `Date`         | 🚧  |   🚧   |   🚧   |
| `Time Input`   | 🚧  |   🚧   |   🚧   |
| `Progress`     | 🚧  |   🚧   |   🚧   |
| `Spinner`      | 🚧  |   🚧   |   🚧   |
| `Toast`        | 🚧  |   🚧   |   🚧   |
| `Tooltip`      | 🚧  |   🚧   |   🚧   |
| `Breadcrumbs`  | 🚧  |   🚧   |   🚧   |
| `Pagination`   | 🚧  |   🚧   |   🚧   |
| `Tabs`         | 🚧  |   🚧   |   🚧   |
| `Drawer`       | 🚧  |   🚧   |   🚧   |
| `Dropdown`     | 🚧  |   🚧   |   🚧   |
| `Modal`        | 🚧  |   🚧   |   🚧   |
| `Popover`      | 🚧  |   🚧   |   🚧   |
| `Divider`      | 🚧  |   🚧   |   🚧   |
| `Spacer`       | 🚧  |   🚧   |   🚧   |
| `Autocomplete` | 🚧  |   🚧   |   🚧   |
| `Kbd`          | 🚧  |   🚧   |   🚧   |
| `Link`         | 🚧  |   🚧   |   🚧   |

## 🧰 Component Features

- [x] Accessible markup (ARIA support where applicable).
- [x] Mobile-friendly by default.
- [x] Supports theming via CSS custom properties.
- [x] Light/Dark mode compatible.
- [x] Lightweight, no runtime dependencies.
- [x] Multi-language support (i18n-ready components).
- [x] Theme Switcher.

## 🙋 Need Help?

Join our developer community, open issues, or request a new component:

- [GitHub Discussions](https://github.com/opensass/kit/discussions).
- [Discord Server](https://discord.gg/b5JbvHW5nv).

> 🔧 Open SASS Components: Made to fit your stack, not the other way around.
