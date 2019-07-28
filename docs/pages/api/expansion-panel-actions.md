---
filename: /packages/material-ui/src/ExpansionPanelActions/ExpansionPanelActions.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# ExpansionPanelActions API

<p class="description">The API documentation of the ExpansionPanelActions React component. Learn more about the properties and the CSS customization points.</p>

```js
import { ExpansionPanelActions } from '@material-ui/core';
```



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name required">children&nbsp;*</span> | <span class="prop-type">node</span> |  | The content of the component. |
| <span class="prop-name">classes</span> | <span class="prop-type">object</span> |  | Override or extend the styles applied to the component. See [CSS API](#css) below for more details. |
| <span class="prop-name">disableSpacing</span> | <span class="prop-type">bool</span> | <span class="prop-default">false</span> | If `true`, the actions do not have additional margin. |

The `ref` is forwarded to the root element.

Any other properties supplied will be provided to the root element (native element).

## CSS

- Style sheet name: `MuiExpansionPanelActions`.
- Style sheet details:

| Rule name | Global class | Description |
|:-----|:-------------|:------------|
| <span class="prop-name">root</span> | <span class="prop-name">MuiExpansionPanelActions-root</span> | Styles applied to the root element.
| <span class="prop-name">spacing</span> | <span class="prop-name">MuiExpansionPanelActions-spacing</span> | Styles applied to the root element if `disableSpacing={false}`.

You can override the style of the component thanks to one of these customizability points:

- With a rule name of the [`classes` object prop](/customization/components/#overriding-styles-with-classes).
- With a [global class name](/customization/components/#overriding-styles-with-global-class-names).
- With a theme and an [`overrides` property](/customization/globals/#css).

If it's not enough, you can find the [implementation of the component](https://github.com/mui-org/material-ui/blob/master/packages/material-ui/src/ExpansionPanelActions/ExpansionPanelActions.js) for more detail.

## Notes

The component is fully [StrictMode](https://reactjs.org/docs/strict-mode.html) compatible.

## Demos

- [Expansion Panels](/components/expansion-panels/)
