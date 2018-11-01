# DCG Repo Checklist

1. DCG Standard README.md. Follows the [standard-readme spec](https://github.com/RichardLitt/standard-readme/blob/master/spec.md):
2. Build badges - pass / fail (at the least, could be others)
3. Ensure tests exist and pass before allowed to merge in
4. GitHub settings, all `master` (and `develop` if applicable) should be
   protected w/these rules:  
  a. required for tests to pass  
  b. peer review required for merge  
  c. reviews dismissed when new commits are pushed  
5. LICENSE:
  - must be named 'LICENSE' exactly (no extension)
  - must be MIT License (unless special dispensation granted by management and written agreement exists)

### Possible:

- Code coverage metrics (badge which determines % coverage)
- Minimum code coverage thresholds defined (could be variable per repo based on situation)
- For applicable repos: automated Docker builds which push to a registry
