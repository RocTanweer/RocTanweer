<style>
    .markdown-body {
        --primary-color: #582DCD;
        --accent-color: #05EBC5;
        --bg-dark: #1E1926;
    }

    .header-container{
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        aspect-ratio: 3/1;
        background: url('quantum-gradient.svg') no-repeat center center;
        background-size: cover;
        margin-bottom: 3rem;
        padding: 1rem;
        border:2px solid;
    }
    .latest-projects{
        border: 1px solid red;
        width: 100%;
    }
    .latest-projects__heading{
        font-size: clamp(1.7rem, 2.4vw, 2rem);
        text-align: center;
    }
    .latest-projects__list{
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        gap: 1rem;
        padding:  0 2rem;
        width: clamp(20rem, 52.2vw, 50rem);
        border: 2px solid #b3b3b3;
        margin: 0 auto;
    }

    .latest-projects__list--item{
        width:300px;
        height: 200px;
        /* aspect-ratio: 1.3/0.8; */
        position: relative;
        overflow:hidden;
        cursor:pointer;
        border:2px solid green;
    }
    .latest-projects__list--item:hover .img-container{
        bottom:0px;
    }
    .img-container{
        position: absolute;
        width:100%;
        bottom: -1049px;
        transition: bottom ease 2s;
    }
</style>

<div class="header-container">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+code&color=%2305EBC5&size=28&center=true&vCenter=true&multiline=true&width=415&height=79&lines=Hi%2C+I'm+Roc+%F0%9F%91%8B;I+build+stuff+on+the+web;Nice+to+see+you+here+%F0%9F%98%8A" />
</div>

<div class="latest-projects">
    <p class="latest-projects__heading">Some Noteworthy Projects 😊</p>
    <div class="latest-projects__list">
        <a href="https://recify.netlify.app/">
            <div class="latest-projects__list--item">
                <div class="img-container">
                    <img src="https://res.cloudinary.com/dlqc9xkmy/image/upload/v1640893204/Github-Readme/recify-light_nrlgyz.png" />
                </div>
            </div>
        </a>
        <a href="https://recify.netlify.app/">
            <div class="latest-projects__list--item">
                <div class="img-container">
                    <img src="https://res.cloudinary.com/dlqc9xkmy/image/upload/v1640955974/Github-Readme/recify-light_nrlgyz_2_xkcj5s.png" />
                </div>
            </div>
        </a>
        <a href="https://recify.netlify.app/">
            <div class="latest-projects__list--item">
                <div class="img-container">
                    <img src="https://res.cloudinary.com/dlqc9xkmy/image/upload/v1640893203/Github-Readme/bookmark_x7xxyl.png" />
                </div>
            </div>
        </a>
        <a href="https://recify.netlify.app/">
            <div class="latest-projects__list--item">
                <div class="img-container">
                    <img src="https://res.cloudinary.com/dlqc9xkmy/image/upload/v1640893203/Github-Readme/room_cvdjm6.png" />
                </div>
            </div>
        </a>
        <a href="https://recify.netlify.app/">
            <div class="latest-projects__list--item">
                <div class="img-container">
                    <img src="https://res.cloudinary.com/dlqc9xkmy/image/upload/v1640893203/Github-Readme/weatherpng_lzvpbw.png" />
                </div>
            </div>
        </a>
    </div>
</div>
