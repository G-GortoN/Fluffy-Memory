<template>
  <div class="home">
    <div class="container mt-5">
      <div class="row">
        <div class="col-md-6">
          <h1>Welcome to Pet Services</h1>
          <p>Experience the best pet care services for your beloved companions.</p>
        </div>
        <div class="col-md-6">
          <!-- Add an image or any other content related to pets here -->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  components: {
  }
}
</script>

<style scoped>
/* Add any custom styles specific to the home page here */
.home {
  background-color: #F9F9F9;
  padding: 50px;
}

.title {
  font-size: 36px;
  font-weight: bold;
  color: #333;
}

.description {
  font-size: 18px;
  color: #666;
  margin-top: 20px;
}
</style>