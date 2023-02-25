<template>
  {{ timerNum }}
</template>

<script>

  export default {
    name: "StopWatch",
      data() {
          return {
              timerNum: 30
          }
      },

      watch: {

          timerCount: {
              handler(value) {

                  if (value > 0) {
                      setTimeout(() => {
                          this.timerNum--;
                      }, 1000);
                  }

              },
              immediate: true
          }

      }
  }

</script>