   <script>
    import Nav from "$lib/components/Nav.svelte";
   </script> 

 <svelte:head>
    <title>QUEEN CHARLOTTE-Home page</title>
 </svelte:head>
 <hearder>
    <img src="/images/logotype.png" alt="logo">
    </hearder>
  
<main>
    <img src="/images/homeimage.jpg" alt="queen charlotte backround">
</main>
<style>
:global(body){
    font-family: 'Cormorant Garamond', serif;
    background-image: url("/images/pattern.svg");
    background-color: rgb(198, 149, 45);
}
main img{
    margin-top: 10px;
    width: 100%;
    height: 30%;
}
:global(header){
   justify-content: center;
   align-items: center;
   height: 10vh;
   display:flex;
   width: 100%;
   padding: 10px 20px;
}
</style>

