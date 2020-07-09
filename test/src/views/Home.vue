<template>
  <div >
      <div v-for="(room,index) in form" :key="index">
          {{room.name_place}}
        
      </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
            form: [
          {
          name_place: 'aaaa',
          date: '',
          radio: null,
          selected: 'A',
          active:false
          },
          {
          name_place: 'bbbb',
          date: '',
          radio: null,
          selected: 'B',
          active:false
          },
        ],
        }
    },
}
</script>

<style>

</style>