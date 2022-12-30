<template>
  <div class="misc-wrapper">
    <div class="misc-inner p-2 p-sm-3">
      <div class="w-100 text-center">
        <h2 class="mb-1">We are launching soon 🚀</h2>
        <p class="mb-1">
          We're creating something awesome. Please subscribe to get notified
          when it's ready!
        </p>
        <p class="mb-5">contact@maronx.com</p>

        <!-- form -->
        <b-form
          inline
          class="row justify-content-center m-0 mb-2 flex-row flex-nowrap"
          @submit.prevent
        >
          <b-form-input
            id="notify-email"
            class="col-12 col-md-5 mb-1 mr-5"
            type="text"
            placeholder="john@example.com"
          />

          <b-button
            variant="primary"
            class="btn-sm-block ml-5"
            type="submit"
            style="width: 100px"
          >
            Notify
          </b-button>
        </b-form>

        <b-img
          fluid
          :src="require('@/assets/images/pages/coming-soon.svg')"
          alt="Coming soon page"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>


<style lang="scss">
@import "@core/scss/vue/pages/page-misc.scss";
</style>
