<script>
    import Navbar from "../components/Navbar.svelte"
    import DashboardContainer from "../components/dashboard_container.svelte";
</script>

<div class="base-bg bg-gray-900">
    <Navbar />
    <DashboardContainer/>

</div>


<style>
    .base-bg{
        height:100vh;
        min-height: 500px;
    }
</style>