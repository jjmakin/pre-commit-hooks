# pre-commit-hooks
Simple system checks to use with pre-commit
Example usage in your own .pre-commit-config.yaml
```
-   repo: https://github.com/jjmakin/pre-commit-hooks
    rev: 'v1.0.0'
    hooks:
    -   id: rpmlint
    -   id: cookstyle
```
