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

Call movies in setup on HomePage since that's the first thing drawn when the page loads.

Get movies from appstate by putting in return

return{
  movies: computed(() => AppState.movies)
}

new Date(movie.releaseDate).toLocaleStringDate() ends up like 09/27/2022

.toLocaleStringDate('en-us', ...)

NEVER put forms directly on the page, make a component

editable is a proxy object
`<form @submit.prevent="handleSubmit" name="search" v-model="editable.term">`

setup() {
  const editable = ref({})

  return {
    editable,
    async handleSubmit() {
      try {

      }
      catch(error) {
        logger.error('[SearchForm]', error)
        Pop.error(error)
      }
    }
  }
}

Service: async getMoviesBySearchTerm(term) {
  const res = await moviesApi.get('/search/movie', {
    params: {
      query: term
    }
  })
  AppState.movies = res.data.results.map(m => new Movie(m))
  AppState.page = res.data.page
  AppState.lastPage = res.data.total_pages
}

setActiveMovie() {
  AppState.activeMovie = props.movie 
}

Put modal or other offscreen in App.vue

? is the Elvis operator. If Elvis is in the building, go ahead. If not, then Elvis has left the building, essentially do nothing.

If an object is possibly null, then use movie?.title to say to wait until you have the object. Only works in advanced frontend frameworks like Vue, not vanilla js.