# howar31.github.io

Account-level GitHub Pages site for `lab.howar31.com`. A container root: it
hosts unrelated themed items at sub-paths, monorepo-style. This repo holds only
the root page.

## Root page

`index.html` is a redirect stub: it sends visitors to `howar31.com`
(client-side — `location.replace` plus a `<meta refresh>` no-JS fallback). It
is not a landing page and reveals nothing about the items hosted under the
domain.

## Twin copy

`index.html` is byte-identical to `index.html` in the `howar31/share` repo
(served at `lab.howar31.com/share/`). Both are the same redirect stub; keep
them byte-identical.
