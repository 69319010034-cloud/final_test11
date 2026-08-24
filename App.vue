<template>
<div class="container">
<h1>{{ studentName }}</h1>
</div>
</template>
<script>
export default {
data() {
return {
studentName: "กมลชนก ศรสันติ์" // แก้เป็นชื่อของตนเอง
};
},
};
</script>
<style>
.container {
width: 100vw;
height: 100vh;
background-color: skyblue;
display: flex;
align-items: center;
justify-content: center;
}
</style>
