# haxe-example

To reproduce, simply run

```bash
npm i
```

I see the following error:

```bash
npm ERR! code EBADPLATFORM
npm ERR! notsup Unsupported platform for haxe@5.2.1: wanted {"os":"win32,win64,darwin,linux","arch":"x64,ia32"} (current: {"os":"darwin","arch":"arm64"})
npm ERR! notsup Valid OS:    win32,win64,darwin,linux
npm ERR! notsup Valid Arch:  x64,ia32
npm ERR! notsup Actual OS:   darwin
npm ERR! notsup Actual Arch: arm64

npm ERR! A complete log of this run can be found in:
npm ERR!     /Users/alexey.berezin/.npm/_logs/2023-03-01T12_33_41_606Z-debug.log
```

Complete log is available in [2023-03-01T12_33_41_606Z-debug.log](./2023-03-01T12_33_41_606Z-debug.log)

## Additional information

- Laptop – Macbook Pro Apple M1 Pro
- MacOS – Ventura 13.1 (22C65)
- Node – v14.20.0
- NPM – 6.14.17
