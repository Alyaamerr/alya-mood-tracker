<script>
    import Greeting from '$lib/Greeting.svelte';
    import Entry from '$lib/Entry.svelte';
</script>

<Greeting />
<!--   Entries   -->
<section class="container px-4 py-3 bg-warning">
    <div class="d-flex justify-content-between">
   	 <div class="p-2"><b>Mood Log</b></div>
   	 <input class="btn btn-light mb-2" type="button" value="+ New Entry" />
    </div>

    <div class="list-group mb-3">
   	 <!-- Individual Entries -->
    	<Entry />
   	 
    </div>
</section>
