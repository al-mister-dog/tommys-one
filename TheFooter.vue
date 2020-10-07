<template>
  <link
    rel="stylesheet"
    href="https://maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css"
  />
  <div class="wrapper">
    <h2>Contact</h2>
    <p>{{ p1 }}</p>
    <p>{{ p2 }}</p>
    <ul>
      <li class="social">
        <a><i class="fa fa-twitter"></i></a>
      </li>
      <li class="social">
        <a><i class="fa fa-facebook"></i></a>
      </li>
      <li class="social">
        <a><i class="fa fa-spotify"></i></a>
      </li>
      <li class="social">
        <a><i class="fa fa-instagram"></i></a>
      </li>
      <li class="social">
        <a><i class="fa fa-youtube"></i></a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      p1:
        "We play all sorts of events from pubs, clubs and festivals to weddings and business events.",
      p2: "Please send gig and event queries to thethumpingtommys@gmail.com",
    };
  },
};
</script>

<style scoped>
.wrapper {
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: antiquewhite;
}
ul {
    display: flex;
    list-style: none;
    justify-content: center;
  align-items: center;
  padding: 0;
}
.social {
    margin: 1rem;
}
</style>