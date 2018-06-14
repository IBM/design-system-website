## Color
| Class                                                                        | Property         | SCSS            | HEX     |
|------------------------------------------------------------------------------|------------------|-----------------|---------|
|`.bx--overflow-menu__icon`                                                    | fill             | $ui-05          | #5a6872 |
|`.bx--overflow-menu-options`                                                  | background-color | $ui-01          | #ffffff |
|`.bx--overflow-menu-options__option:hover`                                    | background-color | $hover-row      | #5596e6 at 10% opacity |
| `.bx--overflow-menu-options__option--danger .bx--overflow-menu-options__btn:hover`| background-color| $hover-danger| #bd1427|
| `.bx--overflow-menu-options__option--danger`                                 | border-top       | $ui-04          | #8897a2 |


| Text           | $text-01    | #152935 |
| Line           | $ui-04      | #8897a2 |

<div data-insert-component="ImageGrid">
  <div>
    ![Overflow menu text hover example](images/overflow-menu-style-1.png)
  </div>
  <div>
    ![Overflow menu warning hover example](images/overflow-menu-style-2.png)
  </div>
</div>
_Text and warning hover examples for Overflow Menu_

## Typography

Overflow Menu text should be set in set in sentence case with the first letter of the first word capitalized.

| Property                         | Font-size (px/rem)| Font-weight  |
|----------------------------------|-------------------|--------------|
| `.bx--overflow-menu-options__btn`| 14 / 0.875        | Normal / 400 |


## Layer

| Class                        | Property    | Layer, Elevation | Box-shadow                      |
|------------------------------|-------------|------------------|---------------------------------|
| `.bx--overflow-menu-options` | box-shadow  | Overlay, 8       | 0 4px 8px 0 rgba(0, 0, 0, 0.1)  |

## Structure

The height of an Overflow Menu is determined by the amount of content in the menu. The Overflow Menu icon can be found in the [iconography](/style/iconography/library) library.

| Class                                       | Property                    | px    | rem   |
|---------------------------------------------|-----------------------------|-------|-------|
| `.bx--overflow-menu-options__option--danger`| border-top                  | 1     | -     |
| `.bx--overflow-menu-options__btn`           | padding-top, padding-bottom | 8     | 0.5   |
| `.bx--overflow-menu-options__btn`           | padding-right, padding-left | 16    | 1     |
| `.bx--overflow-menu__icon`                  | padding                     | 16    | 1     |



| Width    (100%)             | 180                     | 11.25 |
| Height  (100%)             | Varies based on content |       |
---
***
> 
![Structure and spacing measurements for an overflow menu](images/overflow-menu-style-3.png)

_Structure and spacing measurements for Overflow Menu | px / rem_
