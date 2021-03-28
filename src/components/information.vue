<template>
  <div class="information">
    <div class="information_container">
      <div class="information_wrapper">
        <div class="information_column">
          <div class="information_item">
            <p class="information_title">Организаторам</p>
          </div>
          <div class="information_inner">
            <div class="information_link">
              <a href="" class="information_link_subtitle"
                >Документы организаторам</a
              >
            </div>
            <div class="information_item">
              <p class="information_list">Услуги организаторам</p>
            </div>
            <div class="information_item">
              <p class="information_list">Выставочные площади</p>
            </div>
            <div class="information_item">
              <p class="information_list">Рестораны и кафе</p>
            </div>
            <div class="information_item">
              <p class="information_list">Конгресс-центр</p>
            </div>
            <div class="information_item">
              <p class="information_list">Спорт-центр</p>
            </div>
          </div>
        </div>
        <div class="information_column">
          <div class="information_item">
            <p class="information_title">Экспонентам</p>
          </div>
          <div class="information_inner_one">
            <div class="information_item">
              <p class="information_list">Общие условия участия</p>
            </div>
            <div class="information_item">
              <p class="information_list">Услуги экспонентам</p>
            </div>
            <div class="information_item">
              <p class="information_list">Документы экспонентам</p>
            </div>
            <div class="information_item">
              <p class="information_list">Центр деловых контактов</p>
            </div>
            <div class="information_item">
              <p class="information_list">Забронировать гостиницу</p>
            </div>
          </div>
        </div>
        <div class="information_column">
          <div class="information_item">
            <p class="information_title">Посетителям</p>
          </div>
          <div class="information_inner_two">
            <div class="information_item">
              <p class="information_list">Сервисы</p>
            </div>
            <div class="information_item">
              <p class="information_list">
                Онлайн-регистрация <br />
                на мероприятие
              </p>
            </div>
            <div class="information_item">
              <p class="information_list">Забронировать гостиницу</p>
            </div>
            <div class="information_item">
              <p class="information_list">Центр деловых контактов</p>
            </div>
          </div>
        </div>
        <div class="information_column_footer">
          <div class="information_item">
            <p class="information_title">Прессе</p>
          </div>
          <div class="information_inner_tree">
            <div class="information_item">
              <p class="information_list">Аккредитация</p>
            </div>
            <div class="information_item">
              <p class="information_list">Пресс-служба</p>
            </div>
            <div class="information_item">
              <p class="information_list">Правила аккредитации</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Information",
};
</script>
<style lang="scss" scoped>
.information {
  width: 100%;
  height: 426px;
  background: #2378fc;
  &_container {
    display: flex;
    width: 100%;
    height: 100%;
    align-items: center;
    justify-content: center;
  }
  &_wrapper {
    display: flex;
    width: 1114px;
    height: 276px;
    justify-content: center;
  }
  &_column {
    display: flex;
    width: 18rem;
    height: 276px;
    align-items: center;
    flex-direction: column;
  }
  &_column_footer {
    display: flex;
    width: 14rem;
    height: 276px;
    padding-left: 1rem;
    align-items: center;
    flex-direction: column;
  }
  &_item {
    display: flex;
    width: 15rem;
    margin-top: 12px;
  }
  &_title {
    display: flex;
    height: 3rem;
    justify-content: flex-start;
    font-family: "Circe";
    font-style: normal;
    font-weight: 500;
    font-size: 30px;
    line-height: 130%;
    letter-spacing: -0.01em;
    color: #ffffff;
  }

  &_inner {
    display: flex;
    width: 15rem;
    margin-top: 1rem;
    flex-direction: column;
  }
  &_inner_one,
  &_inner_two,
  &_inner_tree {
    display: flex;
    width: 13.9rem;
    margin-top: 4px;
    flex-direction: column;
  }
  &_link {
    display: block;
  }
  &_link_subtitle {
    display: flex;
    overflow: hidden;
    font-family: "Circe";
    font-style: normal;
    font-weight: normal;
    text-decoration-line: underline;
    font-size: 16px;
    line-height: 135%;
    color: #ffc41e;
  }
  &_list {
    display: flex;
    overflow: hidden;
    font-family: "Circe";
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 135%;
    color: #ffffff;
  }
}
</style>
