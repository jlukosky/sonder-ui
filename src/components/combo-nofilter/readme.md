# Readonly combobox

A test of an alternative to the native `<select>` using `role="combobox"` with a `<input readonly>` child.

- Typing selects first matching option (if it exists)
- Typing does not filter options (by design)

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
