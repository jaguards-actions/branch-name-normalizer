# Branch name normalizer

> [!NOTE]  
> This action is a fork of [Slidem/branch-name-normalizer](https://github.com/Slidem/branch-name-normalizer)

Simple action that normalizez the current branch name into a string with only lowercase alphanumerical values, separated by hiphens.
Example: For the branch name: Alex/A-Simple-pr. Output: `alex-a-simple-pr`

Inputs:

- **branch_name**:
    - default: `$GITHUB_HEAD_REF`
    - required: `false`
- **max_length**:
    - default: `40`
    - required: `false`

Output:

- **normalized**
