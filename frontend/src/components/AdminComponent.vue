<template>
  <div v-if="isAuthorized" class="admin-container"></div>

  <!-- กรณีที่ไม่ได้รับอนุญาต -->
  <div v-else class="unauthorized">
    <h2>Access Denied</h2>
    <p>You are not authorized to access this page.</p>
  </div>
</template>
<script>
</script>
    
    <style scoped>
.admin-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 40px 20px;
  background-color: #f4f4f4;
  border-radius: 10px;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
}

.unauthorized {
  text-align: center;
  padding: 40px;
}

.admin-title {
  text-align: center;
  font-size: 3rem;
  margin-bottom: 40px;
  color: #2c3e50;
}

.admin-actions {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}

.action-card {
  background-color: #3498db;
  color: white;
  padding: 20px;
  text-align: center;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.action-card:hover {
  background-color: #2980b9;
}

.unauthorized h2 {
  color: red;
}

.unauthorized p {
  color: gray;
}
</style>
    