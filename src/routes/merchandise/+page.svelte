<script>
import Nav from "$lib/components/Nav.svelte";
import items from "$lib/data/merchandise.json";
</script>

<h1>Merchandise</h1>

<section class="products">

  {#each items as item}
  <div class="product">
      <img src={item.image} alt={item.name}>
      <p>{item.name}</p>
  </div>
  {/each}

</section>

<h2>Order form</h2>

<form>
  <label for="name">Name</label>
    <input type="text" name="name" required>
  

  <label for="email">Email</label>
    <input type="email" name="email" required>
  
  <label for="address">Address</label>
    <input type="address" name="address">
  
  <button type="submit">Submit</button>

</form>

<style>
:global(body){
  align-items: center;
  
}
  .products{
    display: flex;
    gap: 20px;
  }
  .product img{
    width: 200px;
    height: auto;
  }
  form{
    display: grid;
  }
  button{
    background-color: rgb(229, 219, 33);
    border-radius: 30px;
    margin-top: 3vh;
  }
  input{
    border-radius: 30px solid;
    color: rgb(247, 201, 48);
  }
  p{
    color: antiquewhite;
    font-family: 'Cormorant Garamond', serif;
    font-size: large;
  }
</style>