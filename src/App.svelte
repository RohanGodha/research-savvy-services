<script>
  import About from "./components/About.svelte";
  import Contact from "./components/Contact.svelte";

  let sections = [
    "about me",
    "my resume",
    "contact me",
    "book me",
    "my projects",
  ];
</script>

<main>
  <h1>Welcome to Research Savvy Services</h1>

  {#each sections as section}
    <a href="#{section}">{section}</a>
  {/each}

  <section id="about me">
    <About />
  </section>

  <section id="contact me">
    <Contact />
  </section>

  <!-- Other sections here -->
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 600px;
    margin: 0 auto;
  }
  a {
    display: block;
    margin-bottom: 5px;
  }
</style>
