psDoc is a Powershell Help Document generator.

### This is a modified version of this script.

This script was originally created by Chase Florell, it can be obtained at [psDoc](https://github.com/ChaseFlorell/psDoc)


----
### Using psDoc ###

To generate documentation off of your module, simply import your module

```powershell
Import-Module MySpecialModule
```

And generate the documentation

```powershell
.\psDoc.ps1 -moduleName MySpecialModule
```

#### Changes

I changed the original -template parameter to a -Style parameter that takes the following input: 

- Confluence
- HTML
- HTML-Types - Add Type definitions to documentation
- Markdown
- Markdown-Types - Add type definition to documentation

### License ###

[Microsoft Public License (Ms-PL)](https://opensource.org/licenses/MS-PL)
