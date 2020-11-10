<template>
  <div>
    <b-table striped hover :items="cats" :fields="fields"></b-table>
  </div>
</template>

<script>
import cats from '@/data/cats'

export default {
  data () {
    return {
      cats: cats
    }
  }
}
</script>
