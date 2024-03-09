# Contributing

First off, thank you for taking the time to contribute to the Stacks ecosystem ❤️

> [!NOTE]  
> All projects are written using at least one _(or all)_ of the following techologies: _[TypeScript][typescript], [Bun][bun], [Vite][vite], [Vue][vue], and [Tauri][tauri]_

## 💭 Knowledge

### TypeScript

Early on, it's important to note that these projects are written with [TypeScript][typescript]. If you're unfamiliar with it _(or any typed languages)_ then this may feel like a slight roadblock. However, there's never a truly perfect time to start learning it, so ... why not today?

_Don't be discouraged. You will get by learning on-the-fly as you review some of the examples within the codebase. Every project is very approachable (and readable)._

### Get Started

Head over to the [repository][stacks] on GitHub and click the Fork button in the top right corner. After the project has been forked, run the following commands in your terminal:

```bash
gh repo clone stacksjs/stacks
```

_Every project has the same steps to get started:_

```bash
# Check if you have the `./pkgx.yaml` deps installed locally
# otherwise, given `pkgx` is installed, run
dev

# next, install `./node_modules`
bun install


# now, that you are set up you may run any of the following
bun dev
bun build
bun test
```

_Check out each project's `./package.json` and you will find a few more handy scripts._

### Testing

All of the tests are stored within the `./tests` project folder. 

When adding or updating functionality, please ensure it is covered through the test suite. Ensure so by running `bun test`_, or `buddy test` within Stacks contexts._

### Commit

We use [semantic commit messages][semantic-commit-style] to automate package releases. No worries, you may not be aware what this is or how it works just—the CLI will guide you. The commit process was automated to some degree, simply run `bun run commit` in your terminal and follow the instructions.

For example,

```bash
# Add all changes to staging to be committed.
git add .

# Commit changes
bun run commit
buddy commit # inside Stacks context

# Push changes up to GitHub
git push
```

_By following these minor steps, Stacks is able to automatically release new versions & generate relating local & remote changelogs._

### Pull Request

When you're all done, head over to the [repository][stacks], and click the big green `Compare & Pull Request` button that should appear after you've pushed changes to your fork.

Don't expect your PR to be accepted immediately or even accepted at all. Give the community time to vet it and see if it should be merged. Please don't be disheartened if it's not accepted. Your contribution is appreciated more than you can imagine, and even an unmerged PR can teach us a lot ❤️

**Working on your first Pull Request?** You can learn how from this free series [How to Contribute to an Open Source Project on GitHub][pr-beginner-series].

[typescript]: https://www.typescriptlang.org
[vue]: https://vuejs.org/
[vite]: https://vitejs.dev/
[tauri]: https://tauri.app/
[bun]: https://bun.sh/
[stacks]: https://github.com/stacksjs/stacks
[semantic-commit-style]: https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716
[pr-beginner-series]: https://app.egghead.io/courses/how-to-contribute-to-an-open-source-project-on-github
