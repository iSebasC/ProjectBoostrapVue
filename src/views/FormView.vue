<template>
  <div class="mt-5">
    <form action="">
      <b-row>
        <b-col md="6">
          <b-form-input type="text" v-model="texto" :state="comprobar"></b-form-input>
          <small>Minimo de 3 caracteres</small>
        </b-col>
      </b-row>
    </form>
    <p>Texto: {{ texto }}</p>
  </div>
</template>

<script>
export default {
  name: 'Form',
  data() {
    return {
      texto: ''
    }
  },
  computed:{
    comprobar(){
      return this.texto.length > 2 ? true : false
    }
  }
}
</script>