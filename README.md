
<div style="text-align: center; transform: scale(.5);">
  <img src="https://github.com/tldraw/tldraw-v1/raw/main/assets/card-repo.png"/>
</div>

---

> **Note**<br>
The code in this repository is for the **original version** of tldraw, which is hosted at [old.tldraw.com](https://old.tldraw.com). The code for the **new version** (hosted at [tldraw.com](https://tldraw.com)) can be found in the main [tldraw repo](https://github.com/tldraw/tldraw).

**🙋‍♂️ As of 2024, this version is no longer actively maintained.**

---

## Contents

This repository is a monorepo containing two packages:

- [**packages/tldraw**](https://github.com/tldraw/tldraw-v1/tree/main/packages/tldraw) contains the source for the [@tldraw/tldraw](https://www.npmjs.com/package/@tldraw/tldraw) package. This is an editor as a React component named `<Tldraw>`. You can use this package to embed the tldraw editor in any React application.
- [**packages/core**](https://github.com/tldraw/tldraw-v1/tree/main/packages/core) contains the source for the [@tldraw/core](https://www.npmjs.com/package/@tldraw/core) package. This is a renderer for React components in a canvas-style UI. It is used by `@tldraw/tldraw` as well as several other projects.

...and one app:

- [**apps/www**](https://github.com/tldraw/tldraw-v1/tree/main/apps/www) contains the source for the [tldraw.com](https://tldraw.com) website.

...and three examples:

- [**examples/core-example**](https://github.com/tldraw/tldraw-v1/tree/main/examples/core-example) is a simple example for `@tldraw/core`.
- [**examples/core-example-advanced**](https://github.com/tldraw/tldraw-v1/tree/main/examples/core-example-advanced) is a second example for `@tldraw/core`.
- [**examples/tldraw-example**](https://github.com/tldraw/tldraw-v1/tree/main/examples/tldraw-example) is an example for `@tldraw/tldraw`.

## Discussion

Want to connect? Visit the [Discord channel](https://discord.gg/SBBEVCA4PG).

## Contribution

Interested in contributing? See the [contributing guide](/CONTRIBUTING.md).

## Support

Need help? Please [open an issue](https://github.com/tldraw/tldraw-v1/issues/new) for support.

## License

This project is licensed under MIT.

If you're using the library in a commercial product, please consider [becoming a sponsor](https://github.com/sponsors/steveruizok?frequency=recurring&sponsor=steveruizok).

## Trademarks

The tldraw name and logo are trademarks of tldraw. Please see our [trademark guidelines](https://github.com/tldraw/tldraw/blob/main/TRADEMARKS.md) for info on acceptable usage.

## Author

- [@steveruizok](https://twitter.com/steveruizok)
