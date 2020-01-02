<template>
    <div id="dashboard">
        <h5>Dashboard</h5>

        <div class="fixed-action-btn">
            <router-link to="/new" class="btn-floating btn-large red">
                <i class="fa fa-plus"></i>
            </router-link>
        </div>
    </div>
</template>

<script>
export default {
    name: 'dashboard',
    data() {
        return {

        }
    }
}
</script>