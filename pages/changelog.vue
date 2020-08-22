<template>
<div class="container">
  <h1 class="col s12">Changelog</h1>
  <div class="col s12 changelog">
    <div class="card-changelog">
        <div class="card-content-changelog white-text" style="margin:1,2%">
            <span class="card-title-changelog" style="margin-bottom: 0;">SlayBot Version 0.1.5</span>
            <span class="discord-text text-greyple" style="margin-bottom: 8px; display: block;">22nd of August 2020</span>
            <p><i class="fas fa-wrench"></i> Fixed</p>
            <p class="cl-desc">
            • Fixed incorrect statistics on the <code>stats</code> command.
            </p>
            <p><i class="fas fa-exclamation-triangle"></i> Known Issues</p>
            <p>
            • The presences are still showing incorrect amount of servers or users. Please use <code>stats</code> command to get the correct stats
            </p>
        </div>
    </div>
    <div class="card-changelog">
        <div class="card-content-changelog white-text" style="margin:1,2%">
            <span class="card-title-changelog" style="margin-bottom: 0;">SlayBot Version 0.1.4</span>
            <span class="discord-text text-greyple" style="margin-bottom: 8px; display: block;">18th of August 2020</span>
            <p><i class="fas fa-edit"></i> Updates</p>
            <p>
            • Added Environment field to the <code>stats</code> command
            </p>
        </div>
    </div>
    <div class="card-changelog">
        <div class="card-content-changelog white-text" style="margin:1,2%">
            <span class="card-title-changelog" style="margin-bottom: 0;">SlayBot Version 0.1.3</span>
            <span class="discord-text text-greyple" style="margin-bottom: 8px; display: block;">16th of August 2020</span>
            <p><i class="fas fa-wrench"></i> Fixed</p>
            <p>
            • Fixed <code>bug</code> and <code>suggestion</code> commands
            </p>
        </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  head: {
    title: 'Changelog',
  },
}
</script>