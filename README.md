Hello world app on Pivotal Web Services deployed entirely from command line.

```cf push```

Changes made
- Changed index.html
- Changed manifest.yml - increased memory

Challenges faced
- Encountered error during first `cf push`. Kept getting router path is not available.
- Encountered error with app name. Kept getting app name is invalid. Changed it to `cf-sai-spring`. This also fixed the above error but do not think it is related.
- Wish it was integrated with git workflow

