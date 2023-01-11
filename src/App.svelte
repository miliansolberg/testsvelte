<script>
  import Navigation from "./components/navigation.svelte";
  import Button from "./components/Button.svelte";
  import Form from "./components/Form.svelte";
  import Footer from "./components/Footer.svelte";
</script>

<main>
  <Navigation />
  <h1>Welcome to my first Svelte project</h1>
  <Button />
  <Form />
  <Footer />
</main>

<style>
  h1 {
    text-align: center;
    padding-top: 60px;
  }
</style>
