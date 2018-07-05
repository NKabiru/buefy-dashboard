<template>
    <div class="columns is-fullheight">
        <div class="column is-2 is-fullheight">
            <sidebar></sidebar>
        </div>

        <div class="column is-10 is-fullheight">
            <navbar></navbar>
        </div>
    </div>
</template>

<script>
import Sidebar from "../components/Sidebar";
import Navbar from "../components/Navbar";
export default {
  name: "home",
  components: { Navbar, Sidebar }
};
</script>
