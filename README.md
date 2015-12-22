# stylep-menu-icon
<img src=https://avatars1.githubusercontent.com/u/16121328?v=3&s=200 title=stylep-button align=right height=95>

A simple animated menu icon that transforms into a close icon.

## Install
You can install using the [spm](https://github.com/stylep/stylep) command or install using npm and the project name.

``` shell
spm install menu-icon
```

## Usage
``` css
/* menu.css */

@import “stylep-menu-icon”;

.menu-icon {

  /* Button Design Pattern */
  @extend %menu-icon;

  /* Customize your button */
  @mixin menu-icon-color param, param;

  /* or roll your own */

  /* add something custom in here */
}
```

## Patterns
Placeholder selectors that contain common styles for structure and basic behavior.

#### `@extend %menu-icon;`
Describe what this pattern does.

## Styles
Customizable presets that give your pattern a specific style-set.

### name-of-style
Describe the visual look and feel of this style.

##### Options

* `$param-name: default-value` Describe what this does

##### Example
```css
/* describe in english what this following statement really means in detail */
@mixin menu-icon-color default-value;
```

