<template>
    <div>
<p>
    Full Name:{{ firstName() }}
</p>
    <label for="">firstName</label>
    <input type="text" v-model="firstName" > 
<p>
    <label for="LastName"></label>
    <input type="text" v-model="lastname" >
</p>
    </div>
</template>

<script>
    export default {
        name: "ComputeView"
        data(){
            return{
                firstName: Mark
                LastName: Mumi
            }
        },
        methods: {
            fullname() {
                
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>