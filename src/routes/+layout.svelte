<script>
import Header from "./Header.svelte";
</script>

<div class="container mt-2">
    <Header />

    <main>
        <slot />
    </main>

    <footer>
        <hr>
        <p>Wingfoil Gear Talk powered by wingbuddies.de 2023</p>
    </footer>
</div>