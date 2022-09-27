# VUE
New controller is a single component file, a component is a template + a controller

Vue component uses Template, Script, and Style

EVERY VUE CONTROLLER WILL HAVE THIS!!!!!
export default {
  setup() {
    return {     always last thing in the controller

    }
  }
}
Factory Pattern

Setup is like the constructor for Vue

Anything in script return, you will have scope to by using: {{}} plus whatever returned value you want to display

Setup(){let affection = 3}
return {affection}  {{affection}} shows as 3 on HTML side

Vue doesn't use onclick because it would overwrite the handler. So it uses @click="function()"

In Setup: let cat = appstate.cat

img src ends up being <`img :src="object.property">
This is called ATTRIBUTE BINDING

{{}} is called HANDLEBARS TEMPLATING

Homepage to get cats on page means make new CatCard.vue

Tags are self-closing for CatCard, makes it <`CatCard />

slot tags allow you to put text in between <`slot><'/slot>

v-for="c in cats" is forEach now c is a banana-word

