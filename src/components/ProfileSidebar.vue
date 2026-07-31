<template>
  <nav class="profile-sidebar-placeholder">
    <h3>Navigation</h3>
    <ul>
      <li>General Settings</li>
      <li>Profile</li>
      <li>Notifications</li>
    </ul>
  </nav>
</template>

<script setup>
// Sidebar logic will go here
</script>

<style scoped>
.profile-sidebar-placeholder {
  padding: 16px;
  background-color: #f9fafb;
  border: 1px dashed #d1d5db;
  border-radius: 8px;
}

ul {
  list-style: none;
  padding: 0;
  margin-top: 12px;
}

li {
  padding: 6px 0;
  color: #4b5563;
}
</style>