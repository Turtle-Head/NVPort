<template>
    <div>
        <h2 class="green">Skills</h2>
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
                { id: 4, name: 'jQuery', yearsOfExperience: 7 },
                { id: 5, name: 'Knockout', yearsOfExperience: 7 },
                { id: 6, name: 'Bootstrap', yearsOfExperience: 7 },
                { id: 7, name: 'Gulp', yearsOfExperience: 7 },
                { id: 8, name: 'React', yearsOfExperience: 1 },
                { id: 9, name: 'Next', yearsOfExperience: 1 },
                { id: 10, name: 'Angular', yearsOfExperience: 1 },
                { id: 11, name: 'Python', yearsOfExperience: 1 },
                { id: 12, name: 'C#', yearsOfExperience: 1 },
                { id: 13, name: 'C++', yearsOfExperience: 1 },
                { id: 14, name: 'C', yearsOfExperience: 10 },
                { id: 15, name: 'Visual Basic', yearsOfExperience: 2 },
                // Add more skills here
            ]
        };
    }
};
</script>
