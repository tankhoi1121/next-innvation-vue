<template>
  <div id="vue_index">
    <h1>Frist Name: {{firstName}}</h1>
    <h2>Last Name: {{lastName}}</h2>
    <h3>Location: {{location}}</h3>
  </div>
</template>
<script>
module.exports = {
  data: function() {
    return {
      firstName: "Khoi",
      lastName: "Bruce",
      location: "49CA"
    };
  }
};
</script>