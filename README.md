# tailwindcss-animate-css

TailwindCSS v4.0 compatible replacement for `tailwindcss-animate`
([GitHub][Original_Plugin_GitHub], [npm][Original_Plugin_NPM]).

Instead of being an old-fashioned JavaScript plugin, this package provides a
CSS file defining custom utilities based on the new
[CSS-first architecture][TailwindCSS_Custom_Utilities], hence the suffix.

## Installation

### NPM

1. Install the package with `npm`:

   ```bash
   npm install tailwindcss-animate-css
   ```

2. Add the following line to your `app.css` or `globals.css` file:

   ```css
   @import "tailwindcss-animate-css";
   ```

   > [!NOTE]
   > This works with esbuild, Vite and probably other bundlers too. If you are
   > using a different bundler, the syntax may differ.
   > [Let me know][Create_Issue] how it works and I'll update the documentation.

3. Start using the animations!

### Manual download

1. Download the [`tailwindcss-animate.css`][CSS_File]
   file from GitHub and place it next to your `app.css`.
2. Add the following line to your `app.css` or `globals.css` file:

   ```css
   @import "./tailwindcss-animate.css";
   ```

3. Start using the animations!

## Usage

Refer to the [original documentation][Original_Plugin_Docs] for more information.

> [!NOTE]
> I use very litte of the original library, so it might not be a 100% compatible
> drop-in replacement. If you notice any inconsistencies, feel free to contribute
> to this repository by opening a pull-request.

<!-- Links -->

[Original_Plugin_GitHub]: https://github.com/jamiebuilds/tailwindcss-animate
[Original_Plugin_NPM]: https://www.npmjs.com/package/tailwindcss-animate
[Original_Plugin_Docs]: https://github.com/jamiebuilds/tailwindcss-animate/blob/main/README.md
[TailwindCSS_Custom_Utilities]: https://tailwindcss.com/docs/adding-custom-styles#adding-custom-utilities
[Create_Issue]: https://github.com/Wombosvideo/tailwindcss-animate-css/issues/new
[CSS_File]: https://raw.githubusercontent.com/Wombosvideo/tailwindcss-animate-css/refs/heads/main/src/tailwindcss-animate.css
