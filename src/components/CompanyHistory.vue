<!-- src/components/CompanyHistory.vue -->
<template>
    <section class="company-history">
      <h2>История компании</h2>
      <div class="content-block">
        <img src="@/assets/images/slide1.jpg" alt="Company Image" class="content-image" />
        <p class="content-text">
          «VALFEX» — один из самых успешно развивающихся брендов на российском рынке инженерной сантехники.
          Мы готовы разделить свой успех и приглашаем к сотрудничеству монтажные, строительные, торговые
          организации, индивидуальных предпринимателей – всех, чей бизнес нуждается в поставках надежного
          оборудования и материалов.
        </p>
      </div>
  
      <div class="content-block reverse">
        <img src="@/assets/images/slide2.jpg" alt="Company Image" class="content-image" />
        <p class="content-text">
          «VALFEX» — один из самых успешно развивающихся брендов на российском рынке инженерной сантехники.
          Мы готовы разделить свой успех и приглашаем к сотрудничеству монтажные, строительные, торговые
          организации, индивидуальных предпринимателей – всех, чей бизнес нуждается в поставках надежного
          оборудования и материалов.
        </p>
      </div>
  
      <p class="additional-info">
        В 2014 году состоялось открытие полимерного завода. На нем выпускают трубопроводную продукцию из полипропилена.
        <br /><br />
        В 2018 году был открыт арматурный завод полного цикла. На нем выпускают комплектующие для полимерного трубопровода
        и фасонные изделия трубопроводной арматуры.
        <br /><br />
        Заводы оснащены современным итальянским и немецким оборудованием. Испытания продукции проводятся в заводских и
        независимых лабораториях, аккредитованных в ГОСТ. Сертификаты и протоколы испытаний соответствуют международным
        требованиям и стандартам.
        <br /><br />
        На предприятиях работает более 7 000 высококвалифицированных сотрудников и позволяет без труда укомплектовать
        необходимыми специалистами производство.
        <br /><br />
        Мы устанавливаем гарантию на изделия до 10 лет, потому что уверены в качестве продукции VALFEX.
      </p>
  
      <h2>Сотрудничество</h2>
      <p class="cooperation-text">
        «VALFEX» — один из самых успешно развивающихся брендов на российском рынке инженерной сантехники.
        Мы готовы разделить свой успех и приглашаем к сотрудничеству монтажные, строительные, торговые
        организации, индивидуальных предпринимателей – всех, чей бизнес нуждается в поставках надежного
        оборудования и материалов.
      </p>
    </section>
  </template>
  
  <script>
  export default {
    name: 'CompanyHistory',
  };
  </script>
  
  <style scoped>
  .company-history {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    color: #333;
  }
  
  .company-history h2 {
    font-size: 24px;
    margin-bottom: 20px;
  }
  
  .content-block {
    display: flex;
    align-items: flex-start;
    gap: 20px;
    margin-bottom: 20px;
  }
  
  .content-block.reverse {
    flex-direction: row-reverse;
  }
  
  .content-image {
    width: 200px; /* Задайте ширину изображения */
    height: auto;
    background-color: #d8d8d8; /* Цвет-заполнитель для изображения */
  }
  
  .content-text {
    flex: 1;
    font-size: 16px;
    line-height: 1.6;
  }
  
  .additional-info,
  .cooperation-text {
    font-size: 16px;
    line-height: 1.6;
    margin-bottom: 20px;
  }
  </style>
  