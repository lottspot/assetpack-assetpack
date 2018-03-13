An asset pack for... scaffolding new asset packs.

## Synopsis

```
$ make
zip -r assetpack.zip data meta
  adding: data/ (stored 0%)
  adding: data/Makefile (deflated 18%)
  adding: data/gitignore (stored 0%)
  adding: meta/ (stored 0%)
  adding: meta/gitignore.json (deflated 8%)
  adding: meta/Makefile.json (stored 0%)
$ mv assetpack.zip $HOME/.mkproject/assets/assetpack.zip
$ cd $HOME
$ mkproject -t assetpack my-project-type
assetpack-my-project-type
+ Makefile
+ .gitignore
```
