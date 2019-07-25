<template>
    <div>
         <!-- <h1>This is {{$route.params.username}} page</h1> -->
         <h1>This is  {{username}} page</h1>
    </div>
</template>
<script>
export default {
    props:['username']
}
</script>
