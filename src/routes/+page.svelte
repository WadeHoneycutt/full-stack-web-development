<script>
    import ToDoItem from "../lib/toDoItem.svelte";

    const title = "Todos";
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>
<h1>{title}</h1>
<form action="">
    <input type="text" name="text" aria-label="Add ToDo" placeholder="+ type to dadd a todo">
</form>

<ToDoItem/>


