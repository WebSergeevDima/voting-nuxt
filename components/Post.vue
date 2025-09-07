<template>
  <div class="post">
      <div class="post__header">
        <div class="post__logo"><Icon name="icons:logo" size="24" />PurpleSchool</div>
        <div class="header__days-last">4 дня назад</div>
      </div>
    <h2 class="post__title">Добавить функцию голосования</h2>
    <p class="post__content">
      Попробовать добавить в приложение функцию голосования, которая позволит определить, какая фича более полезна, а какая нет. После добавления поста появляется...
    </p>
    <div class="post__footer">
      <div class="post__footer-thumbs">
        <button class="post__footer-thumb">10 <Icon name="icons:thumbs-up" size="18" /></button>
        <button class="post__footer-thumb">1 <Icon name="icons:thumbs-down" size="18" /></button>
      </div>
      <div class="post__footer-actions">
        <button class="button"><Icon name="icons:delete"/></button>
        <button class="button button__edit"><Icon name="icons:edit"/>Изменить</button>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
  .post {

  }

  .post__header {
    display: flex;
    gap: 17px;
    align-items: center;
  }

  .post__logo {
    display: flex;
    align-items: center;
    gap: 8px;
    color: var(--color-gray-dark);
    font-size: 14px;
    font-style: normal;
    font-weight: 300;
    line-height: normal;
  }

  .header__days-last {
    color: var(--color-gray-light);
    font-size: 14px;
    font-style: normal;
    font-weight: 300;
    line-height: normal;
  }

  .post__title {
    color: var(--color-dark);
    font-size: 22px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
  }

  .post__content {
    color: var(--color-gray-dark);
    font-size: 16px;
    font-style: normal;
    font-weight: 300;
    line-height: 24px;
  }

  .post__footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .post__footer-thumbs {
    display: flex;
    align-items: center;
    gap: 13px;
  }

  .post__footer-thumb {
    display: flex;
    align-items: center;
    gap: 6px;
    color: var(--color-gray-dark);
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    border: 0;
    background: none;
    cursor: pointer;
  }

  .post__footer-actions {
    display: flex;
    align-items: center;
    gap: 20px;
  }

  .button {
    border: 0;
    background: none;
    cursor: pointer;
  }

  .button__edit {
    display: flex;
    align-items: center;
    gap: 8px;
    color: var(--color-gray-dark);
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
  }
</style>