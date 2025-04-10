<script lang="ts">
    // Future reactive state or fetch logic can go here
  </script>
  
  <svelte:head>
    <title>BRANACA-SVET – Security Validation Tool</title>
    <meta name="description" content="Run automated security scans with educational feedback based on OWASP standards." />
  </svelte:head>
  
  <main class="min-h-screen bg-gray-50 flex flex-col items-center justify-center px-6 py-12">
    <section class="w-full max-w-4xl text-center">
      <h1 class="text-4xl font-bold text-gray-800 mb-4">BRANACA-SVET</h1>
      <p class="text-lg text-gray-600 mb-8">
        Empowering developers with automated security scans and educational OWASP feedback.
      </p>
  
      <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
        <button
          class="bg-blue-600 hover:bg-blue-700 text-white px-6 py-3 rounded-xl text-sm font-medium shadow transition"
          aria-label="Start Security Scan"
          disabled
        >
          Start Scan (Coming Soon)
        </button>
  
        <button
          class="border border-gray-300 text-gray-700 px-6 py-3 rounded-xl text-sm font-medium shadow-sm hover:bg-gray-100 transition"
          aria-label="Learn more about BRANACA-SVET"
        >
          Learn More
        </button>
      </div>
    </section>
  </main>
      