<script>
  let sections = [
    "about me",
    "my resume",
    "contact me",
    "book me",
    "my projects",
  ];
</script>

<main>
  <h1>Welcome to My Research Work Help</h1>

  {#each sections as section}
    <a href="#{section}">{section}</a>
  {/each}

  <section id="about me">
    <h2>About Me</h2>
    <p>Place your 'About Me' content here.</p>
  </section>

  <section id="my resume">
    <h2>My Resume</h2>
    <p>Place your 'Resume' content here.</p>
  </section>

  <section id="contact me">
    <h2>Contact Me</h2>
    <p>Place your 'Contact Me' content here.</p>
  </section>

  <section id="book me">
    <h2>Book Me</h2>
    <p>Place your 'Book Me' content here.</p>
    <p>Provide your UPI ID: [Your UPI ID]</p>
  </section>

  <section id="my projects">
    <h2>My Projects</h2>
    <p>Place your 'Projects' content here.</p>
  </section>
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }
  a {
    display: block;
    margin-bottom: 5px;
  }
</style>
