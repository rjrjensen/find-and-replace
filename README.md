# Find and Replace Snippets

## .NET

### Update PackageReferences to self-closing tags
| Step | Find | Replace |
| ---- | ---- | ------- |
| 1 | `>\r\s*<Version>` | ` Version="` |
| 2 | `</Version>\r\s.*` | `" />` |
