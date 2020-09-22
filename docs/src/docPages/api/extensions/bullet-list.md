# BulletList
This extension enables you to use bullet lists in the editor. They are rendered as `<ul>` HTML tags,

Type `* ​`, `- ​` or `+ ​` at the beginning of a new line and it will magically transform to a bullet list.

::: warning Use with ListItem
The `BulletList` extension is intended to be used with the [`ListItem`](/api/extensions/list-item) extension. Make sure to import that one too, otherwise you’ll get a SyntaxError.
:::

## Options
| Option | Type   | Default | Description                                  |
| ------ | ------ | ------- | -------------------------------------------- |
| class  | string | –       | Add a custom class to the rendered HTML tag. |

## Commands
| Command     | Options | Description           |
| ----------- | ------- | --------------------- |
| bullet_list | —       | Toggle a bullet list. |

## Keyboard shortcuts
* `Control` + `Shift` + `8`

## Source code
[packages/extension-bullet-list/](https://github.com/ueberdosis/tiptap-next/blob/main/packages/extension-bullet-list/)

## Usage
<demo name="Extensions/BulletList" highlight="3-5,17-18,37-38" />