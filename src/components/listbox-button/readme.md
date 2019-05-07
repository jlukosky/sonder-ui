# Listbox button

A test of a multiselect alternative to `<select>` that uses `role="combobox"` with a `<input>` child. Selected items are added to a list above the combobox. Supports filtering.

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
