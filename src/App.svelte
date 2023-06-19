<script>
    import logo from './assets/logo.png'
    import {Router} from 'svelte-routing'
    import Header from "./lib/components/Header.svelte";
    import Routes from "./lib/components/Routes.svelte";
    import Servicios from "./lib/components/Servicios.svelte";

</script>

<Router>
    <Header />
    <Routes />
    <Servicios />
</Router>

<style>
</style>