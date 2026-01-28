---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
permalink: /app/
---

<link rel="icon" type="image/svg+xml" href="/assets/favicon.svg">

Welcome to Shopt, the shopping app that makes discovering and buying products effortless.

<div class="hero">
  <img src="/assets/shopt-logo.png" alt="Shopt app logo" class="app-logo">
  <h1>Shop Smarter. Shop Faster. Shop Shopt.</h1>
  <p class="subtitle">The ultimate shopping experience.</p>
  <a href="https://apps.apple.com/us/app/shopt/id6744074115" class="cta-btn">Download on the App Store</a>
</div>

<div class="features">
  <div class="feature">
    <h2>Curated Products</h2>
    <p>Discover trending and handpicked items tailored just for you.</p>
  </div>
  <!-- <div class="feature">
    <h2>Seamless Checkout</h2>
    <p>Fast, secure, and easy checkout with Apple Pay integration.</p>
  </div> -->
  <div class="feature">
    <h2>Best recommendations</h2>
    <p>No advertisements. Just the best recommendations.</p>
  </div>
</div>

<div class="app-preview">
  <img src="/assets/shopt-app-preview.png" alt="Shopt app preview" class="app-screenshot">
</div>

<div id="download" class="download-section">
  <a href="https://apps.apple.com/us/app/shopt/id6744074115" class="app-store-badge">
    <img src="/assets/app-store-badge.svg" alt="Download on the App Store">
  </a>
</div>

<style>
.hero {
  text-align: center;
  padding: 3rem 1rem 2rem 1rem;
  background: linear-gradient(120deg, #f8fafc 0%, #e0e7ef 100%);
}
.app-logo {
  width: 100px;
  margin-bottom: 1.5rem;
}
.cta-btn {
  display: inline-block;
  margin-top: 1.5rem;
  padding: 0.75rem 2rem;
  background: #007aff;
  color: #fff;
  border-radius: 2rem;
  font-size: 1.2rem;
  text-decoration: none;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  transition: background 0.2s;
}
.cta-btn:hover {
  background: #005ecb;
}
.cta-btn:visited {
  color: #fff;
  background: #007aff;
}
.subtitle {
  color: #555;
  font-size: 1.2rem;
  margin-bottom: 1.5rem;
}
.features {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
  margin: 3rem 0 2rem 0;
}
.feature {
  background: #fff;
  border-radius: 1rem;
  box-shadow: 0 2px 12px rgba(0,0,0,0.04);
  padding: 2rem;
  max-width: 320px;
  flex: 1 1 250px;
  text-align: center;
}
.app-preview {
  text-align: center;
  margin: 2rem 0;
}
.app-screenshot {
  width: 260px;
  border-radius: 2rem;
  box-shadow: 0 4px 24px rgba(0,0,0,0.10);
}
.download-section {
  text-align: center;
  margin: 3rem 0 2rem 0;
}
.app-store-badge img {
  width: 180px;
}
.note {
  color: #888;
  margin-top: 1rem;
}
@media (max-width: 900px) {
  .features {
    flex-direction: column;
    gap: 1.5rem;
  }
}
</style>
