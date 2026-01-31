## quick start
- `pnpm install`
- `pnpm build`
- `pnpm ui:build`
- `pnpm openclaw onboard --install-daemon`
- run daemon `pnpm openclaw gateway --port 18789 --verbose`
- test discord link `pnpm openclaw message send --target 1244462508966805584 --message "Hello from qAI"`

## telegram
- `pnpm openclaw configure --section channels` then setup telegram
- `pnpm openclaw pairing approve telegram [pairing code in tg]`

## security
- `openclaw security audit --deep`