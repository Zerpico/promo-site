<template>
  <div id="app">   

    <section class="topic">
      <h2 id="about"><a href="#about">#</a>Привет, я Илья</h2>      
      <p>Backend Developer C#</p>
      <p>WPF Developer C#</p> 
    </section>

    <section class="topic">      
      <p>Увлечен программированием, вы можете написать мне в</p>
      <p>
        <a href="mailto:zerpico@yandex.ru">
        <img width="24" height="24" src="./assets/email.png"/>
        zerpico@yandex.ru</a>
        <a href="https://t.me/zerpico">
         <img width="24" height="24" src="./assets/telegram.png"/>
        Telegram</a>
      </p> 
    </section>

    <section class="topic">
      
    </section>

    <section class="nes-container with-title">
      <h3 class="title">Навыки</h3> 
      <div id="textarea" class="item">
        <p>C#, .Net Core, ASP.NET Core/MVC/Web API, EF 6.0</p>
      <p>EF ORM, Dapper ORM, WPF, MVVM, Catel</p>
      <p>MSSQL, PGSQL, SQLite, Firebird</p>
      <p>Docker, Git</p>
      </div>
    </section>

    <section class="nes-container with-title">
      <h3 class="title">Другие навыки</h3> 
      <div id="textarea" class="item">
        <label>Фото- Видеосъемка</label>
        <progress class="nes-progress is-primary"  value="75" max="100"></progress>
      </div>
      <div id="textarea" class="item">
        <label>Прямые руки</label>
        <progress class="nes-progress is-primary"  value="70" max="100"></progress>
      </div>
      <div id="textarea" class="item">
        <label>Пунктуальность</label>
        <progress class="nes-progress is-warning"  value="60" max="100"></progress>
      </div>
      <div id="textarea" class="item">
        <label>Занудство</label>
        <progress class="nes-progress nes-progress-big is-error"  value="150" max="100"></progress>
      </div>
    </section>
   
  </div>
</template>

<script>
export default {
  name: 'app'  
}
</script>

<style>
#app {
  font-family: 'Press Start 2P', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
  max-width: 980px;
  margin: 0 auto;
  margin-top: 50px;
}

.topic {
    margin-bottom: 3rem;
}

.nes-container{
    margin-bottom: 3rem;
}

.nes-progress {
  height: 24px;
  border-image-outset: 1.5;
}

.nes-progress-big {
  width: 120%;
}

label {
    display: inline-block;
    margin-bottom: 0;
    margin-top: 0.3rem;
}

h1, h2 {
  font-weight: normal;
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
</style>
