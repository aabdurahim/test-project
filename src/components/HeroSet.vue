<template>
  <div class="main w-full">
    <div class="container mx-auto my-24 flex justify-between">
      <div class="mx-auto ml-8 w-2/3">
        <p class="font-nunito text-4xl mt-10 mb-6 font-medium leading-10">
          Мы предоставляем комплексные <span class="text-mainred">логистические решения</span>
        </p>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </p>
        <button class="py-4 px-9 rounded-full font-semibold bg-mainred border-2 border-mainred text-white mt-6 hover:bg-white hover:text-mainred hover:border-2 border-mainred">Связаться с нами</button>
        <div class="mt-24 flex justify-between">
          <div class="w-1/3 mr-10">
            <p class="text-4xl text-mainred font-normal text-center">200+</p>
            <div class="border-t-2 border-black my-2.5 py-2.5">
              <p class="text-center">Активных клиентов</p>
            </div>
          </div>
          <div class="w-1/3 mr-10">
            <p class="text-4xl text-mainred font-normal text-center">500+</p>
            <div class="border-t-2 border-black my-2.5 py-2.5">
              <p class="text-center">Успешных операций</p>
            </div>
          </div>
          <div class="w-1/3">
            <p class="text-4xl text-mainred font-normal text-center">1000+</p>
            <div class="border-t-2 border-black my-2.5 py-2.5">
              <p class="text-center">Описание позиции</p>
            </div>
          </div>
        </div>
      </div>
      <div>
        <img src="../assets/images/Frame1.png" alt="">
      </div>
    </div>
    <div class="bg-main pb-36">
      <div class="w-full py-20 bg-main relative">
        <div class="flex justify-between">
          <img src="../assets/images/Frame20.png" alt="" class="absolute top-10 left-10">
          <div class="calculator container w-5/6 mx-auto py-12 bg-white rounded-3xl">
            <div class="mx-16">
              <p class="text-2xl text-mainred">Онлайн калькулятор</p>
              <div class="first-input flex justify-between">
                <div class="my-2">
                  <p class="text-mainred my-2">Имя</p>
                  <input type="text" placeholder="Ваше имя" class="bg-main text-black p-5 border-none">
                </div>
                <div class="my-2">
                  <p class="text-mainred my-2">Телефон</p>
                  <input type="text" placeholder="Ваш номер" class="bg-main text-black p-5 border-none">
                </div>
                <div class="my-2">
                  <p class="text-mainred my-2">E-mail</p>
                  <input type="text" placeholder="Ваш e-mail" class="bg-main text-black p-5 border-none">
                </div>
                <div class="my-2">
                  <p class="text-mainred my-2">Вес, кг</p>
                  <input type="text" placeholder="0 кг" class="bg-main text-black p-5 border-none">
                </div>
                <div class="my-2">
                  <p class="text-mainred my-2">Объем, м³</p>
                  <input type="text" placeholder="0 м³" class="bg-main text-black p-5 border-none">
                </div>
              </div>
              <div class="flex input-text justify-between items-center">
                <div class="my-2">
                  <p class="text-mainred my-2">Данные о грузе</p>
                  <input type="text" placeholder="Тип груза" class="bg-main text-black p-5 border-none">
                </div>
                <div class="my-2">
                  <p class="text-mainred my-2">Откуда</p>
                  <input type="text" placeholder="Название страны и города" class="bg-main text-black p-5 border-none">
                </div>
                <div class="my-2">
                  <p class="text-mainred my-2">Куда</p>
                  <input type="text" placeholder="Название страны и города" class="bg-main text-black p-5 border-none">
                </div>
                <button class="py-4 px-10 rounded-full font-semibold bg-mainred border-2 border-mainred text-white mt-6 hover:bg-white hover:text-mainred hover:border-2 border-mainred">Связаться с нами</button>
              </div>
            </div>
          </div>
          <img src="../assets/images/Frame21.png" alt="" class="absolute top-20 right-20">
        </div>
      </div>
      <div class="container mt-60">
        <div class="ml-28">
          <p class="text-6xl font-semibold">Наши <span class="text-mainred">услуги</span></p>
          <div class="flex justify-between py-8 items-center">
            <p class="text-base w-2/3">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex commodo.</p>
            <button class="py-4 px-10 rounded-full font-semibold bg-mainred border-2 border-mainred text-white mt-6 hover:bg-white hover:text-mainred hover:border-2 border-mainred">Заказать услугу</button>
          </div>
          <div class="flex">
            <div class="w-1/3 bg-white rounded-3xl p-10 mr-7">
              <p class="text-3xl font-semibold"><span class="text-mainred">Железнодорожные </span>перевозки</p>
              <p class="py-3.5">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
              <div class="flex justify-between relative">
                <img src="../assets/images/Train.png" alt="">
                <img src="../assets/images/Frame22.png" class="w-1/3 absolute top-24 right-1" alt="">
              </div>
            </div>
            <div class="w-1/3 bg-white rounded-3xl p-10 mr-7">
              <p class="text-3xl font-semibold"><span class="text-mainred">Автомобильные </span>перевозки</p>
              <p class="py-3.5">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
              <div class="flex justify-between relative">
                <img src="../assets/images/Truck.png" alt="" class="pr-3">
                <img src="../assets/images/Frame22.png" class="w-1/3 absolute top-24 right-1" alt="">
              </div>
            </div>
            <div class="w-1/3 bg-white rounded-3xl p-10">
              <p class="text-3xl font-semibold"><span class="text-mainred">Авиа <br> </span>перевозки</p>
              <p class="py-3.5">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
              <div class="flex justify-between relative">
                <img src="../assets/images/Plane.png" alt="">
                <img src="../assets/images/Frame22.png" class="w-1/3 absolute top-24 right-1" alt="">
              </div>
            </div>
          </div>
          <div class="flex mt-7">
            <div class="w-1/3 bg-white rounded-3xl p-10 mr-7">
              <p class="text-3xl font-semibold">3<span class="text-mainred">PL</span></p>
              <p class="py-3.5">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
              <div class="flex justify-between relative">
                <img src="../assets/images/Freight.png" alt="" class="py-10">
                <img src="../assets/images/Frame22.png" class="w-1/3 absolute top-32 right-1" alt="">
              </div>
            </div>
            <div class="w-1/3 bg-white rounded-3xl p-10 mr-7">
              <p class="text-3xl font-semibold">Перевозки <span class="text-mainred">автомобилей </span></p>
              <p class="py-3.5">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
              <div class="flex justify-between relative">
                <img src="../assets/images/Car.png" alt="">
                <img src="../assets/images/Frame22.png" class="w-1/3 absolute top-24 right-1" alt="">
              </div>
            </div>
            <div class="w-1/3 bg-white rounded-3xl p-10">
              <p class="text-3xl font-semibold"><span class="text-mainred">Таможенные </span>операции</p>
              <p class="py-3.5">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
              <div class="flex justify-between relative">
                <img src="../assets/images/Docs.png" alt="" class="py-5">
                <img src="../assets/images/Frame22.png" class="w-1/3 absolute top-24 right-1" alt="">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container flex mx-auto py-20 pl-20">
      <div class="form w-5/12 rounded-3xl p-10 z-10">
        <p class="text-center text-2xl font-semibold pb-2.5">У вас есть вопросы? <span class="text-mainred">Свяжитесь с нами</span></p>
        <p class="text-center">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commod.</p>
        <form action="">
          <input type="text" placeholder="Ваше имя*" class="rounded-full p-3.5 px-5 my-5 bg-main w-full">
          <input type="text" placeholder="Ваш телефон*" class="rounded-full p-3.5 px-5 mb-5 bg-main w-full">
          <input type="text" placeholder="Ваш e-mail*" class="rounded-full p-3.5 px-5 mb-5 bg-main w-full">
          <input type="text" placeholder="Опишите вашу проблему*" class="rounded-full p-3.5 px-5 mb-5 bg-main w-full">
          <button class="py-4 px-14 rounded-full font-semibold bg-mainred border-2 border-mainred text-white mt-6 hover:bg-white hover:text-mainred hover:border-2 border-mainred">Отправить</button>
        </form>
      </div>
      <img src="../assets/images/Frame23.png" alt="" class="w-1/2 absolute right-32">
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroSet',
  props: {
    msg: String
  }
}


</script>