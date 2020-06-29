<script>
  import { page } from "./stores";

    import Nav from "./Nav.svelte"
    import DISC from "./DISC.svelte";
    import Contact from "./Contact.svelte";
</script>

<Nav />
{#if $page}
  <svelte:component this={$page} />
{:else}
  <p>this is the home page</p>
{/if}
