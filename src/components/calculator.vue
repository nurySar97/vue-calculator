<template>
  <div class="calculator">
    <div class="calculator__inner">
      <h2 class="calculator__title">посчитайте прибыль</h2>
      <div class="calculator__subtitle">
        ДОБРИВО <span>ЭФФЕКТИВНЕЕ ХИМИИ</span>
      </div>
      
      <hr />

      <form class="calculator-form">
        <div class="calculator-form__item">
          <label for="" class="calculator-form__label">Выберите культуру</label>
          <select class="calculator-form__select">
            <option>Пшеница ≈ 3100 грн / т</option>
          </select>
        </div>

        <div class="calculator-form__item">
          <label for="" class="calculator-form__label">Урожайность, ц/га</label>
          <input class="calculator-form__input" type="text" />
        </div>

        <div class="calculator-form__item">
          <label for="" class="calculator-form__label"
            >Стоимость хим. удобрения, грн/га</label
          >
          <input class="calculator-form__input" type="text" />
        </div>

        <div class="calculator-form__item">
          <label for="" class="calculator-form__label"
            >Посевная площадь, га</label
          >
          <input class="calculator-form__input" type="text" />
        </div>
      </form>

      <hr />

      <div class="calculator__result-text">Прибыль от ДОБРИВА</div>
      <div class="calculator__result-amount">50 000</div>
      <div class="calculator__result-currency">грн</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Calculator",
};
</script>
