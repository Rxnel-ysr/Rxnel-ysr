
<style>
  .profile-wrap { max-width: 680px; font-family: var(--font-sans); padding: 2rem 0 1rem; }
  .greeting { font-size: 22px; font-weight: 500; color: var(--color-text-primary); margin: 0 0 4px; }
  .subline { font-size: 14px; color: var(--color-text-secondary); margin: 0 0 2rem; }
  .top-row { display: flex; align-items: flex-start; gap: 20px; margin-bottom: 1.5rem; }
  .avatar-gif { border-radius: var(--border-radius-lg); overflow: hidden; flex-shrink: 0; border: 0.5px solid var(--color-border-tertiary); }
  .stats-col { flex: 1; display: flex; flex-direction: column; gap: 10px; min-width: 0; }
  .stat-img { border-radius: var(--border-radius-md); overflow: hidden; border: 0.5px solid var(--color-border-tertiary); width: 100%; display: block; }
  .section-label { font-size: 11px; font-weight: 500; color: var(--color-text-tertiary); letter-spacing: 0.08em; text-transform: uppercase; margin: 0 0 10px; }
  .langs-streak { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-bottom: 1.5rem; }
  .contact-row { display: flex; align-items: center; gap: 10px; margin-bottom: 1.5rem; }
  .badge-pill { display: inline-flex; align-items: center; gap: 6px; background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: 99px; padding: 6px 14px 6px 10px; font-size: 13px; color: var(--color-text-secondary); text-decoration: none; }
  .badge-dot { width: 8px; height: 8px; border-radius: 50%; background: #D14836; flex-shrink: 0; }
  .devcard-wrap { margin-bottom: 1.5rem; border-radius: var(--border-radius-lg); overflow: hidden; border: 0.5px solid var(--color-border-tertiary); }
  .devcard-wrap img { display: block; width: 100%; }
  .trophies-wrap { border-radius: var(--border-radius-md); overflow: hidden; border: 0.5px solid var(--color-border-tertiary); margin-bottom: 10px; }
  .trophies-wrap img, .activity-wrap img { display: block; width: 100%; }
  .activity-wrap { border-radius: var(--border-radius-md); overflow: hidden; border: 0.5px solid var(--color-border-tertiary); }
  .banner-gif { border-radius: var(--border-radius-lg); overflow: hidden; border: 0.5px solid var(--color-border-tertiary); margin-bottom: 1.5rem; text-align: center; background: #000; }
  .banner-gif img { display: block; width: 100%; max-height: 260px; object-fit: cover; }
</style>
<div class="profile-wrap">
  <h2 class="sr-only">Ronel's GitHub Profile</h2>

  <p class="greeting">Hello 👋 I'm Ronel</p>
  <p class="subline">Developer · Open Source · Always building</p>

  <div class="top-row">
    <div class="avatar-gif">
      <img src="https://i.pinimg.com/originals/ef/f7/99/eff799b62d4575c5e83d4f101e6bc554.gif" height="148" width="148" style="display:block;" alt="avatar" />
    </div>
    <div class="stats-col">
      <img class="stat-img" src="https://github-readme-stats.vercel.app/api?username=rxnel-ysr&hide_title=true&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dark&locale=en&hide_border=true" height="148" alt="GitHub stats" />
    </div>
  </div>

  <p class="section-label">Languages & Streak</p>
  <div class="langs-streak">
    <img class="stat-img" src="https://github-readme-stats.vercel.app/api/top-langs?username=rxnel-ysr&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dark&hide_border=true" height="130" alt="Top languages" />
    <img class="stat-img" src="https://streak-stats.demolab.com?user=rxnel-ysr&locale=en&mode=weekly&theme=dark&hide_border=true&border_radius=5&date_format=M%20j%5B,%20Y%5D" height="130" alt="Streak stats" />
  </div>

  <p class="section-label">Get in touch</p>
  <div class="contact-row">
    <a href="mailto:" class="badge-pill"><span class="badge-dot"></span>Gmail</a>
  </div>

  <div class="banner-gif">
    <img src="https://i.pinimg.com/originals/74/63/59/74635989b770a38189fff31a8ef152ea.gif" alt="banner animation" />
  </div>

  <a href="https://app.daily.dev/rxnel" style="display:block; margin-bottom: 1.5rem;">
    <div class="devcard-wrap"><img src="https://api.daily.dev/devcards/v2/FYBCPsRTboBds4CLH63on.png?type=wide&r=nzy" alt="Ronel's Dev Card" /></div>
  </a>

  <p class="section-label">Trophies</p>
  <div class="trophies-wrap" style="margin-bottom: 10px;">
    <img src="https://github-profile-trophy.vercel.app?username=rxnel-ysr&theme=dracula&column=-1&row=1&margin-w=8&margin-h=8&no-bg=false&no-frame=true&order=4" height="150" alt="GitHub trophies" />
  </div>

  <p class="section-label">Contribution activity</p>
  <div class="activity-wrap">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=rxnel-ysr&radius=16&theme=dracula&area=true&order=5&custom_title=Contribution%20Graph&hide_border=true" height="280" alt="Activity graph" />
  </div>
</div>
