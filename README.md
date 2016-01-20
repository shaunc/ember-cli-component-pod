# Ember-cli-component-pod

Addon allowing generation of pod components together with `style.scss`
for [ember-component-css](https://github.com/ebryn/ember-component-css)
support.

We assume that your `.ember-cli` has `"usePods": true`.

## Installation

* `ember install ember-cli-component-pod`

## Generate component

* `ember g component-pod foo/bar-ish`

Will generate `component.js`, `template.hbs` and `style.scss` in
`app/foo/bar-ish/`.

The comment headers support `yuidoc` tags:

* `@module` -- your app name
@ `@submodule` -- name of the component.


