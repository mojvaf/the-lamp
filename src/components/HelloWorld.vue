<template>
<div id='app'>
 <div class='lamp' v-on:click='toggle'>
   <div class='shade'>
     <div class='light' v-if='on'>
     </div>
   </div>
   <div class='base'></div>
 </div>
</div>
</template>
<script>
export default {
  name: 'HelloWorld',
   el: '#app',
    methods:{
     toggle: function(){
      this.on = !this.on
     }
   }
}
</script>
