# SauerTracker Vue Components

This project provides a few components for pulling and displaying data from
sauertracker.net.

## Usage

Add to your project:

```
yarn add sauertracker-vue-components
# or
npm install sauertracker-vue-components --save
```

Import in your Vue file:

```
import { ServerList } from 'sauertracker-vue-components'
```

Add to your components list:

```
components: {
  // ...
  ServerList
}
```

Use in your template:

```
<server-list
  title="SauerTracker Servers"
  api-url="https://sauertracker.net/api/servers"
  :dark="false"
  :show-empty="false"
/>
```

## Examples

Check the _src/examples_ for example usage.

## License

MIT
