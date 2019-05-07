# Autoselect active option combobox

A test of an alternative to a native `<select>` that uses `div` with `role="combobox"` with an `<input>` child. Provides filtering. Instead of autocomplete the first matching option is selected.

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
