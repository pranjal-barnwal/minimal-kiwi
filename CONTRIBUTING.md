# How to Contribute
> Open for contributions.
Learn more about [creating extensions](./vsc-extension-quickstart.md).

[![Pull Requests Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](https://github.com/pranjal-barnwal/minimal-kiwi)
[![first-timers-only Friendly](https://img.shields.io/badge/beginner-friendly-blue.svg)](https://github.com/pranjal-barnwal/minimal-kiwi)

1. Fork & Clone the [repo](https://github.com/pranjal-barnwal/minimal-kiwi)
    ```pwsh
    git clone git@github.com:{YOUR_GITHUB_USERNAME}/minimal-kiwi.git
    ```

2. Move to the `minimal-kiwi` directory
    ```pwsh
    cd minimal-kiwi
    ```

3. Make the required changes in color-schema & other properties in: `./themes/Minimal Kiwi-color-theme.json`. Also update the ***version*** in `./package.json`.

4. For packaging we're using `vsce` package and `Yeoman` & `generator-code` for management. So install the required dependencies.
    ```pwsh
    npm install -g vsce yo generator-code
    ```

5. Then package the changes, to be pushed into Marketplace
    ```pwsh
    vsce package
    ```
    > This should generate a `minimal-kiwi-{VERSION}.vslx` file. If not then resolve the errors being caused.

6. Commit & push the updated changes. Then make a PR to this [repo](https://github.com/pranjal-barnwal/minimal-kiwi).
<br/><br/>




# Contributors
<a href="https://github.com/pranjal-barnwal/minimal-kiwi/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=pranjal-barnwal/minimal-kiwi" />
</a>
<br/><br/>