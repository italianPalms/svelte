<script>
    import './page.css';
    let name = 'Svelte';
    import Nested from './Nested.svelte';
    let string = 'this string contains some <strong>HTML!!!</strong>';
</script>

<h1>Hello {name}!</h1>

<p>This is a paragraph</p>
<Nested />

<p>{@html string}</p>





<style>
    p{
        font-size: 2em;
    }
   
</style>