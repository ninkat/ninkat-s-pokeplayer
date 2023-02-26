<template>
  <div class="container">
    <myHeader title = "Study Logs" />
    <myTasks :tasks="tasks"/>
  </div>
</template>

<script>
import myHeader from '../components/Header.vue'
import myTasks from '../components/Tasks.vue'
import SplashPage from '../components/SplashPage.vue'

export default {
  name: 'App',
  components: {
    myHeader,
    myTasks,
    SplashPage,
  },
  data() {
    return {
      tasks: []
    }
  },
  created() {
    this.tasks = [
      {
        id:1,
        text: 'January 83, 1486',
        day: '11:36',
        reminder: true,
      },
      {
        id:2,
        text: 'February 25, 2023',
        day: '14:53',
        reminder: true
      },
      {
        id:3,
        text: 'July 9, 2007',
        day: '35:42',
        reminder: true
      },
      {
        id:4,
        text: 'March 15, 2086',
        day: '1:03:05',
        reminder: true
      },
      {
        id:5,
        text: 'December 22, 2022',
        day: '53:12',
        reminder: true
      }
    ]
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400&display=swap');
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: 'Poppins', sans-serif;
  color:#237d3e;
}
.container {
  
}
.btn {
  display: inline-block;
  background: #000;
  color: #ffffff;
  border: none;
  padding: 10px 20px;
  margin: 5px;
  border-radius: 5px;
  cursor: pointer;
  text-decoration: none;
  font-size: 15px;
  font-family: inherit;
}
.btn:focus {
  outline: none;
}
.btn:active {
  transform: scale(0.98);
}
.btn-block {
  display: block;
  width: 100%;
}
</style>