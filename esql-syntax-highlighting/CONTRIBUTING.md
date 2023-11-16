# Contributing

## Developing

### First Run

1. `npm install` - Install all dependencies
2. Launch `Extension` configuration (hit F5)

### Inner Loop

1. Make edits to syntaxes/esql.tmLanguage.json
2. Launch the `Extension` configuration (hit F5)

### Relevant Documentation/Useful Links

- [VSCode: Syntax Highlight Guide](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide)
- [Textmate Manual: Language Grammars](https://macromates.com/manual/en/language_grammars)
- [Writing a TextMate Grammar: Some Lessons Learned](https://www.apeth.com/nonblog/stories/textmatebundle.html)
- A regex debugging tool like [regex101.com](https://regex101.com/). Should support Oniguruma or PCRE2 regular expressions

## Testing

Isolated testing of the grammar is available with snapshot tests, via [PanAeon/vscode-tmgrammar-test](https://github.com/PanAeon/vscode-tmgrammar-test). Read more [here](https://github.com/PanAeon/vscode-tmgrammar-test#snapshot-tests).

- Run snapshot tests: `npm run test`.
- Update snapshots: `npm run test:update-snapshots`

Manually-taken visual snapshots of how the syntax highlighting looks with certain themes are in `test/snapshots/**/theme-visuals`. Filenames indicate the test file and theme used.

- Monokai
- Dark+ (default dark)
- Light+ (default light)
- [Base16 Default Dark](https://marketplace.visualstudio.com/items?itemName=golf1052.base16-generator)

Please update the visual snapshots when making tmLanguage changes. To take new snapshots, run the "All (Extension Pack)" target (see root `launch.json`), enable a particular Theme, and use the [CodeSnap extension](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap) to take the screenshot.


