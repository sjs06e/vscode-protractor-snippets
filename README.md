# Visual Studio Code Snippets for Protractor
Protractor snippets for Javascript and Typescript

![vscode protractor](https://raw.githubusercontent.com/deerawan/vscode-protractor-snippets/master/images/protractor.gif)

## Installation
Type `cmd-shift-p`/`ctrl-shift-p` to launch command palette and choose `Extensions: Install Extension`. Search this package and install.

## Snippets
Below is a list of all snippets and the triggers.

*The ⇥ means the TAB key.*

### Browser
| Trigger     | Description |
| -------     | ----------- |
| `bg→`       | browser.get |
| `bp→`       | browser.pause |
| `bgcurl→`   | browser.getCurrentUrl |
| `bsl→`      | browser.setLocation |
| `bw→`       | browser.wait |
| `bwa→`      | browser.waitForAngular |
| `bamock→`   | browser.addMockModule |
| `bcmock→`   | browser.clearMockModule |

### Element Locators
| Trigger     | Description |
| -------     | ----------- |
| `ebbin→`    | element by.binding |
| `eabin→`    | element.all by.binding |
| `ebxbin→`   | element by.exactBinding |
| `eaxbin→`   | element.all by.exactBinding |
| `ebmod→`    | element by.model |
| `eamod→`    | element.all by.model |
| `ebbtn→`    | element by.buttonText |
| `eabtn→`    | element.all by.buttonText |
| `ebpbtn→`   | element by.partialButtonText |
| `eapbtn→`   | element.all by.partialButtonText |
| `ebrep→`    | element by.repeater |
| `earep→`    | element.all by.repeater |
| `ebxrep→`   | element by.exactRepeater |
| `eaxrep→`   | element.all by.exactRepeater |
| `ebcsstxt→` | element by.cssContainingText |
| `eacsstxt→` | element.all by.cssContainingText |
| `ebopt→`    | element by.option |
| `eaopt→`    | element.all by.option |
| `ebdcss→`   | element by.deepCss |
| `eadcss→`   | element.all by.deepCss |
| `ebclass→`  | element by.class |
| `eaclass→`  | element.all by.class |
| `ebcss→`    | element by.css |
| `eacss→`    | element.all by.css |
| `ebid→`     | element by.id |
| `eaid→`     | element.all by.id |
| `eblink→`   | element by.linkText |
| `ealink→`   | element.all by.linkText |
| `ebplink→`  | element by.partialLinkText |
| `eaplink→`  | element.all by.partialLinkText |
| `ebjs→`     | element by.js |
| `eajs→`     | element.all by.js |
| `ebname→`   | element by.name |
| `eaname→`   | element.all by.name |
| `ebtag→`    | element by.tagName |
| `eatag→`    | element.all by.tagName |
| `ebxp→`     | element by.xpath |
| `eaxp→`     | element.all by.xpath |

### Element Locators
| Trigger     | Description |
| -------     | ----------- |
| `eclr`      | element.clear |
| `eclk`      | element.click |
| `ega`       | element.getAttribute |
| `egt`       | element.getText |
| `esk`       | element.sendKeys |

### Page Object
| Trigger     | Description |
| -------     | ----------- |
| `poset→`    | function to set element using sendKeys() |
| `poget→`    | function to get element using getText() |
| `pogetval→` | function to get element using getAttribute('val') |
| `poclick→`  | function to click element using click() |

## License
[MIT License](http://opensource.org/licenses/MIT)