---
title: Staff
layout: default
nav_order: 8
---
<style>
.staff-container {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
  margin-top: 1rem;
}

.staff-member {
  display: flex;
  align-items: center;
  gap: 1.25rem;
}

.staff-avatar {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
}

.staff-info {
  display: flex;
  flex-direction: column;
}

.staff-name {
  font-size: 1.25rem;
  font-weight: 600;
  margin: 0;
}

.staff-role {
  color: var(--color-space-grey-000, #666);
  margin: 0.2rem 0 0 0;
}
</style>

<div class="staff-container">

  <div class="staff-member">
    <img src="{{ '/assets/staff/claire.jpeg' | relative_url }}" alt="Claire Mathieu" class="staff-avatar">
    <div class="staff-info">
      <h3 class="staff-name">Claire Mathieu</h3>
      <p class="staff-role">Professor | Office Hours: TBD</p>
    </div>
  </div>

  <div class="staff-member">
    <img src="{{ '/assets/images/claire.jpeg' | relative_url }}" alt="Manas Korimilli" class="staff-avatar">
    <div class="staff-info">
      <h3 class="staff-name">Manas Korimilli</h3>
      <p class="staff-role">Head Teaching Assistant | Office Hours: TBD</p>
    </div>
  </div>

</div>
