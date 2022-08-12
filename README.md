<p align="center">
    <img width="128" alt="preview" src="https://user-images.githubusercontent.com/964077/179586355-6d90c66a-6812-4ab7-9657-4596dd1b2a62.png">
</p>
<br />

## Inline Fold - VSCode Extension
⚠️ NOTICE: this extension is still under active development! ⚠️

## VS Code Inline Fold Extension

VS Code Inline Fold extension mimics VS Code's [folding](https://code.visualstudio.com/docs/editor/codebasics#_folding) experience for inline code.
This is especially useful when working with frameworks like Tailwind CSS which use lots of utility classes that often disfigure code visual structure. You can expand the folds by clicking on them. You can also configure the extension to target specific attributes in your markup.
The characters used as a mask can be configured in the settings and you can update the regex expression to match any code pattern you want.
The extension also enables folding of attribute values within HTML/JSX tags. It makes your code tidy and easier to navigate.

<br />

<p align="center">
    <img width="650" alt="preview" src="https://user-images.githubusercontent.com/964077/179401349-4b217316-3099-47d0-a8b0-10fb2381d105.png">
</p>

### Available Settings
- `inlineFold.regex` regex to match the code line
- `inlineFold.regexFlags` regex flags
- `inlineFold.regexGroup` regex group that match the code that should be folded
- `inlineFold.unfoldedOpacity` opacity of the unfolded code when it's clicked or is selected
- `inlineFold.maskChar` text/character to mask the code when it is folded
- `inlineFold.maskColor` color of the mask character(s)
- `inlineFold.after` an optional text/character that will be appended to the end of folded code
- `inlineFold.supportedLanguages` a list of targeted language Ids
- `inlineFold.unfoldOnLineSelect` disabled by default, if enabled fold/unfold will be toggled by selecting anywhere of the line

If the extension doesn't work for your language out of the box, you can add it from the settings under `inlineFold.supportedLanguages` using the specific language Id.

Examples:
- `vue`
- `html`
- `svelte`
- `vue-html`
- `javascript`
- `typescript`
- `javascriptreact`
- `typescriptreact`

*Check here for <a href="https://code.visualstudio.com/docs/languages/identifiers#_known-language-identifiers">more options</a>*

### Running the extension
You can install the extension <a href="https://marketplace.visualstudio.com/items?itemName=moalamri.inline-fold"> in the marketplace here</a>. If you encounter any issue or would like to contribute, <a href="https://github.com/moalamri/vscode-inline-fold">visit the GitHub page</a>.

### Notes
Use settings UI to configure the extension (better for regex escaping).

### Changelog
See the project's <a href="CHANGELOG.md"> changelog</a> here.

### Contributors
<a href="https://github.com/moalamri/vscode-inline-fold/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=moalamri/vscode-inline-fold" />
</a>

Screenshot by [Cody](https://github.com/ccccooooddddyyyy)
