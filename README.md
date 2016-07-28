# @nib-styles/react-form

Styles for `React` based forms at `nib`.

## Installation

    npm install --save @nib-styles/react-form

## Change log

### 0.9.0

- moved `radio` implementation to `@nib-components/radio`


### 0.8.1

- fix: added `margin: 0` to `divider` to override browser specified margins on `<hr/>`s

### 0.8.0

- break: renamed `form__divider` to `divider` and removed the margin so it can be used independently of the form

### 0.6.1

- fix: fixed disable hover state on `radio` inputs - bg color no longer changes and the cursor is left as the default

### 0.6.0

- break: bumped version of `@nib-styles/v2-buttons` from `^2.1.1` to `^3.0.1` => it should only be breaking if you depend on it for more than the submit button (a primary button)

### 0.5.0

- add: disabled state for control labels
