<script>
    import {Route} from 'svelte-routing';
    import Home from "../pages/Home.svelte";
    import Testimonios from '../pages/Testimonios.svelte';
</script>

<Route path="/">
    <Home />
</Route>
<Route path="/testimonios">
    <Testimonios />
</Route>