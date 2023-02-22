<template>
  <div>
    <b-row class="mt-5">
      <b-col cols="12" md="4">
          <b-card title="Lenguaje de Programación" img-src="https://www.php.net/images/meta-image.png" img-alt="Image" img-top>
            <b-card-text>
              PHP es un lenguaje de programación interpretado del lado del servidor y de uso general que se adapta especialmente al desarrollo web
            </b-card-text>

            <b-button href="https://es.wikipedia.org/wiki/PHP" variant="primary" target="_blank">Más Información</b-button>
          </b-card>
      </b-col>
      <b-col cols="12" md="4">
          <b-card title="Lenguaje de Programación" img-src="https://blog.codmind.com/content/images/2021/01/banner-5.jpg" img-alt="Image" img-top>
            <b-card-text>
              Java es un lenguaje de programación y una plataforma informática que fue comercializada por primera vez en 1995 por Sun Microsystems.
            </b-card-text>
            <b-button href="https://es.wikipedia.org/wiki/Java_(lenguaje_de_programaci%C3%B3n)" variant="danger" target="_blank">Más Información</b-button>
          </b-card>
      </b-col>
      <b-col cols="12" md="4" >
          <b-card title="Lenguaje de programación" img-src="https://soyhorizonte.com/wp-content/uploads/2020/10/Javascript-by-SoyHorizonte.jpg" img-alt="Image" img-top>
            <b-card-text>
              JavaScript es un lenguaje de programación interpretado, dialecto del estándar ECMAScript. Se define como orientado a objetos, basado en prototipos, imperativo, débilmente tipado y dinámico.
            </b-card-text>

            <b-button href="https://es.wikipedia.org/wiki/JavaScript" variant="dark" target="_blank">Más información</b-button>
          </b-card>
      </b-col>
    </b-row>

  </div>
</template>

<script>
export default {
  name: 'Card'
}
</script>