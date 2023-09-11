<template>
  <div class="about">
    <div class="segment">
      <h1>About me</h1>
      🏳️‍⚧️Trans girl in Senior High, love programming and art. <br />Girlfriend is <bold>Anemarrhena asphodeloide</bold>.
    </div>
  </div>
</template>

<style>
.about {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
  }
}

@media (max-width: 1023px) {
  .about {
    margin-top: 20px;
  }
}

bold {
  font-weight: bold;
}

.segment {
  padding: 18px;
  border-radius: 6px;
  background-color: var(--color-segment);
}</style>
