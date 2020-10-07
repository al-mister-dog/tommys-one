<template>
<div class="band-bios__wrapper">
  <h2>About</h2>
  <div class="band-bios">
    <p class="band-bio">{{ bio1 }}</p>
    <p class="band-bio">{{ bio2 }}</p>
    <p class="band-bio">{{ bio3 }}</p>
  </div>
  <div class="member-bios">
    <div class="member-bio">
      <h3 class="member-bio__title">{{memberBioTitle1}}</h3>
      <h3 class="member-bio__subtitle">{{memberBioSubtitle1}}</h3>
      <p class="member-bio__p">{{memberBio1}}</p>
    </div>
    <div class="member-bio">
      <h3 class="member-bio__title">{{memberBioTitle2}}</h3>
      <h3 class="member-bio__subtitle">{{memberBioSubtitle2}}</h3>
      <p class="member-bio__p">{{memberBio2}}</p>
    </div>
    <div class="member-bio">
      <h3 class="member-bio__title">{{memberBioTitle3}}</h3>
      <h3 class="member-bio__subtitle">{{memberBioSubtitle3}}</h3>
      <p class="member-bio_p">{{memberBio3}}</p>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      bio1:
        "The Thumping Tommy’s are Benedict Scrivener, Alex Hunter and Giles Casswell. They started some time around 2012, when Ben and Giles used to live with each other in North London. Every Friday Al would come over and everyone would jam old Dubliners and Leadbelly tunes they’d picked up from their parent’s record collections, and drink cans of Guinness and Holstein Pils staying up til about six in the morning. After realising this was really fun they decided to try get some gigs.",
      bio2:
        "In 2013 the Tommys had gathered enough songs to be able to play around pubs in London. Around this time they were picked up by Jim Beam bourbon company who took the Tommys on a distillery tour around Europe. It turned out Bluegrass and bourbon was a great combination, and the Tommys have gained a reputation for playing fun energetic music fused with depth and wide emotional range.",
      bio3:
        "Since those early days the Tommys have performed regular shows at various folk festivals and venues in the UK, Belgium, Norway, and elsewhere. They recently recorded their debut album of original songs at Woodworm Studios, founded by UK folk legends Fairport Convention. The album also features Georgina Leach on the Violin, Tim Fairhall on the bass and Cherise Adams-Burnett on guest vocals. The Fairport Convention subsequently invited the Tommys to play their famous Fairports Cropredy Convention festival in August 2020, after meeting and playing a session with them at Costa Del Folk festival in Portugal in October 2019.",
      memberBioTitle1: "Alex Hunter",
      memberBioTitle2: "Ben Scrivener",
      memberBioTitle3: "Giles Casswell",
      memberBioSubtitle1: "Banjo and some guitar",
      memberBioSubtitle2: "Guitar and some banjo",
      memberBioSubtitle3: "Mandolin, washboard and spoons",
      memberBio1:
        "Before moving to London to pursue a music career Al grew up in Grimsby where he regularly skipped school while dreaming of becoming a basket ball star, later working full time at a fish processing factory. Al learned to play guitar from his Dad, Jim – an ex trawlerman – who taught him picking patterns and Bob Dylan songs. When not playing with the Tommy’s, Al can be found playing New Orleans jazz and Swing music. He has six brothers and sisters and about fifteen nephews and neices, all who play guitar and sing as well.",
      memberBio2:
        "Recognised as a guitar prodigy from an early age, Ben was sent to the Royal Academy of Music youth programme where he spent most of his time looking out the window at the pub over the road. A classic romantic, Ben loves to buy fridge magnets when abroad and goes on long walks, often frequenting graveyards looking for ghosts. Ben also has a sailing license. ",
      memberBio3:
        "Giles grew up on a farm with his four brothers, endowing him with boundless energy as well as the skill of being able to sleep literally anywhere. Eventually he ended up on tour supporting John mayall and the Blues Breakers before his career took a nose dive, starting up the Tommys with Al and Ben. Giles also sings to kids at a nursery school and usually drives the Tommy’s round when they can’t use public transport.",
    };
  },
};
</script>

<style scoped>
.band-bios__wrapper {
  position: relative;
  max-width: 684px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-color: rgb(0, 0, 0, 0.01);
  color: antiquewhite;
  margin: auto;
  margin-top: 8rem;
}

.band-bios {
    margin-bottom: 5rem;
}
.member-bio {
  margin-bottom: 5rem;
}

.member-bio__title {
  margin-bottom: 0;
}
.member-bio__subtitle {
  margin-top: 0;
  margin-bottom: 0;
}
.member-bio__p {
  margin-top: 0;
}
</style>