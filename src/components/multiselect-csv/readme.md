# Multiselect CSV combobox

A test of an alternative to a native `<select>` that uses a div with `role="combobox"` with an `<input>` child. Filters values and pressing `enter` selects.

## Purpose

## Testing

### Test setup

### Results

## Design Guidelines

### Keyboard Interaction

<!-- Auto Generated Below -->


## Properties

| Property  | Attribute | Description                 | Type             | Default     |
| --------- | --------- | --------------------------- | ---------------- | ----------- |
| `label`   | `label`   | String label                | `string`         | `undefined` |
| `options` | --        | Array of name/value options | `SelectOption[]` | `undefined` |


## Events

| Event    | Description                                | Type                |
| -------- | ------------------------------------------ | ------------------- |
| `select` | Emit a custom select event on value change | `CustomEvent<void>` |


----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
