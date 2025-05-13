# GitHub Action For Git Checkout

This action checks-out your repository and if necessary extracts the content of the working-directory to the root folder.

# Usage

```yaml
- name: Git checkout
  uses: vaimo/action-git-checkout@v1
  with:
    # Directory name that will be extracted. 
    # Optional - if not specified then uses the root directory. 
    working-directory: ${{inputs.working-directory}}
```
