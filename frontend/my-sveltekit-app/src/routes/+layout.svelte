<!-- src/routes/+layout.svelte -->
<script>
    import Header from '$lib/components/Header.svelte';
    import Footer from '$lib/components/Footer.svelte';
  </script>
  
  <Header />
  
  <slot /> <!-- Page content  -->
  
  <Footer />
  