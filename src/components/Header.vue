<template>
   <v-jumbotron
    :gradient="gradient"
    src="/static/header.jpeg"
    dark
    height="100vh"
  >
    <v-container fill-height>
      <v-layout align-center>
        <v-flex text-xs-center>
          <h3 class="display-3">Gradient over Image</h3>
        </v-flex>
      </v-layout>
    </v-container>
  </v-jumbotron>
</template>

<script>
export default {
    data () {
        return {
        //      items: [
        //   {
        //     src: 'https://images.pexels.com/photos/691582/pexels-photo-691582.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260'
        //   },
        //   {
        //     src: 'https://images.pexels.com/photos/917494/pexels-photo-917494.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260'
        //   },
        //   {
        //     src: 'https://images.pexels.com/photos/904373/pexels-photo-904373.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260'
        //   },
        //   {
        //     src: 'https://images.pexels.com/photos/675278/pexels-photo-675278.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260'
        //   }
        // ],

        gradient: 'to right, #16A085, #F4D03F'


        }
    }
}
</script>


<style lang="scss" scoped>
.toolbar__content > *:not(.btn):not(.menu):last-child:not(:only-child), .toolbar__extension > *:not(.btn):not(.menu):last-child:not(:only-child) {
    margin-right: 3rem;
}

.fluid {
    padding: 0;
    // background-color: red;
}
</style>
