<script>
    import {Route} from 'svelte-routing';
    import Home from "../pages/Home.svelte";
    import Contacto from "../pages/Contacto.svelte";

</script>
<Route path="/">
    <Home />
</Route>
<Route path="/Contacto">
    <Contacto />
</Route>