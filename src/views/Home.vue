<template>
  <div class="home">
    <b-container>
      
      <b-row align-v="center">
        <job-card></job-card>
        <!-- <b-col md="3">
          <b-card
            title="This is a Card"
            img-src="https://picsum.photos/600/300/?image=36"
            img-alt="Job-info"
            img-top
            tag="article"
            style="max-width:20rem"
            class="mb-2"
          >
            <b-card-text>Text...Text...Text...</b-card-text>
            <b-button variant="primary">Apply</b-button>
          </b-card>
        </b-col>

        <b-col md="3">
          <b-card
            title="This is a Card"
            img-src="https://picsum.photos/600/300/?image=36"
            img-alt="Job-info"
            img-top
            tag="article"
            style="max-width:20rem"
            class="mb-2"
          >
            <b-card-text>Text...Text...Text...</b-card-text>
            <b-button variant="primary">Apply</b-button>
          </b-card>
        </b-col>

        <b-col md="3">
          <b-card
            title="This is a Card"
            img-src="https://picsum.photos/600/300/?image=36"
            img-alt="Job-info"
            img-top
            tag="article"
            style="max-width:20rem"
            class="mb-2"
          >
            <b-card-text>Text...Text...Text...</b-card-text>
            <b-button variant="primary">Apply</b-button>
          </b-card>
        </b-col>

        <b-col md="3">
          <b-card
            title="This is a Card"
            img-src="https://picsum.photos/600/300/?image=36"
            img-alt="Job-info"
            img-top
            tag="article"
            style="max-width:20rem"
            class="mb-2"
          >
            <b-card-text>Text...Text...Text...</b-card-text>
            <b-button variant="primary">Apply</b-button>
          </b-card>
        </b-col> -->
      </b-row>

      
    </b-container>
  </div>
</template>

<script>
// @ is an alias to /src
import JobCard from '@/components/JobCard.vue'

export default {
  name: "Home",
  components: {
    "job-card": JobCard
  }
};
</script>
