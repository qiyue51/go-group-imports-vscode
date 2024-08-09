> # go-group-imports
> 
> VSCode extension for separating imports in Go files into three (or four depending on the settings) groups:
> 
> 1. Standard library imports,
> 2. Third party imports,
> 3. (OPTIONAL) Organization imports (when is configured in settings),
> 4. Own (belonging to the modue) imports.
> 
> ## Extension Settings
> 
> - `groupImports.onSave`: automatically group imports on save. Default value is `true`.
> - `groupImports.includeOrgGroup`: handle imports from the organization into a separate group. Default value is `undefined`.

# forked changes
support workspace, module mode can be used even if the project is under GOPATH, fix some save issue
