# uppm-package-repository-macos10.15-x86_64

these packages are created by [ppkg](https://github.com/leleliu008/ppkg).

these packages have no dependencies other than `/usr/lib/lib*.dylib` and `/System/Library/Frameworks/*.framework`.

these packages are relocatable which means that you can install them to anywhere.

## Environment Variables
following environment variables should be set for `git`:
```bash
export GIT_EXEC_PATH="$PPKG_CORE_INSTALL_DIR/libexec/git-core"
export GIT_TEMPLATE_DIR="$PPKG_CORE_INSTALL_DIR/share/git-core/templates"
```

following environment variables should be set for `file`:
```bash
export MAGIC="$PPKG_CORE_INSTALL_DIR/share/misc/magic.mgc"
```

