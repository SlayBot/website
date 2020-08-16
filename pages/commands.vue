<template>
<div class="container" style="margin-top:30px;margin-bottom:30px;">
  <b-alert show variant="warning">
    <h4 class="alert-heading">Under Construction!</h4>
    <p>
      This page is currently under construction and will be developed actively to make this page ready for you to explore!
      On mobile phones, there is some little issues with the category thing, it will be fixed soon
    </p>
    <hr>
    <p class="mb-0">
      Please use the <code>help</code> command on SlayBot to see every command.
    </p>
  </b-alert>

  <b-card no-body>
    <b-tabs pills card vertical nav-wrapper-class="w-30">
      <b-tab title="Core" active>
        <b-card-text>Tab contents 1</b-card-text>
      </b-tab>

      <b-tab title="Fun">
        <b-card-text>Tab contents 2</b-card-text>
      </b-tab>

      <b-tab title="Information">
        <b-card-text>Tab contents 3</b-card-text>
      </b-tab>

      <b-tab title="Utility">
        <b-card-text>Tab contents 4</b-card-text>
      </b-tab>
    </b-tabs>
  </b-card>
</div>
</template>

<script>
export default {
  head: {
    title: 'Commands',
  },
}
</script>