# dev_fsVUE3
Vue.js 3.x development and prototyping

##### NOTES
- Basically a supercharged version of Vue 2, and is even faster and lighter, comes with improved Typescript support, and some great new features

##### Key Differences v2 vs. v3
- v2 
  Vue v2 creating App
  ```
  import Vue from 'vue'
  import App from './App.vue'
  
  Vue.config.productionTip = false
  
  new Vue({
    render: h => h(App),
  }).$mount('#app')
  ```  

- v3 launched in Q3 2020
  Vue v3 creating App
  ```
  import { createApp } from 'vue'
  import App from './App.vue'
  import './index.css'
  
  createApp(App).mount('#app')
  ``` 
