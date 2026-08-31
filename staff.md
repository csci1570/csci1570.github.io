---
title: Staff
layout: default
nav_order: 8
---
<style>
.staff-container {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  margin-top: 1rem;
}

.staff-member {
  display: flex;
  align-items: flex-start;
  gap: 1.5rem;
}

.staff-avatar {
  width: 200px; /* Adjust image width as needed */
  height: auto;  /* Maintains aspect ratio */
  border-radius: 8px; /* Optional: adds subtle rounded corners; set to 0px for sharp corners */
  object-fit: cover;
  flex-shrink: 0;
}

.staff-info {
  display: flex;
  flex-direction: column;
}

.staff-name {
  font-size: 1.5rem;
  font-weight: 600;
  margin: 0 0 0.5rem 0;
}

.staff-role {
  color: var(--color-space-grey-000, #666);
  margin: 0;
  line-height: 1.5;
}
</style>

<div class="staff-container">

  <div class="staff-member">
    <img src="{{ '/assets/staff/claire.jpg' | relative_url }}" alt="Claire Mathieu" class="staff-avatar">
    <div class="staff-info">
      <h3 class="staff-name">Claire Mathieu</h3>
      <p class="staff-role">Professor | Office Hours: TBD</p>
    </div>
  </div>

  <div class="staff-member">
    <img src="{{ '/assets/staff/manas.jpg' | relative_url }}" alt="Manas Korimilli" class="staff-avatar">
    <div class="staff-info">
      <h3 class="staff-name">Manas Korimilli</h3>
      <p class="staff-role">HTA | Office Hours: TBD</p>
    </div>
  </div>

  <div class="staff-member">
    <img src="{{ '/assets/staff/sunny.jpg' | relative_url }}" alt="Sunny Xu" class="staff-avatar">
    <div class="staff-info">
      <h3 class="staff-name">Sunny Xu</h3>
      <p class="staff-role">UTA | Office Hours: TBD</p>
    </div>
  </div>

</div>
