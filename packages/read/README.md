# @changesets/read

[![npm package](https://img.shields.io/npm/v/@changesets/read)](https://npmjs.com/package/@changesets/read)
[![View changelog](https://img.shields.io/badge/Explore%20Changelog-brightgreen)](./CHANGELOG.md)

Read in all changesets from a repository.

```js
import readChangesets from "@changesets/read";

let changesets = await readChangesets(cwd);
```

This returns an array of formatted changesets.
