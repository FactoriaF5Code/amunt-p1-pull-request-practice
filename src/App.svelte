<script>
    import logo from './assets/logo.png'
    import {Router} from 'svelte-routing'
    import Header from "./lib/components/Header.svelte";
    import Routes from "./lib/components/Routes.svelte";
    import Testimonios from "./lib/pages/Testimonios.svelte";
</script>

<Router>
    <Header />
    <Routes />
    <Testimonios />
</Router>

<style>
</style>