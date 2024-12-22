<script>
  import * as m from "$lib/paraglide/messages.js";
  import { page } from "$app/stores";
</script>

<span>{m.hello_world({ name: "Bobini" })}</span>

<p>current url path is {$page.url}</p>
