<template>
    <div class="project-grid">
        <div v-for="project in projects" :key="project.id" class="project-thumbnail">
            <img :src="project.thumbnail" alt="Project Thumbnail" />
            <div class="project-info">
                <h3>{{ project.name }}</h3>
                <p>{{ project.description }}</p>
            </div>
            <div class="project-links">
                <a :href="project.liveSite" target="_blank">Live Site</a>
                <a :href="project.githubRepo" target="_blank">GitHub Repo</a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'ProjectsView',
    data() {
        return {
            projects: [
            {
                    id: 1,
                    name: "Coding the little things",
                    description: "When I first learned how to use GoogleMaps API I was excited to see what I could do with it. I decided to share how to use the API with this website.",
                    thumbnail: "..\\assets\\code.png",
                    liveSite: "http://turtle-head.github.io/Coding-the-little-things/",
                    githubRepo: "http://turtle-head.github.io/Coding-the-little-things/"
                },
                {
                    id: 2,
                    name: "Bugged",
                    description: "A clone of Frogger, the popular game from the 80s. This game was built using HTML5, CSS, and JavaScript using Canvas. The game is fully functional and can be played by clicking the link below.",
                    thumbnail: "..\\assets/bugged-min.png",
                    liveSite: "http://turtle-head.github.io/Bugged/",
                    githubRepo: "https://github.com/Turtle-Head/Bugged"
                },
                {
                    id: 3,
                    name: "CatClicker",
                    description: "An early project that taught me how to use mouse clicks. Included in this project is an admin button to change thing with each cat picture.",
                    thumbnail: "..\\assets/catClicker-min.png",
                    liveSite: "http://turtle-head.github.io/CatClicker/",
                    githubRepo: "https://github.com/Turtle-Head/CatClicker"
                },
                {
                    id: 4,
                    name: "Gelp",
                    description: "A map website that uses GoogleMaps API to show chosen locations and their services.",
                    thumbnail: "..\\assets/gelp-min.png",
                    liveSite: "http://turtle-head.github.io/Project5/",
                    githubRepo: "https://github.com/Turtle-Head/Project5"
                },
                {
                    id: 5,
                    name: "FeedReader",
                    description: "A project that uses Jasmine to test a feed reader.",
                    thumbnail: "..\\assets\feedreader-min.png",
                    liveSite: "http://turtle-head.github.io/FeedReader-P6/",
                    githubRepo: "https:/github.com/Turtle-Head/FeedReader-P6"
                },
                 {
                    id: 6,
                    name: "Cleanup",
                    description: "A Multi-Page website that uses HTML, and CSS. The site inclues a mailto form.",
                    thumbnail: "..\\assets\\cleanup.jpg",
                    liveSite: "https://turtle-head.github.io/CleanUp/index.html",
                    githubRepo: "https://github.com/Turtle-Head/CleanUp"
                },
                {
                    id: 7,
                    name: "Calculator V2",
                    description: "A Calcuator App written in C#",
                    thumbnail: "..\\assets\\calc1.png",
                    liveSite: "https://github.com/Turtle-Head/CalculatorV2",
                    githubRepo: "https://github.com/Turtle-Head/CalculatorV2"
                },
                {
                    id: 8,
                    name: "Calculator V6",
                    description: "A Calcuator App written in Visual Basic",
                    thumbnail: "..\\assets\\gelp-min.png",
                    liveSite: "https://github.com/Turtle-Head/Calculator-v6",
                    githubRepo: "https://github.com/Turtle-Head/Calculator-v6"
                },
                {
                    id: 9,
                    name: "AirBus",
                    description: "A Airline Reservation App written in Visual Basic with a SQL database.",
                    thumbnail: "..\\assets\\AirBus.png",
                    liveSite: "https://github.com/Turtle-Head/AirBub",
                    githubRepo: "https://github.com/Turtle-Head/AirBub"
                },
                {
                    id: 10,
                    name: "BattleShip",
                    description: "A BattleShip clone of the popular boardgame. Written in C# with a SQL database.",
                    thumbnail: "..\\assets\\BS3.png",
                    liveSite: "https://github.com/Turtle-Head/BattleShip",
                    githubRepo: "https://github.com/Turtle-Head/BattleShip"
                },
                {
                    id: 11,
                    name: "Dog",
                    description: "An object oriented program written in C#.",
                    thumbnail: "..\\assets\\Kingdom.png",
                    liveSite: "https://github.com/Turtle-Head/Dog/tree/main",
                    githubRepo: "https://github.com/Turtle-Head/Dog/tree/main"
                },
                {
                    id: 12,
                    name: "Club",
                    description: "An App designed to track attendance for a club. Written in C# with a SQL database.",
                    thumbnail: "..\\assets\\Club.png",
                    liveSite: "https://github.com/Turtle-Head/Club",
                    githubRepo: "https://github.com/Turtle-Head/Club"
                }
            ]
        };
    }
};
</script>
    <div class="project-grid">
        <div v-for="project in project" :key="project.id" class="project-thumbnail">
            <img :src="project.thumbnail" alt="Project Thumbnail" />
            <div class="project-info">
                <h3>{{ project.name }}</h3>
                <p>{{ project.description }}</p>
            </div>
            <div class="project-links">
                <a :href="project.liveSite" target="_blank">Live Site</a>
                <a :href="project.githubRepo" target="_blank">GitHub Repo</a>
            </div>
