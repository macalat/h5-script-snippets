# H5 Script Snippets

This is a collection of snippets for Infor's **H5 Scripting language** that I personally use.
![](https://raw.githubusercontent.com/macalat/h5-script-snippets/master/images/h5-script-snippets.gif)

## Usage

Type part of a snippet, press `enter`, and the snippet unfolds.

Alternatively, press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (macOS) to activate snippets from within the editor.

Press `Tab` to cycle through variables.

## Snippets

| Snippet                       | Purpose                                                                           |
| ----------------------------- | --------------------------------------------------------------------------------- |
| `h5start`                     | Creates a boilerplate with subscription on lifecycle events                       |
| `h5start-translate`           | Creates a boilerplate with translation setup and subscription of lifecycle events |
| `h5start-no-LCH`              | Creates a boilerplate without events subscription                                 |
| `h5start-no-LCH-translate`    | Creates a boilerplate with translation and without events subscription            |
| `h5MI`                        | Async method for an MI Request                                                    |
| `H5ExportMI`                  | Async method for an EXPORTMI transaction                                          |
| `h5addbutton`                 | Factory method for creating a button                                              |
| `h5addlabel`                  | Factory method for creating a label                                               |
| `h5addtextbox`                | Factory method for creating a textbox                                             |
| `h5addelement`                | Factory method for creating Label or Textbox                                      |
| `h5addcombobox`               | Factory method for creating a combobox                                            |
| `h5getfieldvalue`             | ScriptUtil's GetFieldValue                                                        |
| `h5setfieldvalue`             | ScriptUtil's SetFieldValue                                                        |
| `h5customdialog`              | Simple custom dialog boilerplate                                                  |
| `h5busyindicator`             | Method fo handling busyindicator                                                  |
| `h5singlebutton`              | Old way of creating single button (use for quick testing)                         |
| `h5addsingletextbox`          | Old way of creating single textbox (use for quick testing)                        |
| `h5addsinglecombobox`         | Old way of creating single combobox (use for quick testing)                       |

---

## Change Log

## 1.2.0
- Revert back attaching and detaching of events since H5 change how H5 scripts are loaded

## 1.1.0
- Changed attaching and detaching of events on simpler approach
- Renamed connect and disconnect to attachEvents and detachEvents respectively

## 1.0.5
- Cleanup busyindicator snippet

### 1.0.3
- Fixed license and change logs

### 1.0.2
- Fix wrong snippets for `h5getfieldvalue` and `h5MI`

### 1.0.1
- Update repository link

### 1.0.0
- Initial release

---

## For more information

* [macalat.wordpress.com](https://macalat.wordpress.com/)
* [Contact](mailto:macalat99@gmail.com?subject=H5%20Script%20Snippet)

