# Github Backend
[![node.js][node-button]][node]


| Code | Description |
| --- | --- | --- | --- |
| `title_color` | Card's title color. | string (hex color) | `2f80ed` |
| `text_color` | Body text color. | string (hex color) | `434d58` |
| `icon_color` | Icons color if available. | string (hex color) | `4c71f2` |
| `border_color` | Card's border color. Does not apply when `hide_border` is enabled. | string (hex color) | `e4e2e2` |
| `bg_color` | Card's background color. | string (hex color or a gradient in the form of *angle,start,end*) | `fffefe` |
| `hide_border` | Hides the card's border. | boolean | `false` |
| `theme` | Name of the theme, choose from [all available themes](themes/README.md). | enum | `default` |
| `cache_seconds` | Sets the cache header manually (min: 21600, max: 86400). | integer | `1800` |
| `locale` | Sets the language in the card, you can check full list of available locales [here](#available-locales). | enum | `en` |
| `border_radius` | Corner rounding on the card. | number | `4.5` |
