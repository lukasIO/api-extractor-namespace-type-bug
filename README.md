# Bug reproduction

1. `pnpm install`
2. `pnpm --filter=foo build` - works
3. `pnpm --filter=foo api:update` - works
4. `pnpm --filter=bar build` - works
5. `pnpm --filter=bar api:update` - breaks
