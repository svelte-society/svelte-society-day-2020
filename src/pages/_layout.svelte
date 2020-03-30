<style>
  .shaded {
    width: 100%;
    background: #f3f6f9;
  }
  header {
    padding: 64px 1rem;
  }
  nav {
    margin: 0;
  }
  @media screen and (max-width: 840px) {
    nav {
      flex-direction: column;
    }
  }
  h1 {
    margin: 0 0 0 35px;
    padding: 0;
    text-align: center;
  }
  a {
    color: black;
    font-size: 19px;
  }
  li a:hover {
    text-decoration: none;
    border-bottom: 4px solid var(--color);
  }
  .logo {
    display: flex;
    align-items: center;
  }
</style>

<svelte:head>
  <title>Svelte Society Day 2020 - A 1-day Online Conference</title>
  <meta
    prefix="og: http://ogp.me/ns#"
    property="og:title"
    content="Svelte Society Day 2020 - An online 1-day Svelte conference" />
  <meta
    prefix="og: http://ogp.me/ns#"
    property="og:url"
    content="https://sveltesociety.dev/" />
  <meta
    prefix="og: http://ogp.me/ns#"
    property="og:description"
    content="Svelte Society Day 2020 - An online 1-day Svelte conference" />
  <meta
    prefix="og: http://ogp.me/ns#"
    property="og:image:secure_url"
    content="https://sveltesociety.dev/logo.jpg" />
  <meta
    prefix="og: http://ogp.me/ns#"
    property="og:image"
    content="https://sveltesociety.dev/logo.jpg" />
  <meta property="og:image" content="https://sveltesociety.dev/logo.jpg" />
  <meta
    property="og:site_name"
    content="Svelte Society Day 2020 - A 1-day Online Conference" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:site" content="@sveltesociety" />
  <meta name="twitter:creator" content="@sveltesociety" />
  <meta
    name="twitter:title"
    content="Svelte Society Day 2020 - 1-day Online Conference" />
  <meta
    name="twitter:image"
    content="Svelte Society Day 2020 - An online 1-day Svelte conference" />
  <meta
    name="twitter:description"
    content="Let's get together for a one day event all about Svelte. Watch some
    talks, learn a thing or two and get to know the community!" />
</svelte:head>

<div class="shaded" id="title">
  <header>
    <nav>
      <div class="logo">
        <a href="/">
          <img alt="Svelte Society Logo" src="./logo.jpg" />
        </a>
        <h1>SVELTE SOCIETY DAY</h1>
      </div>
      <ul>
        <li>
          <a href="#title">HOME</a>
        </li>
        <li>
          <a href="#cfp">CALL FOR PROPOSALS</a>
        </li>
        <li>
          <a href="#faq">FAQ</a>
        </li>
      </ul>
    </nav>
  </header>
</div>
<slot />
