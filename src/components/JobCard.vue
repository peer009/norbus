<template>
    <div class="container">
      <div>
          <div class="jumbotron">
          <h1>GOLD COAST MAFIA</h1>      
        <p>Go on acquiring power in the name of the LORD and in the mightness of his strength.</p>
       </div>

      </div>
      <b-row align-v="centre">
        <b-col>
          <b-card title="SKY" 
            img-src="../assets/lights.jpg"
            img-alt="job-info"
            img-top
            style="max-width:40rem"
            tag="article"
            class="img-thumbnail mb-2"
          >
            <b-card-text>
              <pre style="font-family:Georgia,serif;">
                "Ghosts of dead rainbows dancing through the sky,
                All heaven quivering to their noiseless feet,
                Hand held in hand in eager circles fleet,
                Sharp phalanxes that pierce, and darts that fly,
                And ranks that shiver up to where on high
                Spirits of light and ghosts of color meet
                In a trembling phantom heart, whose pulses heat
                With pallid beauty, palpitate, and die".
              </pre>
            </b-card-text>
            <b-button v-b-toggle.collapse-0 variant="info">Details </b-button>
            <b-collapse id="collapse-0" class="mt-2">
              <b-card>
                  <p class="card-text">Northern Lights <br> by Amos Russel Wells</p>
              </b-card>
            </b-collapse>
          </b-card>
        </b-col>
        <b-col>
          <b-card title="FOREST" 
            img-src="../assets/nature.jpg"
            img-alt="job-info"
            img-top
            style="max-width:40rem"
            tag="article"
            class="img-thumbnail mb-2"
          >
            <b-card-text>
              <pre style="font-family:Georgia,serif;">
                "This is the forest primeval. 
                The murmuring pines and the hemlocks,
                Bearded with moss, and in garments green, indistinct in the twilight,
                Stand like Druids of old, with voices sad and prophetic,
                Stand like harpers hoar, 
                with beards that rest on their bosoms".
              </pre>
            </b-card-text>
            <b-button v-b-toggle.collapse-1 variant="info">Details </b-button>
            <b-collapse id="collapse-1" class="mt-2">
              <b-card>
                  <p class="card-text">Evangeline<br>by Henry Wadsworth Longfellow </p>
                </b-card>
            </b-collapse>
          </b-card>
        </b-col>
      </b-row>  
    </div>
    
</template>

<script>
export default {
    
}
</script>

<style scoped lang="scss">


</style>