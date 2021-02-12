<template>
  <v-expansion-panels class="white">
    <v-expansion-panel class="white">
      <v-expansion-panel-header>
        Liste des Clients
      </v-expansion-panel-header>
      <v-expansion-panel-content>
        <ul id="clients-list">
          <li v-for="client in clients" :key="client.name" class="text-left">{{ client.name }}</li>
        </ul>
      </v-expansion-panel-content>
    </v-expansion-panel>
  </v-expansion-panels>
</template>

<script>
module.exports = {
  data: function () {
    return {
      clients: [
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Bar' },
      { name: 'Foo' },
      { name: 'Bar' }
      ]
    }
  }
}
</script>

<style scoped>
  ul {
    column-count: 6;
    color: black;
    font-weight: 300;
    list-style: none;
  }
  v-expansion-panel-header {
    text-align: center;
  }
  button {
    color: black;
    text-align: center;
  }
  v-expansion-panels {
    box-shadow: none;
  }
</style>