<template>
  <h1>JOBS PAGES KWA</h1>

  <div v-for="job in jobs" :key="job.id" class="jobs">
    <h2>{{ job.title }}</h2>
  </div>

</template>

<script>
export default {
  data(){
    return{
      jobs: [
        {id:"1",title:"PJ Manager",detail:"creative coder project manager"},
        {id:"2",title:"Web Developer",detail:"creative coder Web Developing"},
        {id:"3",title:"Graphic Designer",detail:"creative coder Graphic Designing"}
      ]
    }
  }

}
</script>

<style>
.jobs{
  color: crimson;
}
</style>