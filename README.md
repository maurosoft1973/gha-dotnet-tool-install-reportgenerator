# Install .NET Tool - Report Generator

Install the latest version of [Report Generator](https://www.nuget.org/packages/dotnet-reportgenerator-globaltool) using `dotnet tool`.

## Usage

To use this action in your GitHub repository, you can follow these steps:

```yaml
uses: maurosoft1973/dotnet-tool-install-reportgenerator@v1
```

### Inputs

```yaml
with:
  # The version of Report Generator to install.
  version: 5.4.1
```

### Outputs

This action has no outputs.

## Examples

### Install Reportgenerator using `dotnet tool`

```yaml
steps:
  - name: Install Report Generator
    uses: maurosoft1973/dotnet-tool-install-reportgenerator@v1
```

## Contributing to Install .NET Tool - Report Generator

Contributions are welcome! 
Feel free to submit issues, feature requests, or pull requests to help improve this action.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
