# SauerTracker Vue Components

This project provides a few components for pulling and displaying data from
sauertracker.net.

## Usage

Add to your project:

```bash
yarn add sauertracker-vue-components
# or
npm install sauertracker-vue-components --save
```

Import in your Vue file:

```javascript
import { ServerList } from "sauertracker-vue-components";
```

Add to your components list:

```javascript
components: {
  ServerList,
  // ...
}
```

Use in your template:

```html
<server-list
  title="SauerTracker Servers"
  api-url="https://sauertracker.net/api/servers"
  :dark="false"
  :show-empty="false"
/>
```

## Examples

Check
[src/examples](https://github.com/AngrySnout/sauertracker-vue-components/tree/master/src/examples)
for example usage.

## License

MIT
