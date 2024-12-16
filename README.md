# Reproduction SvelteKit - No CSR - `inert` attribute

See https://github.com/sveltejs/kit/issues/13170

## Steps

1. Clone this repository
2. Install dependencies `pnpm install`
3. Start the dev server `pnpm dev`
4. Inspect the `button` element in server-side-rendered root page

Expected: h1 should not have attribute `insert`
Actual: h1 has `insert="false"`

