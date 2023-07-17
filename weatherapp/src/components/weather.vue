<script src="./weather.ts"></script>
<template>
    {{value}}
    <input type="text" v-model = "value"/><br/>
    <button @click="handleCheck">Check</button>

</template>