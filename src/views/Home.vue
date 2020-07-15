<template>
  <div class="home">
    <b-container>
      <b-row align-v="center">
        <job-card v-for="job in jobs" :key="job.id" :name="job.name"></job-card>
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
  },
  mounted() {
    this.fetchData()
  },
  data() {
    return {
      jobs: []
    }
  },
  methods: {
    async fetchData() {
      const response = await fetch("jobs.json")
      const value = await response.json()
      this.jobs = value
      console.log(value)
    }
  }
}
</script>
