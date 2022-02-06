# docums-table-reader-plugin

[Docums](https://khanhduy1407.github.io/docums/) plugin that adds a `{{ read_csv('table.csv') }}` markdown tag to directly insert CSV files as a table into a page.

## Installation

Install the plugin using `pip3`:

```bash
pip3 install docums-table-reader-plugin
```

Next, add the following lines to your `docums.yml`:

```yml
plugins:
  - search
  - table-reader
```

> If you have no `plugins` entry in your config file yet, you'll likely also want to add the `search` plugin. Docums enables it by default if there is no `plugins` entry set.

## Usage

In your markdown documents you can now use:

```html
{{ read_csv('path_to_table.csv') }}
```

Where the path is relative to the location of your project's `docums.yml` file.

## Documentation

See [khanhduy1407.github.io/docums-table-reader-plugin/](https://khanhduy1407.github.io/docums-table-reader-plugin/).