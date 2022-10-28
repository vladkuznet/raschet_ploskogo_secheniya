<html>
<h1 align="center">Raschet_ploskogo_secheniya</h1>
<p>В файле организованы несколько функций с возможностью редактирования входных данных.
При занании характеристик бетонного сечения могут использоваться нормативные данные из СП63.13330 (трехлинейная диограмма деформирования бетона)
</p>
<body>
  <p><img src="https://user-images.githubusercontent.com/111303182/198578082-4643ec4f-ed54-4724-b33c-a27c46337cb5.png"></p>
</body>
  
### Global Usage

Global Registeration via Vue.use() method.

```js
// main.js
import Vue from "vue";
import App from "./App.vue";
import router from "./router";
// import the plugin
import Calendar from "vue2-baremetrics-calendar";

Vue.config.productionTip = false;

// use the plugin
Vue.use(Calendar);

new Vue({
  router,
  render: h => h(App)
}).$mount("#app");
```
</html>
описание (с использованием слов и изображений);
демо (изображения, ссылки на видео, интерактивные демо-ссылки);
технологии в проекте;
что-то характерное для проекта (проблемы, с которыми пришлось столкнуться, уникальные составляющие проекта);
техническое описание проекта (установка, настройка, как помочь проекту).
