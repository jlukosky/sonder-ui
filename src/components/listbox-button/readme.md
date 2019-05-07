# Listbox button

A test of a readonly single `<select>` alternative that uses `role="combobox"` with a `<input readonly>` child. Basic functionality only, no autocomplete or filtering.

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
