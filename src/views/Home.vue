<template>
    <div class="home">
        <b-container>
          <b-row align-v="centre">
              <job-card></job-card>
          </b-row> 
        </b-container>
    <!-- <b-container>
      <b-row align-v="centre">
        <b-col md="3">
          <b-card title="This Is A Card" 
            img-src="../assets/image.jpg"
            img-alt="job-info"
            img-top
            tag="article"
            style="max-width:20rem"
            class="mb-2"
          >
            <b-card-text>
              This is the body of the card which contains information pertaining to that card.
            </b-card-text>
            <b-button variant="primary">Apply </b-button>
          </b-card>
        </b-col>
        <b-col md="3">
          <b-card title="This Is The Second Card" 
            img-src="../assets/image.jpg"
            img-alt="job-info"
            img-top
            tag="article"
            style="max-width:20rem"
            class="mb-2"
          >
            <b-card-text>
              This is the body of the card which contains information pertaining to that card.
            </b-card-text>
            <b-button variant="primary">Apply </b-button>
          </b-card>
        </b-col>
        <b-col md="3">
          <b-card title="This Is The Third Card" 
            img-src="../assets/image.jpg"
            img-alt="job-info"
            img-top
            tag="article"
            style="max-width:20rem"
            class="mb-2"
          >
            <b-card-text>
              This is the body of the card which contains information pertaining to that card.
            </b-card-text>
            <b-button variant="primary">Apply </b-button>
          </b-card>
        </b-col>
        <b-col md="3">
          <b-card title="This Is The Forth Card" 
            img-src="../assets/image.jpg"
            img-alt="job-info"
            img-top
            tag="article"
            style="max-width:20rem"
            class="mb-2"
          >
            <b-card-text>
              This is the body of the card which contains information pertaining to that card.
            </b-card-text>
            <b-button variant="primary">Apply </b-button>
          </b-card>
        </b-col>
      </b-row>
    </b-container> -->
  </div>
</template>

<script>
// @ is an alias to /src
import JobCard from "@/components/JobCard.vue";

export default {
  name: "Home",
  components: {
      "job-card": JobCard
  }
};
</script>
