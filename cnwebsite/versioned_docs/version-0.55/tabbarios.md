---
id: version-0.55-tabbarios
title: TabBarIOS
original_id: tabbarios
---

### Props

* [View props...](view.md#props)

- [`barStyle`](tabbarios.md#barstyle)
- [`barTintColor`](tabbarios.md#bartintcolor)
- [`itemPositioning`](tabbarios.md#itempositioning)
- [`style`](tabbarios.md#style)
- [`tintColor`](tabbarios.md#tintcolor)
- [`translucent`](tabbarios.md#translucent)
- [`unselectedItemTintColor`](tabbarios.md#unselecteditemtintcolor)
- [`unselectedTintColor`](tabbarios.md#unselectedtintcolor)

---

# 文档

## Props

### `barStyle`

The style of the tab bar. Supported values are 'default', 'black'. Use 'black' instead of setting `barTintColor` to black. This produces a tab bar with the native iOS style with higher translucency.

| 类型                     | 必填 |
| ------------------------ | -------- |
| enum('default', 'black') | 否       |

---

### `barTintColor`

Background color of the tab bar

| 类型               | 必填 |
| ------------------ | -------- |
| [color](colors.md) | 否       |

---

### `itemPositioning`

Specifies tab bar item positioning. Available values are:

* fill - distributes items across the entire width of the tab bar
* center - centers item in the available tab bar space
* auto (default) - distributes items dynamically according to the user interface idiom. In a horizontally compact environment (e.g. iPhone 5) this value defaults to `fill`, in a horizontally regular one (e.g. iPad) it defaults to center.

| 类型                           | 必填 |
| ------------------------------ | -------- |
| enum('fill', 'center', 'auto') | 否       |

---

### `style`

| 类型       | 必填 |
| ---------- | -------- |
| View.style | 否       |

---

### `tintColor`

Color of the currently selected tab icon

| 类型               | 必填 |
| ------------------ | -------- |
| [color](colors.md) | 否       |

---

### `translucent`

A Boolean value that indicates whether the tab bar is translucent

| 类型 | 必填 |
| ---- | -------- |
| bool | 否       |

---

### `unselectedItemTintColor`

Color of unselected tab icons. Available since iOS 10.

| 类型               | 必填 |
| ------------------ | -------- |
| [color](colors.md) | 否       |

---

### `unselectedTintColor`

Color of text on unselected tabs

| 类型               | 必填 |
| ------------------ | -------- |
| [color](colors.md) | 否       |