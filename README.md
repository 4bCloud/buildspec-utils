# buildspec-utils
This script get some information to use in your Codebuild


## How to use:

Inside your buildspec.yml, use like this:
```
install:
    commands:
      - curl -fsSL https://raw.githubusercontent.com/4bCloud/buildspec-utils/main/buildspec-extras.sh >> extras.sh
      - . ./extras.sh
```
