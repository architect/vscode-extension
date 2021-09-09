# Architect for VS Code

<p align=center><img src="https://github.com/architect/vscode-extension/raw/main/assets/architect-logo-black-white-outline-transparent.png?raw=true" width=500></p>

Full support for all standard OpenJS Architect file format values, including:

- Pragmas
- Scalar values: (`string`, `number`, `boolean`)
- Complex values: (`array`, `vector`, `map`)
- Comments (of course)

Automatically detects common Architect files, including:

- `app.arc` + `.arc` - primary project manifests)
- `prefs.arc` + `preferences.arc` - local Sandbox preferences, including env vars
- `config.arc` + `.arc-config` - function configs

[Learn more about the Architect format here](https://arc.codes/docs/en/guides/get-started/project-layout)
