# @embroider/core

## 3.0.0

### Major Changes

- 8c179845: [#1363](https://github.com/embroider-build/embroider/pull/1363) : Simplified template resolution : _by [@ef4](https://github.com/ef4)_
- 8c179845: [#1339](https://github.com/embroider-build/embroider/pull/1339) : Layer template resolver on top of module resolver : _by [@ef4](https://github.com/ef4)_
- 8c179845: [#1331](https://github.com/embroider-build/embroider/pull/1331) : Move resolving into dedicated plugins : _by [@ef4](https://github.com/ef4)_

### Minor Changes

- 8c179845: [#1376](https://github.com/embroider-build/embroider/pull/1376) : legacy addon resolving : _by [@ef4](https://github.com/ef4)_

  This adds the ability to intercept module resolution requests to and from addons that have been rewritten from v1 to v2.

  It's what will allow resolving modules without needing to physically rewrite the node_modules tree.

- 8c179845: [#1355](https://github.com/embroider-build/embroider/pull/1355) : Refactor self-resolution : _by [@ef4](https://github.com/ef4)_
- 66de9820: [#1354](https://github.com/embroider-build/embroider/pull/1354) : Add glint helper types for more macros : _by [@vlascik](https://github.com/vlascik)_
- 8c179845: [#1373](https://github.com/embroider-build/embroider/pull/1373) : app tree resolving : _by [@ef4](https://github.com/ef4)_

### Patch Changes

- 8c179845: [#1346](https://github.com/embroider-build/embroider/pull/1346) : Bugfix: inconsistent handling of webpack virtual modules : _by [@ef4](https://github.com/ef4)_
- Updated dependencies [66de9820]
- Updated dependencies [8c179845]
- Updated dependencies [8c179845]
- Updated dependencies [8c179845]
- Updated dependencies [8c179845]
  - @embroider/macros@1.11.0
  - @embroider/shared-internals@3.0.0
