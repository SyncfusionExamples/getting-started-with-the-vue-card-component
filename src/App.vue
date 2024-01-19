<script setup>

</script>

<template>
<div class="container">
    <div class="e-card e-card-horizontal">
        <div class="e-card-image"></div>  
        <div class="e-card-stacked"> 
        <div class="e-card-header">
            <div class="e-card-header-image profile"></div>
            <div class="e-card-header-caption">
                <div class="e-card-title">Laura Chauhan</div>
                <div class="e-card-sub-title">Sales Coordinator</div>
            </div>
            </div>
        <div class="e-card-separator"></div>
        <div class="e-card-content">
            Laura Chauhan received a BA in psychology from the University of Washington.
            She has also completed a course in Business French. She reads and writes French.  
        </div>
        <div class="e-card-actions e-card-vertical">
            <button class="e-card-btn">Like</button>
            <button class="e-card-btn">Subscribe</button>
        </div>
       </div>  
    </div>

</div>
</template>

<style scoped>
@import '../node_modules/@syncfusion/ej2-base/styles/material.css';
@import '../node_modules/@syncfusion/ej2-vue-layouts/styles/material.css';
.container
{
    margin:50px auto 0; 
    width:500px; 
    height:700px;
}
.e-card-header-image.profile
{
      background-image: url('../src/assets/profile.jpg');
    height: 60px !important;
    width: 60px !important;
}
.e-card-image
{
    background-image: url('../src/assets/sales.jpg');
    
}
</style>