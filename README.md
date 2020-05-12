[![npm version](https://badge.fury.io/js/base-es6-template.svg)](https://badge.fury.io/js/base-es6-template)
[![npm downloads](https://img.shields.io/npm/dt/base-es6-template.svg?style=flat)](https://www.npmjs.com/package/base-es6-template)

### Installation
```bash
Click on green button "Use this template".
```

### Flow Capabilities
```yaml
- Before commit:
- Check code and autofix common errors.  (npm run precommit)
- Check commit comment using git hooks using husky.

- Post commit:
- Changelog automation uging standard-version tool. (npm run release:minor)


- Unpublish npm module. (npm run unpublish)
```

### Fix
```bash
git add .
npm run precommit
git commit -m 'fix: some fix file'
npm run release:patch
```

### Minor change
```bash
git add .
npm run precommit
git commit -m 'feat: some change'
npm run release:minor
```

### Major change
```bash
git add .
npm run precommit
git commit -m 'feat: large changes '
npm run release:major
```
