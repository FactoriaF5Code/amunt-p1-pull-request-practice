<script>
    import logo from './assets/logo.png'
    import {Router} from 'svelte-routing'
    import Header from "./lib/components/Header.svelte";
    import Routes from "./lib/components/Routes.svelte";
    import Catálogos from "./lib/pages/Catálogos.svelte";
</script>

<Router>
    <Header />
    <Routes />
    <Catálogos />
</Router>

<style>
</style>