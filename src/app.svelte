<script>
  import { Route } from 'svelte-navigator';
  import Layout from './layouts/default.svelte';
  import Index from './pages/index.svelte';
</script>

<Layout>
  <Route path="/" component={Index} />
</Layout>
