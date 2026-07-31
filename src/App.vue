<template>
  <div class="container">
    <ProfileHeader/>
    <main class="settings-layout">
      <aside class="sidebar-slot">
        <ProfileSidebar />
      </aside>
      <section class="content-slot">
        <ProfileForm />
      </section>
    </main>
  </div>
</template>

<script setup>
import ProfileHeader from './components/ProfileHeader.vue'
import ProfileSidebar from './components/ProfileSidebar.vue'
import ProfileForm from './components/ProfileForm.vue'
</script>

<style scoped>
.subtitle {
  color: #6b7280;
  font-size: 14px;
  margin-top: 4px;
}

.settings-layout {
  display: grid;
  grid-template-columns: 240px 1fr;
  gap: 32px;
  background: #ffffff;
  border-radius: 12px;
  border: 1px solid #e5e7eb;
  padding: 24px;
}

@media (max-width: 768px) {
  .settings-layout {
    grid-template-columns: 1fr;
  }
}
</style>