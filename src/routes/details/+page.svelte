
   <script>
        import Nav  from "$lib/components/Nav.svelte";
   </script>
   <svelte:head>
        <title>Details- character page</title>
   </svelte:head>

    <div class="section-reverse">
    <div class="character">
    <div class="image_box1">
        <img src="/images/charlotte01.jpg" alt="Queen Charlotte">
    </div>
     <div class="text">
        <p>
            The miniseries revolves around Queen Charlotte and consists of two plot lines: 
            one in the present of Bridgerton, beginning in 1814 with the death of the royal heir 
            Princess Charlotte, an event that causes the Queen to pressure her children to marry 
            and produce another royal heir; the other begins in 1761 with Charlotte meeting and 
            marrying King George. The latter explores the King and Queen's marriage and his mental illness.
        </p>
    </div>
</div>
</div>


    <div class="character_gallery">
    <img src="/images/charlotteGeorge01.jpg" alt="Queen Charlotte">
    <img src="/images/charlotteGeorge02.jpg" alt="Queen Charlotte">
    <img src="/images/charlotteGeorge03.jpg" alt="Queen Charlotte">
    </div>


<div class="section">

    <div class="text">
        <p>
            Queen Charlotte is from a small town named Mirow in Northern Germany. 
            After her parents died, she was raised by her brother Duke Adolphus. 
            Against Charlotte's wishes, Adolphus signed a betrothal contract to marry 
            Charlotte off to the King George III of England. They traveled together 
            to London for the wedding.
        </p>
    </div>

    <div class="image_box">
        <div class="title_box">
            <img src="/images/ornamentLeft.png" alt="">
            <h2>CHARLOTTE</h2>
            <img src="/images/ornamentRight.png" alt="">
        </div>

        <img src="/images/charlotte02.jpg" alt="Charlotte">
    </div>

</div>

<div class="section reverse">

    <div class="text">
        <p>
            King George was talking to Farmer Crosby about the advantages of using 
            horses in place of oxen when his valet, Reynolds came to get him and 
            said his mother needed him at the palace. He believed the dowager 
            princess had found King George a bride.
        </p>
    </div>

    <div class="image_box">
        <div class="title_box">
            <img src="/images/ornamentLeft.png" alt="">
            <h2>GEORGE</h2>
            <img src="/images/ornamentRight.png" alt="">
        </div>

        <img src="/images/george01.jpg" alt="George">
    </div>

</div>

<div class="section">

    <div class="text">
        <p>
            Agatha Danbury is a senior matron who is considered one of the most 
            powerful women in London high society. Lady Danbury is the Queen's 
            closest friend and helped her adjust to her position as Queen.
        </p>
    </div>

    <div class="image_box">
        <div class="title_box">
            <img src="/images/ornamentLeft.png" alt="">
            <h2>LADY DANBURY</h2>
            <img src="/images/ornamentRight.png" alt="">
        </div>

        <img src="/images/ladyDanbury.jpg" alt="Lady Danbury">
    </div>

</div>

<div class="section reverse">

    <div class="text">
        <p>
            When Charlotte came to London to marry King George III, Brimsley was 
            assigned to work with her, starting with taking her to the seamstress 
            to have her dress fitted.
        </p>
    </div>

    <div class="image_box">
        <div class="title_box">
            <img src="/images/ornamentLeft.png" alt="">
            <h2>BRIMSLEY</h2>
            <img src="/images/ornamentRight.png" alt="">
        </div>

        <img src="/images/brimsley.jpg" alt="Brimsley">
    </div>

</div>
    <div class="character_gallery">
        <img src="/images/charlotte03.jpg" alt="charlotete03">
        <img src="/images/charlotteGeorge04.jpg" alt="charlotteGeorge04">
        <img src="/images/george02.jpg" alt="george02">
    </div>

<style>
:global(body){
    background-image: url('/images/pattern.svg');
    display: flex;
    flex-direction: column;
    background-color: rgb(198, 149, 45);
    font-family:'Cormorant Garamond', serif;
}
:global(h1), :global(h2), :global(.title_box) {
    letter-spacing: 3px;
    font-weight: 600;
    color: white;
}
.character{
    display: flex;
    align-content: space-between;
    align-items: center;
    width: 85%;
    margin: 90px auto;
    gap: 15px;
}

.character_gallery{
    margin-top: 20px;
    display: flex;
    align-items: center;
    gap: 20px;
}
.character_gallery img{
    width: 450px;
    height: auto;
}

.section {
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 80%;
    margin: 120px auto;
}
.section.reverse{
    flex-direction: row-reverse;
}
.text {
    width: 40%;
    border: 3px solid orange ;
    color: white;
    font-size: 1.9rem;
}


.image_box {
    width: 50%;
    position: relative;   
}

.image_box img {
    width: 100%;
    display: block;
}


.title_box {
    position: absolute;
    top: -70px;         
    left: 0;
    display: flex;
    align-items: center;
    gap: 20px;
    font-size: 22px;
    letter-spacing: 3px;
    
}

.title_box img {
    gap: 40px;
    width: 70px; 
    height: 20px;        
}

</style>
 