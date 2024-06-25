# Reproduce

## Issue #1: Missing unknown symbol in preview

`$ pnpm i`

`$ pnpm preview`

See 404 error in the browser for file `/build/q-Bq36Wx9q.js`. This only exists when using the Link component.

## Issue #2: Missing symbols when hovering in dev

`$ pnpm i`

`$ pnpm start`

Hover over the `page` link and you'll see a few 404 errors.
