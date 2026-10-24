    # SigmaOS-fish

    Fish config & plugins

    Part of the **SigmaOS** sovereign operating-system ecosystem — a multi-repository
    distribution modelled on Linux Mint and Omarchy Linux. See the parent
    [`SigmaOS`](https://github.com/AaryanSinghChauhan09/SigmaOS) repository for the
    full component index.

    ## Upstream inspirations
    - https://github.com/omacom/omarchy-fish

    ## Design principles applied
    - **Separation of Concerns**
- **Defensive Programming**
- **Fail-Fast**
- **DRY**
- **KISS**
- **Deterministic Testing**

    ## Usage
    Verbs: `generate, plugins, aliases, apply-plan`

    ```
    $ sigma-shell plugins plugins.txt
zsh-autosuggestions
zsh-syntax-highlighting
$ sigma-shell aliases aliases.txt
gs = git status
$ sigma-shell generate --shell zsh --plugins plugins.txt --alias gs='git status'
$ sigma-shell apply-plan --shell zsh --dest ~/.zshrc

    ```

    ## Build & test
    ```
    make build
    make test
    ```

    ## Licence
    GNU General Public License v3.0 (FOSS).
