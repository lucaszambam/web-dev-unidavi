<template>
    <div class="grid-table">
        <div class="a1">A1</div>
        <div class="a2">A2</div>
        <div class="a3">A3</div>
        <div class="b2">B2</div>
        <div class="b4">B4</div>
        <div class="c1">C1</div>
    </div>
    
</template>
  
<script>
export default {
    name: 'Exercise18',
}
</script>

<style scoped>
.grid-table {
    display: grid;
    grid-template-rows: 1fr 1fr 1fr;
    grid-template-columns: 1fr 1fr 1fr;
    border: 1px solid black;
    border-collapse: collapse;

}
.a1 {
    grid-row-start: 1;
    grid-row-end: 4;
}
.b4 {
    grid-row-start: 2;
    grid-row-end: 5;
}

.b2 {
    grid-row-start: 2;
    grid-row-end: 4;
}
.c1 {
    grid-column-start: 1;
    grid-column-end: 3;
}
.a1,.a2,.a3,.b2,.b4,.c1 {
    border: 1px solid black;
}
</style>