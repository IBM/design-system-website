## Color

| Class                        | Property   |SCSS       | HEX     |
|------------------------------|------------|-----------|---------|
| `.bx--label`                 | color      | $text-01   | #152934 |
| `.bx--label-description`     | color      | $text-02   | #5a6872 |
| `.bx--file-filename`         | color      | $text-01   | #152934 |
| `.bx--file__selected-file`   | background | $ui-01     | #ffffff |
| `.bx--file-close`            | fill       | $inverse-01| #152934 |


## Typography

The File Uploader label and instruction text should be set in sentence case, with only the first letter of the first word in the sentence capitalized.

| Class                  | Font-size (px/rem) | Font-weight     | Type style |
|------------------------|--------------------|-----------------|------------|
|`.bx--label`            | 14 / 0.875         | Semi-Bold / 600 | Zeta       |
|`.bx--label-description`| 14 / 0.875         | Normal / 400    | -          |
|`.bx--file-filename`    | 12 / 0.75          | Normal / 400    | -          |

## Structure

The width of an uploaded file varies based on the content and layout of a design. Refer to the [Button](/components/button) guidelines for styling and usage of the “Add files” button.

| Class                | Property           | px  | rem   |
|----------------------|--------------------|-----|-------|
| `.bx--file-filename` | height             | 30  | 1.875 |
| `.bx--file-close`    | height, width      | 16  | 1     |
| `.bx--file-container`| margin-top         | 24  | 1.5   |

---
***
> 
![Structure and spacing measurements for File Uploader](images/file-uploader-style-1.png)

_Structure and spacing measurements for File Uploader | px / rem_

### Recommended

The following specs are not built into the File Uploader component but are recommended by design as the proper amount between File Uploader elements.

| Class                  | Property                  | px  | rem   |
|------------------------|---------------------------|-----|-------|
| `.bx--file-close`      | margin-left, margin-right | 16  | 1     |
