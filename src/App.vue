<template>
  <div id="nav">
    <router-link to="/">Principal</router-link>
  </div>
  <router-view/>
</template>

<style>
.container {
  display: grid;
  grid-template-columns: auto;
  max-width: 100%;
}

#header {
  margin: 1em;
}

#footer {
  margin: 1em;
}

#product-list {
  display: grid;
  grid-template-columns: 33.3% 33.4% 33.3%;
  margin: 1em;
}

#product-info {
  display: grid;
  grid-template-columns: 5% 30% auto 10%;
  margin: 1em;
}

.imagen-previsualizacion {
  max-height: 100%;
  max-width: 100%;
}

.product {
  border: 1px solid black;
  margin: 1em 1em 1em 0;
}

.product-description {
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
  max-width: 20em;
}

.product-image {
  max-width: 100%;
  max-height: 100%;
}
</style>
