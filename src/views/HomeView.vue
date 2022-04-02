<script>


export default {
    data() {
        return {
            message: "Hello World! Welcome to VueJS"
        };
    },
}
</script>

<template>
    <div class="container">
      <div class="text-center">
        <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />
        <h1>{{ message }}</h1>
      </div>
    </div>
</template>

<style>

.news{
  text-align: center;
}

.super{
  display:flex;
  flex-direction:row;
  flex-wrap:wrap;
  justify-content: center;
  }

.article{
  position: relative;
   height:500px;
   width: 250px;
   margin-right:20px;
   margin-top:20px;
   border:2px solid rgb(232, 234, 237);
   border-radius: 12px;
   }

img{
    width:100%;
    height: 150px;
    }

.title{
  font-weight:600;
  margin-top: 15px;
  }

.bottom-color{
    height: 10px;
    width: 100%;
    background-color:rgb(92,192,146);
    color:rgb(92,192,146);
    border-radius:900px;
    position: absolute;
    bottom: 0px;  
}

form{
  margin-top:30px;
  display:flex;
  justify-content: center;
  flex-direction: column;
}

#search{
  width:50% !important;
  margin-left: 300px;
  flex-grow: 0;
}
</style>