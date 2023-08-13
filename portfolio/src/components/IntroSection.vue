<script>
</script>

<template class="intro-section">
    <div class="image-section">
        <img src="../assets/IMG_20230728_191410.jpg" alt="David Amegayibor's Profile Picture">
        
    </div>
    <h1 class="title">
         Fullstack Web Developer
    </h1>
    <div class="bio">
        <h2>About Me</h2>
        <p>
            My name is David Amegayibor. I am a software engineer specializing in web development.
            Over the past two years, I have acquired and built strong skills and knowledge in HTML, CSS,
            Python, and Javascript, I can turn wireframes into visually appealing responsive websites.
            Currently, I am pursuing AWS Cloud Computing with ALX to increase my skill set.
        </p>
        <p>
            I love tech and I am very passionate about using my skills to solve problems and impact the
            world around me positively. I am a great team player, very dependable, and goal-oriented. I
            am a selfless individual who seeks to collaborate when necessary in attaining any set
            objective. Also, I can multitask and quickly adapt to changing environments.
        </p>
        <p>
            I am ready to use my skills in web development and cloud computing to help any organization
            attain its specified objective.
        </p>
    </div>
</template>

<style scoped>
    .intro-section{
        text-align: center;
    }

    .image-section{
        width: 250px;
        height: 250px;
        margin: 0 auto;
    }
    .image-section > img{
        width: inherit;
        height: inherit;
        border-radius: 50%;
    }

    .title{
        text-align: center;
        margin-top: 0px;
    }

    .bio{
       display: flex;
       flex-direction: column;
       place-items: center;
    }

    .bio > h2{
        margin-bottom: 0px;
    }

    .bio > p{
        margin-top: 0px;
    }

    @media only screen and (min-width: 600px) {
        
    }
</style>