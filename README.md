# discover-npm-packages

Discover new `npm` packages based on 1+ other packages provided.

This tool crawls npm + GitHub and gives you an output of the packages + readme preview sorted by downloads.

It's useful to find out which dependencies your packages are using, or just find out about neat things to try!

Built with [Civet](https://civet.dev) & [Bun](https://bun.sh).

> **Warning**
> Make sure you setup your environment variables from `.env.example` before running the command!

To install (🏗️ Not published yet! 🏗️):

```bash
# with npm
npm i -g @jliocsar/discover-npm-packages

# with Bun
bun i -g @jliocsar/discover-npm-packages
```

To install dependencies:

```bash
bun install
```

To run:

```bash
# use -c to define how deep it'll crawl
bun run start <...packages> -c 2
```

This project was created using `bun init` in bun v1.0.3.
