<template>
  <div class="container" style="margin-top:30px">
    <h2>Frequently Asked Questions</h2><br>
    <b-card no-body class="mb-3">
      <b-card-header header-tag="header" class="p-0" role="tab">
        <b-button block v-b-toggle.accordion-1 variant="dark">WHY DOES SLAYBOT NOT RESPOND TO ANY COMMANDS?</b-button>
      </b-card-header>
      <b-collapse id="accordion-1" accordion="my-accordion" role="tabpanel">
        <b-card-body style="background-color:#181b24">
          <b-card-text>1. Make sure that SlayBot has the <code>Send Messages</code> permission as well as the <code>Embed Links</code> permission and that it has access to your channel.</b-card-text>
          <b-card-text>2. Are you typing the command correctly? View the command list to check the usage.</b-card-text>
          <b-card-text>3. Check our <a href="https://status.slaybot.xyz">statuspage</a> and <a href="https://status.discordapp.com">Discord's status</a> if SlayBot appears to be offline!</b-card-text>
        </b-card-body>
      </b-collapse>
    </b-card>

    <b-card no-body class="mb-3">
      <b-card-header header-tag="header" class="p-0" role="tab">
        <b-button block v-b-toggle.accordion-2 variant="dark">How can i invite SlayBot to my server?</b-button>
      </b-card-header>
      <b-collapse id="accordion-2" accordion="my-accordion" role="tabpanel">
        <b-card-body style="background-color:#181b24">
          <b-card-text>It's simple! Just go to <a href="/invite">https://slaybot.xyz/invite</a> and then there should be some servers where you can add it.</b-card-text>
        </b-card-body>
      </b-collapse>
    </b-card>

    <b-card no-body class="mb-3">
      <b-card-header header-tag="header" class="p-0" role="tab">
        <b-button disabled block v-b-toggle.accordion-3 variant="dark">How can i change the prefix? (soon)</b-button>
      </b-card-header>
      <b-collapse id="accordion-3" accordion="my-accordion" role="tabpanel">
        <b-card-body style="background-color:#181b24">
          <b-card-text>{{ text }}</b-card-text>
        </b-card-body>
      </b-collapse>
    </b-card>
  </div>
</template>

<script>
export default {
  head: {
    title: 'FAQ',
  },
}
</script>