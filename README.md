# ES|QL VSCode Extensions pack

This repo houses a number of useful extensions supporting the [Elasticsearch Query Language](https://www.elastic.co/guide/en/elasticsearch/reference/master/esql.html) (ES|QL) development in VS Code. They _can_ be installed independently, but it's recommended to just install the [extension pack](https://marketplace.visualstudio.com/items?itemName=rosshamish.kuskus-extensions-pack) which includes them all.

This is not an official Elastic project is not supported in any official capacity.

These extensions are forked from [kuskus](https://github.com/rosshamish/kuskus), which is a set of extensions for Kusto. These extensions would not be possible without this previous work.


## Extensions

| ES\|QL Extensions pack | All extensions in one pack. [One click to install them all](https://marketplace.visualstudio.com/items?itemName=rosshamish.kuskus-extensions-pack)! |
| :----: | :----: |
| [ES\|QL Syntax Highlighting](https://github.com/smith/esql-extensions-pack/tree/master/esql-syntax-highlighting) | Textmate grammar. Works with most themes. Fork of [josefsin/kusto-syntax-highlighting](https://github.com/josin/kusto-syntax-highlighting). |
| [ES\|QL Language Server](https://github.com/smith/esql-extensions-pack/tree/master/esql-language-server) | Autocomplete<br/>![Autocomplete](https://github.com/rosshamish/kuskus/raw/master/kusto-extensions-pack/readme-content/language-server/completion.gif) <br/> Hover info <br/>![Hover Info](https://github.com/rosshamish/kuskus/raw/master/kusto-extensions-pack/readme-content/language-server/hover-info.gif)<br/> Format Document <br/>![Format Document](https://github.com/rosshamish/kuskus/raw/master/kusto-extensions-pack/readme-content/language-server/format-document.gif)<br/>Supports builtins out of the box. You can also Load Symbols to get intellisense for the tables and functions on your cluster.<br/>![Load Symbols](https://github.com/rosshamish/kuskus/raw/master/kusto-extensions-pack/readme-content/language-server/load-symbols.gif)<br/>Diagnostics are also available, but are not yet fully supported and are disabled by default. Diagnostics are the red squiggly underlines / the items in the Problems tab. |

## Contributors

- Nathan Smith, on github @smith
- Ross Anderson, on github @rosshamish
- Peter Weisbeck, on github @weisbeck
- Bradley Holloway, on github @bradleyholloway
- Josiah Matlack, on github @mosqutip
- Pradeep Vairamani
