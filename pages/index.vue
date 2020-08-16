<template>
<div>
  <div class="animated fadeInLeft">
    <div class="css-1g6x143">
      <div class="css-a77b4f">
        <div class="css-7e3rlo" style="margin-top: 4.5%;">
          <h1 class="css-1aq9v0y">SlayBot</h1>
          <p class="css-1fwfe0p">SlayBot is a multifunctional Discord bot with XP, moderating and logging features!</p>
          <div class="css-k008qs">
            <a href="https://discordapp.com/oauth2/authorize?&amp;client_id=582237912423465019&amp;scope=bot&amp;permissions=-1" target="_blank" rel="noopener noreferrer">
              <button type="button" class="btn blurple invite-button bold-6 btn-primary">
                <img width="25px" src="https://cdn.slaybot.xyz/assets/logos/discord.svg" alt="discord logo" />
                Invite to Discord
              </button>
            </a>
          </div>
        </div>
        <div class="is-hidden-mobile"><img src="https://cdn.slaybot.xyz/assets/logos/slaybotlogo.png" alt="preview" class="css-16qe6n6" style="width: 60%;" /></div>
      </div>
    </div>
  </div>

  <FeaturesDesktop />
  <FeaturesMobile />
</div>
</template>

<script>
export default {
  head: {
    title: 'Home',
  },
}
</script>

<style>
</style>
