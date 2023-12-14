<template>
    <div>
        <h1>Skills</h1>
        <ul>
            <li class="green" v-for="skill in skills" :key="skill.id">
                {{ skill.name }} - {{ skill.yearsOfExperience }} years
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    data() {
        return {
            skills: [
                { id: 1, name: 'JavaScript', yearsOfExperience: 7 },
                { id: 2, name: 'HTML5', yearsOfExperience: 7 },
                { id: 3, name: 'CSS', yearsOfExperience: 7 },
                { id: 4, name: 'JQuery', yearsOfExperience: 7 },
                { id: 5, name: 'Knockout.js', yearsOfExperience: 7 },
                { id: 6, name: 'Bootstrap', yearsOfExperience: 7 },
                { id: 7, name: 'Gulp', yearsOfExperience: 7 },
                { id: 8, name: 'React', yearsOfExperience: 1 },
                { id: 9, name: 'Vue.js', yearsOfExperience: 1 },
                { id: 10, name: 'Angular', yearsOfExperience: 1 },
                { id: 11, name: 'Python', yearsOfExperience: 1 },
                { id: 12, name: 'C#', yearsOfExperience: 1 },
                { id: 13, name: 'C++', yearsOfExperience: 1 },
                { id: 14, name: 'C', yearsOfExperience: 10 },
                { id: 15, name: 'Visual Basic', yearsOfExperience: 2 },
                { id: 16, name: 'SQL', yearsOfExperience: 1 },
                { id: 17, name: 'PHP', yearsOfExperience: 1 },
                { id: 18, name: 'MySQL', yearsOfExperience: 1 },
                { id: 19, name: 'Git', yearsOfExperience: 7 },
                { id: 20, name: 'GitHub', yearsOfExperience: 7 },
                { id: 21, name: 'GoogleMaps API', yearsOfExperience: 7 },
                { id: 22, name: 'Jasmine', yearsOfExperience: 7 },
                { id: 23, name: 'Node.js', yearsOfExperience: 7 },
                { id: 24, name: 'RESTful API', yearsOfExperience: 7 },
                { id: 25, name: 'JSON', yearsOfExperience: 7 },
                { id: 26, name: 'AJAX', yearsOfExperience: 7 },
                { id: 27, name: 'XML', yearsOfExperience: 7 },
                { id: 28, name: 'GitLab', yearsOfExperience: 1 },
                { id: 29, name: 'WordPress', yearsOfExperience: 5 },

            ]
        };
    }
};
</script>
