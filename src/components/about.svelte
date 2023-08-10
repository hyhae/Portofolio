
<div class="main-container">
    
    <div class="img-container">
        <img class="img-item" src="https://media.licdn.com/dms/image/D5603AQFu10td_MrZxA/profile-displayphoto-shrink_800_800/0/1691527861938?e=1697068800&v=beta&t=JPHq_EJQKj2Py9mKzyw-ogiRN1awKKWkyhwhM7wP1SM">
    </div>

    <div class= "info-container">
        <span class="name">Hussein ElSherif</span>
        <h3 class="job">Senior Fullstack developer at Cegedim</h3>
        <h5 class="statement">I build modern high performing digital experiences for the web</h5>
    </div>
</div>



<style>
    .main-container{
        display: flex;
        flex-direction: row;
        flex:1;
        justify-content: space-evenly;
        gap: 1rem;
        margin-top: 15vh;
        width:50vw;
    }

    .img-container{
        display: flex;
        justify-content: center;
        max-width: 50vw;
    }

    .img-item{
        max-height: 50vh;
        border-radius: 100%;
    }

    .info-container{
        margin-top: 10%;
        display: flex;
        flex-shrink: 1;
        flex-direction: column;
        justify-content: flex-start;
        align-items: start;
        width: 100%;
    }

    .name{
        font-size: 3vh;
        font-weight: 700;
    }

    @media (max-width: 1250px){
        .main-container{
            display: flex;
            flex-direction: column;
            justify-content: space-around;
            gap: 1rem;
            margin-top: 5vh;
            width: 100%;
        }

        .img-container{
            display: flex;
            flex-direction: row;
            justify-content: center;
            align-items: center;
            align-self: center;
        }

        .img-item{
            align-self: center;
            max-height: 30vh;
            border-radius: 100%;
        }


        .info-container{
            display: flex;
            flex-direction: column;
            flex:1;
            justify-content: center;
            align-items: center;
            width: 100vw;
            margin: 0px;
        }

        .name{
            font-size: 3vh;
            font-weight: 700;
        }
        
        .job{
            
        }

        .statement{
            
        }
    }

</style>