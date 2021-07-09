<template>
  <div class="about">
    <div class="about__body">
      <div class="about__header">
        <div class="about__title title"></div>
        <div class="about__text"> как сделать web-проект</div>
      </div>
      <div class="about__row">
        <div class="about_coll">
          <div class="item_about">
            <div class="item-about__icon">
              <img src="src/assets/01.png"/>
            </div>
            <div class="item-about__title">WEB 1</div>
            <div class="item-about__text">тут первый текст</div>
          </div>
        </div>
        <div class="about_coll">
          <div class="item_about">
            <div class="item-about__icon">
              <img src="src/assets/02.png"/>
            </div>
            <div class="item-about__title"> WEB 2</div>
            <div class="item-about__text"> тут второй текст</div>
          </div>
        </div>
        <div class="about_coll">
          <div class="item_about">
            <div class="item-about__icon">
              <img src="src/assets/03.png"/>
            </div>
            <div class="item-about__title"> WEB 3</div>
            <div class="item-about__text"> туту третий текст</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.about {
}
.about__body{

}

.title {
  font-size: 34px;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 8.95px;
}
</style>
