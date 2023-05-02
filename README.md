# Set Variables

GitHub action that sets environment variables for your GitHub workflow.

## Usage

The action has a required input called `envFilePath`. This sets the path to the file or directory containing the environment variables to set for the GitHub workflow.

### Single environment variable file

```yml
- name: Set Environment Variables
  uses: tw3lveparsecs/github-actions-set-variables@latest
  with:
    envFilePath: ./drop/.github/variables/vars.env
```

### Directory containing multiple environment variable files

```yml
- name: Set Environment Variables
  uses: tw3lveparsecs/github-actions-set-variables@latest
  with:
    envFilePath: ./drop/.github/variables/*
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)

# Contributions

Contributions are welcome! See the [Contributor's Guide](CONTRIBUTING).
