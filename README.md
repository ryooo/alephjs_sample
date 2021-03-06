![Aleph.js](https://raw.githubusercontent.com/alephjs/aleph.js/master/design/poster.svg)

# Alephjs.org
The website of **Aleph.js**, this website is built with Aleph.js and automatically deploys to [Vercel](https://vercel.com).

> https://alephjs.org

## System Requirements
- [Deno](https://deno.land/) 1.8.3
- [Aleph.js](https://deno.land/x/aleph) 0.3.0-alpha.30
- [VS Code](https://code.visualstudio.com/) with [deno extension](https://marketplace.visualstudio.com/items?itemName=denoland.vscode-deno) (recommended)

## Development Setup
```bash
# start the website in `development` mode
aleph dev

# start the website in `production` mode
aleph start

# build the website to a stact site
aleph build
```

curl -fsSL https://deno.land/x/install/install.sh | sh -s v1.8.3 && /vercel/.deno/bin/deno run -A https://deno.land/x/aleph@v0.3.0-alpha.30/cli.ts build