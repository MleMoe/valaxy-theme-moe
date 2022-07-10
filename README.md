<p align="center">
Valaxy-Theme-Moe<sup><em>(vue)</em></sup>
</p>

> This is a [valaxy](https://github.com/YunYouJun/valaxy) theme just for fun and a promise.

## Usage

### Clone to local

> Use [pnpm](https://pnpm.io/), because we need its workspace.

```bash
git clone git@github.com:MleMoe/valaxy-theme-moe.git
cd valaxy-theme-moe
# If you don't have pnpm installed, run: npm install -g pnpm
pnpm i
```

### Development

```bash
# dev node
pnpm dev
# dev client
pnpm demo
```

### Build

```bash
pnpm build
```

### Release

> Publish to [npm](https://www.npmjs.com/).

#### Manual

```bash
pnpm ci:publish
```

#### Auto by GitHub Actions

> You can release it by github actions.

Click `Settings` -> `Secrets` -> `Actions` in your GitHub repo.

Add `New repository secret`:

- `NPM_TOKEN`: `your npm token` (Generate from your npm `Access Tokens` - `Automation`)

```bash
npm run release
# choose your version to automatic release
```

## Checklist

- [ ] Change the author name in `LICENSE` & `package.json` & `.github`
- [ ] Write `ThemeConfig` & Other init content
- [ ] Rename `valaxy-theme-starter` to `valaxy-theme-<name>` (custom it)
- [ ] Change `theme: 'starter'` to `theme: <name>` in `valaxy.config.ts`
- [ ] Each of your Vue components should have a namespace
  - For example: `YunTest.vue` for `valaxy-theme-yun`

Let's write the theme & docs!

## Thanks

Thanks to xiao yun
