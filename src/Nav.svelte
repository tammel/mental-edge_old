<script>
	import { page } from './stores'
	
  import Disc from "./DISC.svelte"
  import Contact from "./Contact.svelte"
</script>

<nav>
	<button on:click={ () => { $page = undefined } }>Home</button>
    <button on:click={ () => { $page = Disc } }>DISC</button>
    <button on:click={ () => { $page = Contact } }>Contact Us</button>
</nav>
