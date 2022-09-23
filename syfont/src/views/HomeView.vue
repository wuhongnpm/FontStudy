<template>
  <div class="home">
  <header>
    <p>Dave Allen</p>
    <ul>
      <li>"Burning Castle" Video Premiere – Sept. 1, 2022 at 12est</li>
      <li>"Burning Castle" Video Premiere – Sept. 1, 2022 at 12est</li>
      <li>~ Music Videos ~</li>
      <li>Paste Review</li>
      <li>Remezcla Interview</li>
      <li>Pitchfork Review</li>
      <li>Treble Review</li>
      <li>Post-Trash Review</li>
      <li>Our Culture Interview</li>
    </ul>
  </header>
  <footer>
    <p><a href="https://beian.miit.gov.cn/#/Integrated/index">鲁ICP备18000993号-2</a></p>
  </footer>
  <address><a href="https://music.renatazeiguer.com/links">Powered By Renatazeiguer</a></address>
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'HomeView'
}
</script>
<style scoped>
.home {
  background-image: url('../assets/img/homeback_img.jpg');
  background-size: cover;
  width: 100%;
  height: 1200px;
  border-radius: 25px;
  border-style:dotted;
  border-color: #A0674B;
  list-style-type: none;
  text-align: center;
}
ul{
  display: flex;
  flex-direction:column;
  align-items:center;

}
li {
  display: block;
  width: 50%;
  border: 0;
  border-radius: 2px;
  font-size: 18px;
  font-weight: 600;
  margin: 1rem 0;
  padding: 25px;
  background-color: rgb(225, 205, 193);
  color: rgb(0, 0, 0);
  opacity: 0.77;
  border-radius: 8px;
}
p{
  text-align: center;
  color: white;
  font-size: 21px;

}
footer {
   color: blue;
   font-size: 21px;
   width: 100%;
   height: 30px;
}
footer a {
  text-decoration: none;
  color:white;
}
address {
  width: 7%;
  background:#6064ff;
  opacity: 0.7;
  padding: 15px;
  border-radius: 6px;
  position: relative;
  left: 0;
  bottom: 0;

}
address a {
  text-decoration: none;
}
</style>
