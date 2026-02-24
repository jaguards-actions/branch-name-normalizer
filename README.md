# Branch name normalizer

> [!NOTE]  
> This action is a fork of [Slidem/branch-name-normalizer](https://github.com/Slidem/branch-name-normalizer)

Simple action that normalize the current branch name into a string with only lowercase alphanumerical values, separated by hyphens.
This will comply RFC1123 standard https://tools.ietf.org/html/rfc1123 to publish the branch name to a subdomain, for example.
Example: For the branch name: `copilot/test-pr`. Output: `copilot-test-pr`

Inputs:

- **branch_name**:
    - default: `$GITHUB_HEAD_REF`
    - required: `false`
- **max_length**:
    - default: `63`
    - required: `false`

Output:

- **normalized**
