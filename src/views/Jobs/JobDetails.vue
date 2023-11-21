<template>
<h1>Job Details Pages</h1>
<p> The job id is {{ id }}</p>
    </template>
    
    <script>
    
    export default {
        props: ['id'],
        data(){
            return{
                id: this.$route.params.id
            }
        }


   
    }
    </script>
    