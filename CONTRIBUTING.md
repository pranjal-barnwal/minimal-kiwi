# How to Contribute

<img src="./assets/coverpage.webp" alt="Minimal Kiwi Cover by Pranjal Kumar (@pranjal-kumar)" width=400>

> _Open for contributions. Learn more about [creating extensions](./vsc-extension-quickstart.md)._

[![Pull Requests Welcomed](https://img.shields.io/badge/PRs-Welcomed-brightgreen.svg?style=flat)](https://github.com/pranjal-barnwal/minimal-kiwi)
[![Minimal Kiwi, loved by community](https://img.shields.io/badge/Community-Loved-pink.svg)](https://github.com/pranjal-barnwal/minimal-kiwi)

1. Fork & Clone the [repo](https://github.com/pranjal-barnwal/minimal-kiwi)

    ```pwsh
    git clone git@github.com:{YOUR_GITHUB_USERNAME}/minimal-kiwi.git
    ```

2. Move to the `minimal-kiwi` directory

    ```pwsh
    cd minimal-kiwi
    ```

3. Make the required changes in color-schema & other properties in: `./themes/Minimal Kiwi-color-theme.json`. Also update the **_version_** in `./package.json`.

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
