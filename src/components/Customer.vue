<template>
<h3>Hello Customer {{name}}</h3>
</template>

<script>
export default{
    name:'Customer',
    props : {
        name:{type:String,required:true}
        age:{type:String,required:true}
}
}

</script>

<style>

</style>