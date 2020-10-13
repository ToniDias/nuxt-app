<template>
  <div>
    <h1>Create an Event</h1>
  </div>
</template>
<script>
export default {
  head() {
    return {
      title: 'Create an Event', // <-- For our title tag
      meta: [
        {
          hid: 'description',
          name: 'description', // <-- for our meta description tag
          content: 'You can create a new event in your neighborhood',
        },
      ],
    }
  },
}
</script>
