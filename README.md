# AlphaZero



An experimental reimplementation of [AlphaZero](https://en.wikipedia.org/wiki/AlphaZero). Meant as a proof of concept for decision aid systems.

This project uses the [NBDev](https://github.com/fastai/nbdev/tree/master/) development library.

Before contributing changes, run the following to remove excess cell metadata:

```
nbdev_install_git_hooks
nbdev_clean_nbs
```


To preview changes to documentation locally run:

```
nbdev_build_lib
nbdev_build_docs
make docs_serve
```

If you encounter a Jekyll error when building the documentation site, and see 'webrick' mentioned in the log, move to the `docs/` folder and run: `bundle add webrick`.

 
