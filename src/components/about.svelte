
<div class="main-container">
    
    <div class="img-container">
        <img class="img-item" src="https://media.licdn.com/dms/image/D5603AQFu10td_MrZxA/profile-displayphoto-shrink_800_800/0/1691527861938?e=1697068800&v=beta&t=JPHq_EJQKj2Py9mKzyw-ogiRN1awKKWkyhwhM7wP1SM">
    </div>

    <div class= "main-info-container">
        <div class= "info-container">
            <span class="name">Hussein ElSherif</span>
    
            <span class="job">Senior Fullstack developer<br>@ Cegedim Egypte</span>
    
            <span class="statement">I build modern high performing digital experiences for the web</span> 
        </div>

        <div class = "nav-container">
                <li>
                    <a>About</a>
                </li>
            
                <li>
                    <a>Experience</a>
                </li>
            
                <li>
                    <a>Projects</a>
                </li>
            
                <li>
                    <a>Reference</a>
                </li>
        </div>

    </div>

</div>



<style>
    @media (min-width: 1000px){
        .img-container{
            margin-left: 10vw;
            align-items: center;
            justify-content: center;
            display: flex;
            max-width: 15vw;
            width: 15vw;
            height: fit-content;
        }

        .img-item{
            border-radius: 100%;
            width: inherit;
            max-width: inherit;
        }

        .main-info-container{
            display: flex;
            flex-shrink: 1;
            flex-direction: column;
            justify-content: space-between;
            align-items: start;
            width: 100vw;
            height: 100vh;
            gap: 1rem;
        }

        .info-container{
            display: flex;
            flex-shrink: 1;
            flex-direction: column;
            justify-content: flex-start;
            align-items: start;
            width: 100%;
            height: 20vh;
            gap: 1rem;
        }

        .nav-container{
            flex-direction: column;
            flex:1;
            align-items: flex-start;
            align-self: flex-start;
            margin-left: 1vw;
        }

        .nav-container li{
            margin-top: 1.5vh;
        }

        li::marker{
            content:"-";
            font-size: 1.5rem;
            vertical-align: bottom;
        }
    }
    
    @media (max-width: 1000px){

        .img-container{
            margin-left: 0;
            width: 30vw;
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

        .nav-container{
            display:none;
        }
    }

</style>