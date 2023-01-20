<template>
<div class="head">
  <div class="container mx-auto">
    <div class="flex justify-between mx-auto py-3.5 items-center"> 
      <div class="mx-auto">
        <img class="w-1/6" src="../assets/images/logo.png" alt="">
      </div>
      <div class="flex mx-auto cursor-pointer font-medium">
        <a class="mx-5 hover:text-mainred">Главная</a>
        <a class="mx-5 hover:text-mainred">Услуги</a>
        <a class="mx-5 hover:text-mainred">О компании</a>
        <a class="mx-5 hover:text-mainred">Документы</a>
        <a class="mx-5 hover:text-mainred">Контакты</a>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'HeaderSet',
  props: {
    msg: String
  }
}
</script>

