# JavaScript

<ClientOnly>
```vue live
<template>
  <div>
    <input v-model="name"/>
    <br/>
    Your name is {{name}}
  </div>
</template>

<script>
  export default {
    data: () => ({
      name: null
    })
  }
</script>
```
</ClientOnly>