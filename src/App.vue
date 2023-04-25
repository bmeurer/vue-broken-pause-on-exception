<script>
export default {
  methods: {
    handleClick(event) {
      throw new Error("Don't press the button!");
    }
  }
}
</script>

<template>
  <h1>Demo Vue app for broken pause on exception</h1>

  <div>
    <button type="button" @click="handleClick">Press me!</button>
  </div>
</template>
