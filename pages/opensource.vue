<template>
<div class="container" style="margin-top:30px;margin-bottom:30px;">
  <h2>Open-Source</h2>
  <p>This page has list of Open-Source libraries we use</p><br>

  <h4>SlayBot's Libraries</h4>
  <div class="row osrow">
        <div class="col-6"><a href="https://www.npmjs.com/package/@sentry/node">@sentry/node</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/ascii-table">ascii-table</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/chalk">chalk</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/crypto">crypto</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/datadog-metrics">datadog-metrics</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/discord.js">discord.js</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/figlet">figlet</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/generate-password">generate-password</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/intl">intl</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/moment">moment</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/moment-duration-format">moment-duration-format</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/mongoose">mongoose</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/ms">ms</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/node-fetch">node-fetch</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/nodemon">nodemon</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/pm2">pm2</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/request">request</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/request-promise-native">request-promise-native</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/statcord.js">statcord.js</a></div>
        <div class="col-6"><a href="https://www.npmjs.com/package/uuid">uuid</a></div>
    </div>
</div>
</template>

<script>
export default {
  head: {
    title: 'Open Source',
  },
}
</script>

<style scoped>
/*! CSS Used from: https://taigabot.net/css/app.css */
*,*::before,*::after{box-sizing:border-box;}
a{color:#ff006d;text-decoration:none;background-color:transparent;}
a:hover{color:#b3004c;text-decoration:none;}
.row{display:flex;flex-wrap:wrap;margin-right:-15px;margin-left:-15px;}
.col-6{position:relative;width:100%;padding-right:15px;padding-left:15px;}
.col-6{flex:0 0 50%;max-width:50%;}
@media print{
*,*::before,*::after{text-shadow:none!important;box-shadow:none!important;}
a:not(.btn){text-decoration:underline;}
}
div.osrow a{color:white;}
div.osrow a:hover{color:#EFEFEF;}
</style>