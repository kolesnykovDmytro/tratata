<template>
  <div id="app">
    <roomItem/>
  </div>
</template>

<script>
import roomItem from './components/roomItem'

export default {
  name: 'App',
  components: {
    roomItem
  }
}
</script>

<style lang="sass">

@import 'assets/styles/normalize.sass'
@import 'assets/styles/mixins/font-face.sass'
// @import 'assets/styles/fonts.sass'
@import 'assets/styles/vars.sass'

+font-face("roboto-regular", "assets/fonts/RobotoRegular/roboto-regular-webfont")
+font-face("roboto-light", "assets/fonts/RobotoLight/roboto-light-webfont")
+font-face("raleway-medium", "assets/fonts/RalewayMedium/raleway-medium-webfont")
+font-face("raleway-bold", "assets/fonts/RalewayBold/raleway-bold-webfont", bold)
+font-face("raleway-semibold", "assets/fonts/RalewaySemiBold/raleway-semibold-webfont")

#app
  font-family: $default-font
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale

</style>
