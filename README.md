# honkit-plugin-i18nsettings

This plugin adds language settings button in the Honkit website.

### Enable this plugin

it can be enabled using a `book.json` configuration:

```
{
    plugins: ["i18nsettings"]
}
```

### Configuration

This plugin can be configured in the `book.json`:

Default configuration is:

```js
{
    "pluginsConfig": {
        "i18nsettings": {
            "language": "en",
            "languages": [
            {
                "config": "en",
                "text": "English"
            }]
        }
    }
}
```

### Plugin API

This plugin exposes the following API to easily allow new themes to manage the plugin behavior.

All API functions are called using the prefix `gitbook.i18nsettings.`, for instance `gitbook.i18nsettings.changeLanguage()`.
