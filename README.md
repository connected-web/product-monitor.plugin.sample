# Product Monitor Sample Plugin
A sample plugin (template) for product-monitor that adds an endpoint to generate a random string of characters.

## Development

```
npm install
npm test
```

## Exposed methods
### plugin()
Creates a new instance of the plugin.

```js
var plugin = require('product-monitor.plugin.sample')();
```

### plugin.apply(app)
Applies the plugin to a product-monitor app.

### plugin.info()
Returns the `name`, `description`, and `keywords` for the plugin:

```js
{
    name: 'product-monitor.plugin.sample',
    description: 'A sample plugin (template) for product-monitor that adds an endpoint to generate a random string of characters.',
    keywords: [
      'product-monitor',
      'nodejs',
      'plugin',
      'template'
    ]
}
```

### plugin.getConfig()
Returns the config applied to the plugin.

### plugin.setConfig(pluginConfig)
Changes the config applied to the plugin.

## Change Log
### 1.0.1
- Corrected description of `plugin.info()`

### 1.0.0
- Initial release
