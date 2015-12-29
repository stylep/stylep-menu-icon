# stylep-menu-icon
<img src=https://avatars1.githubusercontent.com/u/16121328?v=3&s=200 title=stylep align=right height=95>

A simple animated menu icon that transforms into a close icon.

## Install
You can install using the [spm](https://github.com/stylep/stylep) command or install using npm and the project name.

``` shell
spm install menu-icon
```

## Usage
``` css
/* menu-icon.css */

@import “stylep-menu-icon”;

.menu-icon {

  /* Customize your icon */
  @mixin menu-icon #000, #999, 3px, 14px, .3s;

  /* or roll your own */

  /* add something custom in here */
}
```

## Styles
Customizable presets that give your pattern a specific style-set.

#### `menu-icon`
Draws three bars that look like a menu icon.

##### Options

* `$menu-icon-color: #000` Color of the menu icon
* `$menu-icon-active-color: #000` Color of the menu icon activated
* `$menu-icon-radius: 3px` How rounded the menu icon bars are.
* `$menu-icon-size: 14px` Relative sizing of the menu icon
* `$menu-icon-class: :focus` The class that activates the menu-icon

## License
This project is licensed under the MIT [license](LICENSE).
