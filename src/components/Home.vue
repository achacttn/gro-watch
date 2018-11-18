<template>
    <div id="container">
        <div>Welcome to Grocery Watch Home page</div>
        <div id="testdiv1">1527 - ABDD - D8H2</div>
        <div id="testdiv2">9D02 - DK2N - NS88</div>
        <div>{{ this.testString }}</div>
    </div>
</template>

<script>
export default {
    name: 'Home',
    data(){
        return {
            testString: 'is this visible? lol'
        };
    },
    created(){
        // console.log(this.testString);
    }
}
</script>
