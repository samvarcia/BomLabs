<style>
  .Modal {
    position: relative;
  }
  .Modal-overlay {
    background-color: rgba(0, 0, 0, 0.7);
    position: fixed;
    text-align: center;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    z-index: 8;
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
  }
</style>

<div class="Modal">
  <div class="Modal-overlay" />
  <slot />
</div>
