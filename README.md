## init

```bash
git clone https://github.com/dwelle/joi-browser.git && \
cd joi-browser &&\
git remote add upstream https://github.com/jeffbski/joi-browser.git
```

## building

1. `git pull --rebase upstream/master`
2. update `package.json` joi dependenacy to latest commit in [dwelle/joi](https://github.com/dwelle/joi)
3. run `npm i`
4. `git commit -a --amend && git push -f`

## manual rebuild (for whatever reason)

```bash
npm run prepublish
```
