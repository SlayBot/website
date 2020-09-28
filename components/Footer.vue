<template>
  <div id="footer">
    <div style="height: 150px; overflow: hidden;">
  <svg viewBox="0 0 500 150" preserveAspectRatio="none" style="height: 100%; width: 100%;">
    <path d="M0.00,49.98 C149.99,150.00 349.20,-49.98 500.00,49.98 L500.00,150.00 L0.00,150.00 Z" style="stroke: none;fill: #090a0c;"></path>
  </svg>
</div>
    <footer class="footer footer-big">
      <div class="container">
        <div class="content">
          <div class="row">
            <div class="col-lg-3 col-12">
              <div class="column">
                <img
                  src="https://cdn.slaybot.xyz/images/site/slaybotwhite.png"
                  class="logo"
                  alt="SlayBot"
                />
              </div>
              <br />
              <small class="mb-2">
                Registered in Disneyland
                <br />By SlayBot Developers
              </small>
            </div>
            <div class="col-lg-2 col-6">
              <div class="column">
                <h4 class="mt-3">Product</h4>
                <ul>
                  <li>
                    <a href="/blog">News & Updates</a>
                  </li>
                  <li>
                    <router-link to="/privacy">Privacy Policy</router-link>
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-lg-2 col-6">
              <div class="column">
                <h4 class="mt-3">Developers</h4>
                <ul>
                  <li>
                    <a href="https://github.com/slaybot">GitHub</a>
                  </li>
                  <li>
                    <router-link to="/knowledgebase/">Knowledgebase</router-link>
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-lg-2 col-6">
              <div class="column">
                <h4 class="mt-3">Links</h4>
                <ul>
                  <li>
                    <a href="/invite">Invite</a>
                  </li>
                  <li>
                    <a href="/support">Support</a>
                  </li>
                  <li>
                    <a href="/docs">Documentation</a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-lg-3 col-6">
              <div class="column">
                <h4 class="mt-3">You might like</h4>
                <ul>
                  <li>
                    <a href="https://youtube.com">Youtube</a>
                  </li>
                  <li>
                    <a href="https://www.mountaindew.com/">Mountain Dew</a>
                  </li>
                  <li>
                    <a
                      href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"
                    >Rick Astley - Never Gonna Give You Up</a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <hr />
          <div class="row">
            <div class="col-md-8">
              <div class="column">
                <nav>
                  <ul>
                    <li class="d-inline-block">
                      <a href="/" class="nav-link">© 2019-2020 SlayBot.</a>
                    </li>
                    <li class="d-md-inline-block d-none">
                      <a href="/status" class="nav-link">System Status</a>
                    </li>
                    <li class="d-md-inline-block d-none">
                      <a href="/monitor" class="nav-link">System Monitors</a>
                    </li>
                  </ul>
                </nav>
              </div>
            </div>
            <div class="col-md-4 d-none d-md-block">
              <div class="dropdown float-right">
                Language:
                <div
                  class="btn btn-link text-primary"
                  role="button"
                  data-toggle="dropdown"
                  aria-haspopup="true"
                  aria-expanded="false"
                >
                  <i class="fas fa-language d-none d-lg-inline"></i>
                  <span>English</span>
                </div>
                <div
                  class="dropdown-menu"
                  style="position: absolute; transform: translate3d(0px, 42px, 0px); top: 0px; left: 0px; will-change: transform;"
                >
                  <a href="javascript:void(0);" role="button" class="dropdown-item active">
                    <span>English</span>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>