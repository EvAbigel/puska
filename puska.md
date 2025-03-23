# HTMLElement
## Instance properties
- innerHTML | string
- innerText | string
- classList | DOMTokenList
- id | string
- type |string
- for | string
- children | HTMLCollection
- parentElement | HTMLElement

## Instance methods
- querySelector(string) | Element
- querySelectorAll(string) | NodeList
- addEventListener(string, callback(EventTarget)) | void
- callback(EventTarget) | void
- createElement(string) | Element
- appendChild(Node) | void

# Document
## Instance properties
- body | HTMLBodyElement
- table | HTMLTableElement
- tableheader | HTMLTableSectionElement
- tablebody | HTMLTableSectionElement
- th | HTMLTableCellElement
- tr | HTMLTableRowElement
- td | HTMLTableCellElement

- createElement(string) | Element
- getElementById(string) | Element

- URL | string


# HTMLBodyElement
- appendChild(Node) | void
- parentElement(Node)
- getElementById(string) | Element

# DOM TableData
- colSpan
- rowSpan

# FileReader

## Instance properties
- result | string

## Instance methods
- readAsText(file) | void

# Callback functions

## Used in event listeners
- (EventTarget) => void