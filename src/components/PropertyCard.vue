<template>
    <div>
      <div @mouseover=true class="cards">
  <img :src="property.image" alt="properties">
  <h1>{{property.title}}</h1>
  <p style="font-style:italic; font-size:20px">{{property.location}}</p>
  <div class="specifications">
  <span><font-awesome-icon icon="fa-regular fa-bed-empty" /></span>
  <p>{{property.specifications.bedrooms}}</p>
  <p>{{property.specifications.bathrooms}}</p>
  <p>{{property.specifications.garage}}</p>
  <p>{{property.specifications.size}}</p>
  </div>
  </div>   
    </div>
</template>
<script>
export default {
    props:["property"]
}
</script>
<style>
  .cards{
    border:2px solid;
    width: 300px;
    }
  
  .cards img{
    width:19rem;
    height: 15rem;
    object-fit:cover;
    overflow: hidden;
  } 
  .specifications{
    display:flex;
    flex:wrap;
  }  
</style>