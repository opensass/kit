# 🧩 Open SASS Components

**Open SASS Components** are a growing collection of UI elements designed to be **modular**, **framework-agnostic**, and **ready for any stack**. All components are built with flexibility in mind and work with **TailwindCSS**, **Bootstrap**, or **vanilla CSS**.

## 📦 Component Categories

| Category     | Components                                                                           |
| ------------ | ------------------------------------------------------------------------------------ |
| Data Display | `Accordion`, `Avatar`, `Badge`, `Card`, `Code`, `Image`, `Snippet`, `Table`, `User`  |
| Data Entry   | `Checkbox`, `Form`, `Input`, `Listbox`, `OTP`, `Radio`, `Select`, `Slider`, `Switch` |
| Date & Time  | `Calendar`, `Date`, `Time Input`                                                     |
| Feedback     | `Alert`, `Progress`, `Skeleton`, `Spinner`, `Toast`, `Tooltip`                       |
| Navigation   | `Breadcrumbs`, `Browser` `Navbar`, `Pagination`, `Sidebar`, `Tabs`                   |
| Overlays     | `Drawer`, `Dropdown`, `Modal`, `Popover`                                             |
| Structure    | `Divider`, `Spacer`                                                                  |
| Utilities    | `Autocomplete`, `Kbd`, `OTP`                                                         |
| Localization | `I18n`                                                                               |
| System       | `ELD`, `Theme`                                                                       |
| Typography   | `Kbd`, `Link`                                                                        |

## 🚀 Getting Started

To use a component, simply import it via the CLI:

```sh
os add component-name framework-name
```

## 💡 Example: `Accordion` Component (Yew / Rust)

### ✅ Works with Any CSS Framework

### 🌀 TailwindCSS

```rust
<Accordion
    size={Size::Medium}
    expanded={html! { <h3>{ "Section Expanded" }</h3> }}
    collapsed={html! { <h3>{ "Section Collapsed" }</h3> }}
    class="bg-white dark:bg-gray-900 border border-gray-300 dark:border-gray-700 rounded-md shadow"
    expanded_class="bg-blue-100 dark:bg-blue-900 text-blue-800 dark:text-blue-200"
    collapsed_class="bg-gray-100 dark:bg-gray-800 text-gray-800 dark:text-gray-300"
    content_class="p-4"
    style=""
    expanded_style=""
    collapsed_style=""
    content_style=""
    will_open={on_will_open.clone()}
    did_open={on_did_open.clone()}
    will_close={on_will_close.clone()}
    did_close={on_did_close.clone()}
>
    <List>
        <Item align={Align::Left}>{ "Item 1 - Left" }</Item>
        <Item align={Align::Right}>{ "Item 2 - Right" }</Item>
    </List>
</Accordion>
```

### 🎩 Bootstrap

```rust
<Accordion
    size={Size::Medium}
    expanded={html! { <h3 class="accordion-header">{ "Section Expanded" }</h3> }}
    collapsed={html! { <h3 class="accordion-header collapsed">{ "Section Collapsed" }</h3> }}
    class="accordion border border-secondary rounded"
    expanded_class="accordion-body bg-light text-dark"
    collapsed_class="accordion-body bg-white text-secondary"
    content_class="accordion-collapse"
    style=""
    expanded_style=""
    collapsed_style=""
    content_style="padding: 1rem;"
    will_open={on_will_open.clone()}
    did_open={on_did_open.clone()}
    will_close={on_will_close.clone()}
    did_close={on_did_close.clone()}
>
    <List>
        <Item align={Align::Left}>{ "Item 1 - Left" }</Item>
        <Item align={Align::Right}>{ "Item 2 - Right" }</Item>
    </List>
</Accordion>
```

### 🧱 Vanilla CSS

```rust
<Accordion
    size={Size::Medium}
    expanded={html! { <h3 class="os-accordion-title">{ "Section Expanded" }</h3> }}
    collapsed={html! { <h3 class="os-accordion-title os-collapsed">{ "Section Collapsed" }</h3> }}
    class="os-accordion-container"
    expanded_class="os-expanded"
    collapsed_class="os-collapsed"
    content_class="os-content"
    style="border: 1px solid #ccc; border-radius: 6px;"
    expanded_style="background: #f0f8ff; color: #003366;"
    collapsed_style="background: #fafafa; color: #666;"
    content_style="padding: 1rem;"
    will_open={on_will_open.clone()}
    did_open={on_did_open.clone()}
    will_close={on_will_close.clone()}
    did_close={on_did_close.clone()}
>
    <List>
        <Item align={Align::Left}>{ "Item 1 - Left" }</Item>
        <Item align={Align::Right}>{ "Item 2 - Right" }</Item>
    </List>
</Accordion>
```

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
