<script>
    let todos = $state([
        { title: "Assigment 1", done: false },
        { title: "Assigment 2", done: false },
        { title: "Assigment 3", done: false },  
    ])
</script>

<h3> My To Do List</h3>

<ul>
    {#each todos as todo}
    <li>
        {todo.title}
    </li>
    {/each}
</ul>