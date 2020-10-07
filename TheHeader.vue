<template>
<div>
  <ul>
    <li class="music">Music</li>
    <li class="video">Video</li>
    <li class="title">The Thumping Tommys</li> 
    <li class="shows">Shows</li>
    <li class="contact">Contact</li>
  </ul>
</div>
</template>

<script>

export default {

}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 div {
  position: absolute;
  width: 100%;
  display: flex;
  background-color: rgb(0,0,0,0.01);
  color: antiquewhite;
}
ul {
  display: flex;
  justify-content: center;
  align-items: center;
  list-style: none;
  margin: auto;
  padding: 0;
}
li {
  margin: 1rem
}
li:hover:not(.title) {
  background-color: rgba(192, 184, 157, 0.5);
  border-radius: 4px;
  cursor: pointer;
}
.title {
  cursor: auto;
  font-size: 2rem;
} 

@media screen and (max-width: 680px) {
  ul {
  min-width: 375px;
  width: 100%;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr;
  gap: 0px 0px;
  grid-template-areas:
    "music video shows contact"
    "title title title title";

  }
  .music {
    grid-area: music;
    margin-bottom: 0;
  }
  .video {
    grid-area: video;
    margin-bottom: 0;
  }
  .shows {
    grid-area: shows;
    margin-bottom: 0;
  }
  .contact {
    grid-area: contact;
    margin-bottom: 0;
  }
  .title {
    grid-area: title;
    margin-top: 0;
  }
} 

</style>
