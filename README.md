# Setvars

This action sets environment variables for your GitHub workflow from variables in an environment variable (.env) file or from a directory containing multiple environment variable files. 

## Usage

### Single environment variable file
```yml
- name: Configure Environment Variables
  uses: tw3lveparsecs/github-actions-setvars@v0.1
  with:
    varFilePath: ./drop/.github/variables/vars.env
```

### Directory containing multiple environment variable files
```yml
- name: Configure Environment Variables
  uses: tw3lveparsecs/github-actions-setvars@v0.1
  with:
    varFilePath: ./drop/.github/variables/*
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)

# Contributions

Contributions are welcome! See the [Contributor's Guide](CONTRIBUTING).