<template>
    <div class="project-grid">
        <div v-for="project in project" :key="project.id" class="project-thumbnail">
            <img :src="project.thumbnail" alt="Project Thumbnail" />
            <div class="project-info">
                <h3>{{ project.name }}</h3>
                <p>{{ project.description }}</p>
            </div>
            <div class="project-links">
                <a :href="project.liveSite" target="_blank">Live Site</a>
                <a :href="project.githubRepo" target="_blank">GitHub Repo</a>
            </div>
        </div>
    </div>
</template>

<script>
<template>
    <div class="project-grid">
        <div v-for="project in projects" :key="project.id" class="project-thumbnail">
            <img :src="project.thumbnail" alt="Project Thumbnail" />
            <div class="project-info">
                <h3>{{ project.name }}</h3>
                <p>{{ project.description }}</p>
            </div>
            <div class="project-links">
                <a :href="project.liveSite" target="_blank">Live Site</a>
                <a :href="project.githubRepo" target="_blank">GitHub Repo</a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            projects: [
                {
                    id: 1,
                    name: "Coding the little things",
                    description: "When I first learned how to use GoogleMaps API I was excited to see what I could do with it. I decided to share how to use the API with this website.",
                    thumbnail: "https://turtle-head.github.io/Portfolio/img/code.png",
                    liveSite: "http://turtle-head.github.io/Coding-the-little-things/",
                    githubRepo: "http://turtle-head.github.io/Coding-the-little-things/"
                },
                {
                    id: 2,
                    name: "Bugged",
                    description: "A clone of Frogger, the popular game from the 80s. This game was built using HTML5, CSS, and JavaScript using Canvas. The game is fully functional and can be played by clicking the link below.",
                    thumbnail: "https://turtle-head.github.io/Portfolio/img/bugged-min.png",
                    liveSite: "http://turtle-head.github.io/Bugged/",
                    githubRepo: "https://github.com/Turtle-Head/Bugged"
                },
                {
                    id: 3,
                    name: "CatClicker",
                    description: "An early project that taught me how to use mouse clicks. Included in this project is an admin button to change thing with each cat picture.",
                    thumbnail: "https://turtle-head.github.io/Portfolio/img/catClicker-min.png",
                    liveSite: "http://turtle-head.github.io/CatClicker/",
                    githubRepo: "https://github.com/Turtle-Head/CatClicker"
                },
                {
                    id: 4,
                    name: "Gelp",
                    description: "A map website that uses GoogleMaps API to show chosen locations and their services.",
                    thumbnail: "https://turtle-head.github.io/Portfolio/img/gelp-min.png",
                    liveSite: "http://turtle-head.github.io/Project5/",
                    githubRepo: "https://github.com/Turtle-Head/Project5"
                },
                {
                    id: 5,
                    name: "FeedReader",
                    description: "A project that uses Jasmine to test a feed reader.",
                    thumbnail: "https://turtle-head.github.io/Portfolio/img/feedreader-min.png",
                    liveSite: "http://turtle-head.github.io/FeedReader-P6/",
                    githubRepo: "https://github.com/Turtle-Head/FeedReader-P6"
                },
                {
                    id: 6,
                    name: "Cleanup",
                    description: "A Multi-Page website that uses HTML, and CSS. The site inclues a mailto form.",
                    thumbnail: "https://turtle-head.github.io/Portfolio/img/water-1761027.jpg",
                    liveSite: "https://turtle-head.github.io/CleanUp/index.html",
                    githubRepo: "https://github.com/Turtle-Head/CleanUp"
                },
                {
                    id: 7,
                    name: "Calculator V2",
                    description: "A Calcuator App written in C#",
                    thumbnail: "https://turtle-head.github.io/Portfolio/img/calcV2.png",
                    liveSite: "https://github.com/Turtle-Head/CalculatorV2",
                    githubRepo: "https://github.com/Turtle-Head/CalculatorV2"
                },
                {
                    id: 8,
                    name: "Calculator V6",
                    description: "A Calcuator App written in Visual Basic",
                    thumbnail: "https://turtle-head.github.io/Portfolio/img/CalcV6.png",
                    liveSite: "https://github.com/Turtle-Head/Calculator-v6",
                    githubRepo: "https://github.com/Turtle-Head/Calculator-v6"
                },
                {
                    id: 9,
                    name: "AirBus",
                    description: "A Airline Reservation App written in Visual Basic with a SQL database.",
                    thumbnail: "https://turtle-head.github.io/Portfolio/img/AirBus.png",
                    liveSite: "https://github.com/Turtle-Head/AirBub",
                    githubRepo: "https://github.com/Turtle-Head/AirBub"
                },
                {
                    id: 10,
                    name: "BattleShip",
                    description: "A BattleShip clone of the popular boardgame. Written in C# with a SQL database.",
                    thumbnail: "https://turtle-head.github.io/Portfolio/img/BS3.png",
                    liveSite: "https://github.com/Turtle-Head/BattleShip",
                    githubRepo: "https://github.com/Turtle-Head/BattleShip"
                },
                {
                    id: 11,
                    name: "Dog",
                    description: "An object oriented program written in C#.",
                    thumbnail: "https://turtle-head.github.io/Portfolio/img/Kingdom.png",
                    liveSite: "https://github.com/Turtle-Head/Dog/tree/main",
                    githubRepo: "https://github.com/Turtle-Head/Dog/tree/main"
                },
                {
                    id: 12,
                    name: "Club",
                    description: "An App designed to track attendance for a club. Written in C# with a SQL database.",
                    thumbnail: "https://turtle-head.github.io/Portfolio/img/Club.png",
                    liveSite: "https://github.com/Turtle-Head/Club",
                    githubRepo: "https://github.com/Turtle-Head/Club"
                },
            ]
        };
    }
};
</script>

<style>
.project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}

.project-thumbnail {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.project-thumbnail img {
    width: 100%;
    max-width: 300px;
    height: auto;
}

.project-info {
    margin-top: 10px;
}

.project-info h3 {
    margin-bottom: 5px;
}

.project-links {
    margin-top: 10px;
}

.project-links a {
    margin-right: 10px;
}
</style>
