<script setup></script>

<template>
  <div class="card">
    <img src="../assets/images/image-qr-code.png" alt="" />
    <div class="card__body">
      <h2>Improve your front-end skills by building projects</h2>
      <div>
        Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.card {
  max-width: 20rem;
  height: 31rem;
  background-color: var(--color-white);
  box-shadow: 0 1.25rem 1.25rem rgba(0, 0, 0, 0.0476518);
  border-radius: 1.25rem;

  img {
    width: 100%;
    border-radius: 10px;
    padding: 1rem;
  }

  &__body {
    padding: 0 1rem 2.5rem 1rem;

    h2 {
      color: var(--text-header);
      font-size: 1.375rem;
      font-style: normal;
      font-weight: 700;
      line-height: 28px;
      margin-bottom: 1rem;
    }
  }
}
</style>
