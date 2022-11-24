# ESbuild Demo

## Install and build

```bash
pnpm i
pnpm build
```

## List dependencies

### Of file built with esbuild

Should report no dependencies.

```bash
pnpm trace
```

### Of original file

Should report md5 as a dependency.

```bash
pnpm trace-original
```