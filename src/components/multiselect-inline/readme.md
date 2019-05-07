# Multiselect inline buttons combobox

A test of a multiselect alternative to `<select>` that uses `role="combobox"` with a `<input>` child. Selected items are added to a list within the combobox and visually appear as buttons with the input (although they immediately precede it in the DOM). Supports filtering.

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
| `options` | --        | Array of name/value options | `SelectOption[]` | `[]`        |


## Events

| Event    | Description                                | Type                |
| -------- | ------------------------------------------ | ------------------- |
| `select` | Emit a custom select event on value change | `CustomEvent<void>` |


----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
