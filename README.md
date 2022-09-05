To repro, install deps with `pnpm install`, I used node 18 but the bug also appears with node 16.
Then try to build with `pnpm run build`.

The problem disappears if the `background` prop on the image component is removed.