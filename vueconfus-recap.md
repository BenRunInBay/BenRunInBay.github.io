# VueConfUS 2019 Recap

## Higlights:
- Vue 3: launch date not set yet, but some great new features to look forward to (see below).
- Caution: if you're using Mixins or Hooks, they are likely to change in Vue 3.
- Some good options are emerging for using Vue to build mobile and desktop applications. See Natalia's presentation below and check out the Ionic Framework.
- Nuxt.js has a great feature where it compiles a page on the server as plain HTML to deliver a fast rendering, and then subsequently downloads Vue and the interactive JS components.

---

## Vue 3 highlights
- Switching from Object.defineProperty to Proxies, which will eliminate reactivity breaks when setting an array index or adding a property to an existing, reactive object. In other words, no more need for Vue.$set()
- Slots refinement and simplification
- v-model and event simplification
- Multiple root nodes
- See [slides from Chris Fritz](https://github.com/chrisvfritz/vue-3-trends)

---

## Especially good presentations:

### Natalia Tepluhina gave an outstanding and succinct talk on building Vue for desktop applications
- [Slides](https://www.slideshare.net/NataliaTepluhina/desktop-apps)

### CSS variables and using advanced CSS in Vue - Miriam E Suzanne
- [Slides](https://talks.oddbird.net/dynamic-css/vueconf19/)

### Performance secrets - Guillaume Chau
- [Slides](https://slides.com/akryum/vueconfus-2019#/)


