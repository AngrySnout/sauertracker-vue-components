<template>
  <server-list
    title="SauerTracker Servers"
    api-url="https://sauertracker.net/api/servers"
    :dark="false"
    :show-empty="false"
  />
</template>

<script>
import ServerList from "../components/ServerList";

export default {
  name: "ServerListExample",
  components: {
    ServerList
  }
};
</script>

<style>
html,
body {
  margin: 0;
  min-width: 100%;
  width: 100%;
  min-height: 100%;
  height: 100%;
}

body {
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, sans-serif;
}
</style>
