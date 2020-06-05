<template>
  <div>
    <!-- <div>{{message}}</div> -->
    <div v-for='(item) in items' :key="item">
      {{item}}
    </div>
    <input type="checkbox" id='isTrue' value="adq" v-model="isTrue">
    <label for="isTrue">{{isTrue}}</label>
    <input type="text" value="ahjk">
    <p>
      <input type="checkbox"  id="jspan" value="jspans" v-model="web_name">
      <label for="isTrue">jspan</label>
      <input type="checkbox"  id="Panda" value="Panda" v-model="web_name">
      <label for="isTrue">Panda</label>
      <input type="checkbox"  id="panpan" value="pampan" v-model="web_name">
      <label for="isTrue">panpan</label>
    </p>
    <p>
      {{web_name}}
    </p>
  </div>
</template>

<script>
export default {
  name:'about',
  data () {
    return {
      items:[1,3,4,5,6,7,8,1],
      isTrue:true,
      // isTrue:[],
      web_name: []
    }
  }
}
</script>

<style>

</style>