# Setvars

This action sets environment variables for your GitHub workflow.

## Usage

```yml
- name: Configure Environment Variables
  uses: .github/actions/setvars
  with:
    varFilePath: ./drop/.github/variables/*
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)

# Contributions

Contributions are welcome! See the [Contributor's Guide](CONTRIBUTING).