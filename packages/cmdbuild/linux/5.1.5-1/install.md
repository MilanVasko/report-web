# Report for 'install lua 5.1.5-1 cmdbuild'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving

- **Error:** Error getting dependency of "cmdbuild 0.1.0-1": Error getting dependency of "luaxml 101012-2": Package lua = 5.1 needed, but selected at version 5.1.5-1.
- Trying to force usage of 'lua 5.3.2-1' to solve dependency resolving issues
- **Error:** Package lua 5.1.5-1 needed, but installed at version 5.3.2-1.
- Trying to force usage of 'lua 5.2.4-1' to solve dependency resolving issues
- **Error:** Package lua 5.1.5-1 needed, but installed at version 5.2.4-1.
- Trying to force usage of 'lua 5.1.5-1' to solve dependency resolving issues
- **Error:** Error getting dependency of "cmdbuild 0.1.0-1": Error getting dependency of "luaxml 101012-2": Package lua = 5.1 needed, but installed at version 5.1.5-1.
