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
  <title>Svelte Society Day</title>
</svelte:head>

<div class="shaded">
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
          <a href="#docs">HOME</a>
        </li>
        <li>
          <a href="#docs">DOCS</a>
        </li>
        <li>
          <a href="#faq">FAQ</a>
        </li>
      </ul>
    </nav>
  </header>
</div>
<slot />
