---
layout: default
---

<style>
  .creds {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 12px;
    margin: 4px auto 48px;
    padding: 0 16px;
  }
  .creds a.cred {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    width: auto;
    padding: 9px 18px 9px 14px;
    border: 1px solid rgba(255, 255, 255, 0.28);
    border-radius: 999px;
    background: rgba(255, 255, 255, 0.08);
    -webkit-backdrop-filter: blur(6px);
    backdrop-filter: blur(6px);
    color: rgba(255, 255, 255, 0.92);
    font-size: 14px;
    letter-spacing: 0.02em;
    text-align: left;
    text-decoration: none;
    transition: background-color 200ms, border-color 200ms;
  }
  .creds a.cred:hover,
  .creds a.cred:focus-visible {
    background: rgba(255, 255, 255, 0.18);
    border-color: rgba(255, 255, 255, 0.55);
    outline: none;
  }
  .creds svg {
    width: 18px;
    height: 18px;
    flex: none;
    fill: currentColor;
  }
  .creds .sep {
    width: 1px;
    height: 14px;
    background: rgba(255, 255, 255, 0.35);
  }
  .creds .sub {
    color: rgba(255, 255, 255, 0.7);
  }
</style>

<nav class="creds" aria-label="Credentials">
  <a class="cred" href="https://www.toptal.com/developers/resume/johannes-binder#qZyRxo" target="_blank" rel="noopener">
    <svg viewBox="0 0 21 30" aria-hidden="true"><path fill-rule="evenodd" d="M8.11 0L14.82 6.7C14.87 6.75 14.91 6.8 14.97 6.85L20.82 12.7L11.31 22.16L15.66 26.52L12.75 29.41L6.09 22.75C6.01 22.68 5.93 22.6 5.85 22.52L0 16.68L9.48 7.25L5.16 2.94L8.11 0ZM12.36 10.5C12.27 10.48 12.18 10.48 12.1 10.5C12.01 10.53 11.94 10.57 11.78 10.72L6.37 16.11C6.21 16.27 6.17 16.34 6.15 16.42C6.12 16.51 6.12 16.6 6.15 16.68C6.17 16.77 6.22 16.85 6.37 17L8.09 18.72C8.24 18.87 8.31 18.91 8.4 18.94C8.49 18.96 8.57 18.96 8.66 18.94C8.75 18.91 8.82 18.87 8.97 18.72L14.38 13.33C14.54 13.18 14.58 13.1 14.61 13.02C14.63 12.93 14.63 12.85 14.61 12.76C14.59 12.67 14.54 12.6 14.39 12.45L12.67 10.73C12.52 10.57 12.44 10.53 12.36 10.5Z"/></svg>
    <span>Toptal</span><span class="sep"></span><span class="sub">Top 3% vetted</span>
  </a>
  <a class="cred" href="https://www.credly.com/users/johannes-binder/" target="_blank" rel="noopener">
    <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 1.5l2.2 1.6 2.7-.1.9 2.6 2.2 1.6-.8 2.6.8 2.6-2.2 1.6-.9 2.6-2.7-.1L12 18l-2.2-1.6-2.7.1-.9-2.6L4 12.3l.8-2.6L4 7.2l2.2-1.6.9-2.6 2.7.1L12 1.5zm-1.2 11.2l-2-2-1.3 1.3 3.3 3.3 5.7-5.7-1.3-1.3-4.4 4.4zM7.6 17.6L6 22.5l3-1 2 2.5 1-3.6-4.4-2.8zm8.8 0L12 20.4l1 3.6 2-2.5 3 1-1.6-4.9z"/></svg>
    <span>Credly</span><span class="sep"></span><span class="sub">Certifications</span>
  </a>
</nav>
