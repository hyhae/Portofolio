
<div class="main-container">
    
    <div class="img-container">
        <img class="img-item" src="https://media.licdn.com/dms/image/D5603AQFu10td_MrZxA/profile-displayphoto-shrink_800_800/0/1691527861938?e=1697068800&v=beta&t=JPHq_EJQKj2Py9mKzyw-ogiRN1awKKWkyhwhM7wP1SM">
    </div>

    <div class= "info-container">
        <span class="name">Hussein ElSherif</span>

        <span class="job">Senior Fullstack developer<br>@ Cegedim Egypte</span>

        <span class="statement">I build modern high performing digital experiences for the web</span    >
    </div>
</div>



<style>
    .main-container{
        display: flex;
        flex-direction: row;
        flex:1;
        justify-content: space-evenly;
        align-items: center;
        gap: 1rem;
        margin-top: 15vh;
        width:50vw;
    }

    .img-container{
        margin-left: 10vw;
        align-items: center;
        justify-content: center;
        display: flex;
        max-width: 20vw;
        width: 20vw;
        height: fit-content;
    }

    .img-item{
        border-radius: 100%;
        width: inherit;
        max-width: inherit;
    }

    .info-container{
        margin-top: 10%;
        display: flex;
        flex-shrink: 1;
        flex-direction: column;
        justify-content: flex-start;
        align-items: start;
        width: 100%;
        gap: 1rem;
    }

    .name{
        font-size: 3vh;
        font-weight: 700;
    }

    .job{
        font-size: 2vh;
    }

    .statement{
        font-size: 1.5vh;
    }
    
    @media (max-width: 1000px){
        .main-container{
            display: flex;
            flex-direction: column;
            justify-content: space-evenly;
            gap: 1rem;
            margin: 10vw ;
            align-items: normal;
        }

        .img-container{
            margin-left: 0;
            width: 60vw;
            max-width: inherit;
            display: flex;
            flex-direction: row;
            justify-content: center;
        }

        .img-item{
            width: inherit;
            max-width: inherit;
            align-self: center;
            border-radius: 100%;
        }


        .info-container{
            width: 80vw;
            display: flex;
            flex-direction: column;
            flex:1;
        }

        .name{
            font-size: 8vw;
            font-weight: 700;
        }
        
        .job{
            font-size: 4vw;
        }

        .statement{
            font-size: 3vw;
        }
    }

</style>