<script>
    import Navbar from "../components/Navbar.svelte"
    import DashboardContainer from "../components/dashboard_container.svelte";
</script>


<div class="base-bg ">
    <div class="py-20 h-screen sm:px-20 lg:px-72 bg-gray-900">
        <DashboardContainer/>
    </div>

</div>

<style>
    .base-bg{
        height:100vh;
        min-height: 500px;
    }
</style>