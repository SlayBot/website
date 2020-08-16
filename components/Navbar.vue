<template>
<div style="margin-bottom:30px">
  <b-navbar toggleable="lg" type="dark" variant="info">
    <div class="container">
      <b-navbar-brand href="#"><img src="https://cdn.slaybot.xyz/assets/logos/slaybot.svg" width="100" style="margin-top:2px"></b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
            <b-nav-item to="/">
              Home
            </b-nav-item>
            <b-nav-item to="/commands">
              Commands
            </b-nav-item>
            <b-nav-item to="/faq">
              FAQ
            </b-nav-item>
            <b-nav-item to="/stats">
              Stats
            </b-nav-item>
          <b-nav-item-dropdown text="More">
            <b-dropdown-item href="/discord"><i class="fab fa-discord"></i> Discord</b-dropdown-item>
            <b-dropdown-item href="/trello"><i class="fas fa-clipboard-check"></i> Trello</b-dropdown-item>
            <b-dropdown-item to="/changelog"><i class="fas fa-clipboard-check"></i> Changelog</b-dropdown-item>
            <b-dropdown-item href="/status"><i class="fas fa-server"></i> Status</b-dropdown-item>
            <b-dropdown-item href="/twitter"><i class="fab fa-twitter"></i> Twitter</b-dropdown-item>
            <b-dropdown-item href="/reddit"><i class="fab fa-reddit"></i> Reddit</b-dropdown-item>
          </b-nav-item-dropdown>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="/invite"><i class="fab fa-discord"></i> Invite to Discord</b-nav-item>
          <b-nav-item href="/support"><i class="far fa-question-circle"></i> Support Server</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </div>
  </b-navbar>
</div>
</template>