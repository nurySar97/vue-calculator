<template>
  <section class="benefit">
    <div class="benefit__container container">
      <div class="benefit__inner">
        <div class="benefit__item">
          <div class="benefit__advantages">
            <div class="benefit__img">
              <div class="benefit__img-inner">
                <div class="benefit__img-wrapper">
                  <img
                    class="benefit__img-oil"
                    src="./../assets/images/oil.png"
                    alt=""
                  />
                </div>
              </div>
            </div>

            <div class="benefit__content">
              <!-- benefit cards start -->
              <div class="benefit__cards">
                <div class="benefit__card">
                  <h3 class="benefit__card-title">ПРИРОСТ УРОЖАЯ</h3>
                  <div class="benefit__card-subtitle">
                    в сравнении с химическим удобрением
                  </div>
                  <div class="benefit__card-amount">30%-250%</div>
                </div>

                <div class="benefit__card">
                  <h3 class="benefit__card-title">ЭКОНОМИЯ</h3>
                  <div class="benefit__card-subtitle">
                    химических удобрений в хозяйстве
                  </div>
                  <div class="benefit__card-amount">до 70%</div>
                </div>

                <div class="benefit__card">
                  <h3 class="benefit__card-title">РОСТ КОРНЕВОЙ</h3>
                  <div class="benefit__card-subtitle">
                    системы растений при использовании
                  </div>
                  <div class="benefit__card-amount">в 3-10раз</div>
                </div>
              </div>
              <!-- benefit cards end -->

              <!-- learn more start -->
              <section class="learnmore">
                <h2 class="learnmore__title">
                  УЗНАЙТЕ <br />
                  О НАГРО БОЛЬШЕ!
                </h2>
                <button class="learnmore__btn">УЗНАТЬ БОЛЬШЕ</button>
              </section>
              <!-- learn more end -->
            </div>
          </div>
        </div>
        <div class="benefit__item benefit__item--calc">
          <Calculator />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Calculator from "./calculator.vue";
export default {
  name: "benefit",
  components: {
    Calculator,
  },
};
</script>
