<script>
  import { Router, Route } from 'svelte-navigator';
  import Layout from './layouts/default.svelte';
  import Index from './pages/index.svelte';
</script>

<Layout>
  <Router>
    <Route path="/" component={Index} />
  </Router>
</Layout>
