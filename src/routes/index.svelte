<script>
    import TodoItem from "../lib/todo-item.svelte";
    let head = "Todo's";
</script>

<svelte:head>
    <title>{head}</title>
</svelte:head>

<h1>{head}</h1>

<form action="" method="">
    <input type="text" name="text" aria-label="Add a todo" placeholder="+ add to todo" />
</form>

<TodoItem />