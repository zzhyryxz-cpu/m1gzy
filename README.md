
<div class="hub" id="hub">
  <header id="dragBar">
    <div class="brand">
      <span class="logo">S</span>
      <div>
        <strong>SEBI HUB</strong>
        <small>Script Interface</small>
      </div>
    </div>
    <div class="window-buttons">
      <button id="minBtn">−</button>
      <button id="closeBtn">×</button>
    </div>
  </header>

  <div id="hubBody">
    <nav class="tabs">
      <button class="tab active" data-tab="home">Home</button>
      <button class="tab" data-tab="scripts">Scripts</button>
      <button class="tab" data-tab="settings">Settings</button>
    </nav>

    <main>
      <section class="page active" id="home">
        <p class="eyebrow">WELCOME BACK</p>
        <h2>Script Hub</h2>
        <p class="muted">Your custom interface is ready.</p>
        <div class="status">
          <span class="dot"></span>
          Interface online
        </div>
      </section>

      <section class="page" id="scripts">
        <h2>My Scripts</h2>
        <p class="muted">Choose a demo button.</p>
        <input id="search" placeholder="Search scripts..." />
        <div id="scriptList">
          <button class="script-card" data-name="speed">
            <span>Speed UI</span><span>›</span>
          </button>
          <button class="script-card" data-name="visual">
            <span>Visual UI</span><span>›</span>
          </button>
          <button class="script-card" data-name="utility">
            <span>Utility UI</span><span>›</span>
          </button>
        </div>
      </section>

      <section class="page" id="settings">
        <h2>Settings</h2>
        <label class="setting">
          <span>Glow effect</span>
          <input type="checkbox" id="glowToggle" checked />
        </label>
        <label class="setting">
          <span>Show status</span>
          <input type="checkbox" id="statusToggle" checked />
        </label>
        <button class="action" id="resetBtn">Reset settings</button>
      </section>

      <div class="message" id="message">
        Welcome to Sebi Hub!
      </div>
    </main>

    <footer>SEBI HUB <span>•</span> v1.0</footer>
  </div>
</div>

<button id="reopenBtn">S</button>
