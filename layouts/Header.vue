<script></script>

<template>
  <div
    class="w-full h-8 px-4 flex justify-between items-center bg-[#242424]"
  >
    <div class="w-1/2 min-[737px]:w-1/3">
      <form class="flex flex-row">
        <label class="text-[#FFFFFF21] hidden min-[737px]:flex" for="city-select">Ваш город </label>
        <select
          class="text-[#FFFFFF99] bg-[#242424] appearance-none sm:px-4"
          name="city"
          id="city-select"
        >
          <option value="">Выберите город</option>
          <option value="petersburg">Сантк-Петербург</option>
          <option value="moscow">Москва</option>
          <option value="ekaterinburg">Екатеринбург</option>
          <option value="novosibirsk">Новосибирск</option>
        </select>
      </form>
    </div>

    <div class="w-1/3 hidden min-[737px]:flex justify-around">
      <a href=""><img src="/public/img/телеграмм.png" alt="telegram" /></a>
      <a href=""><img src="/public/img/вк.png" alt="vk" /></a>
      <a href=""><img src="/public/img/вайбер.png" alt="vaiber" /></a>
      <a href=""><img src="/public/img/ютуб.png" alt="youtube" /></a>
      <a href=""><img src="/public/img/инста 1.png" alt="instagram" /></a>
    </div>

    <div class="w-1/2 min-[737px]:w-1/3 flex justify-end">
      <img
        src="/public/img/icons8-положить-трубку.png"
        alt="phone"
        class="h-3.5 w-3 self-center"
      />
      <div class="text-[#FFFFFF99] pl-2 sm:pr-2">8 (800) 100 26 80</div>
      <div class="hidden min-[1060px]:flex flex-row text-[#FFFFFF99]">
       <p class="pr-2">ЕЖЕДНЕВНО</p>
       <p>10:00 - 20:00</p>   
      </div>
    </div>
  </div>
</template>
