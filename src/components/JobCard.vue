<template>
  <div>
     <b-col>
          <b-card
            :title="name"
            img-src="https://picsum.photos/600/300/?image=36"
            img-alt="Job-info"
            img-top
            tag="article"
            style="max-width:20rem"
            class="mb-2"
            footer="Card Footer"
          >
            <b-card-text>Text...Text...Text...</b-card-text>
            <b-button variant="primary">Apply</b-button>
          </b-card>
        </b-col>
  </div>
</template>

<script>

export default {
  name: 'home',
  props: ['name']
}
</script>

<style lang="scss" scoped>

</style>