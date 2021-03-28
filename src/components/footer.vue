<template>
  <div class="footer">
    <div class="footer_container">
      <div class="footer_wrapper">
        <div class="footer_column">
          <div class="footer_inner">
            <p class="footer_header">О компании</p>
          </div>
          <div class="footer_item">
            <p class="footer_link">О нашей компании</p>
          </div>
          <div class="footer_item">
            <p class="footer_list">Вакансии</p>
          </div>
          <div class="footer_item">
            <p class="footer_list">Партнеры</p>
          </div>
          <div class="footer_item">
            <p class="footer_list">Контакты</p>
          </div>

          <div class="footer_block_column">
            <div class="footer_inner">
              <p class="footer_header">Организаторам</p>
            </div>
            <div class="footer_item">
              <p class="footer_list">Преимущества площадки</p>
            </div>
            <div class="footer_item">
              <p class="footer_list">Структура комплекса</p>
            </div>
            <div class="footer_item">
              <p class="footer_list">Онлайн-заявка на организацию</p>
            </div>
            <div class="footer_item">
              <p class="footer_list">Документы организаторам</p>
            </div>
          </div>
        </div>
        <div class="footer_column_one">
          <div class="footer_inner">
            <p class="footer_header">Экспонентам</p>
          </div>
          <div class="footer_item">
            <p class="footer_list">Общие условия участия</p>
          </div>
          <div class="footer_item">
            <p class="footer_list">Услуги экспонентам</p>
          </div>
          <div class="footer_item">
            <p class="footer_list">Документы экспонентам</p>
          </div>
          <div class="footer_item">
            <p class="footer_list">Забронировать гостиницу</p>
          </div>

          <div class="footer_block_column">
            <div class="footer_inner">
              <p class="footer_header">Посетителям</p>
            </div>
            <div class="footer_item">
              <p class="footer_list">Сервисы</p>
            </div>
            <div class="footer_item">
              <p class="footer_list">Онлайн-регистрация</p>
            </div>
            <div class="footer_item">
              <p class="footer_list">Забронировать гостиницу</p>
            </div>
            <div class="footer_item">
              <p class="footer_list">Центр деловых контактов</p>
            </div>
          </div>
        </div>
        <div class="footer_column_two">
          <div class="footer_inner">
            <p class="footer_header">Прессе</p>
          </div>
          <div class="footer_item">
            <p class="footer_list">Аккредитация</p>
          </div>
          <div class="footer_item">
            <p class="footer_list">Пресс-служба</p>
          </div>
          <div class="footer_item">
            <p class="footer_list">Правила аккредитации</p>
          </div>

          <div class="footer_block_column">
            <div class="footer_inner">
              <p class="footer_header">Приложение</p>
            </div>
            <div class="footer_wrap">
              <div class="footer_icon"></div>
              <div class="footer_icon_one"></div>
            </div>
          </div>
        </div>
        <div class="footer_column_tree">
          <div class="footer_inner">
            <p class="footer_header">Мы в соц. сетях</p>
          </div>
          <div class="footer_socials">
            <div class="footer_widget">
              <div class="footer_icon_youtube"></div>
            </div>
            <div class="footer_widget">
              <div class="footer_icon_vk"></div>
            </div>
            <div class="footer_widget">
              <div class="footer_icon_f"></div>
            </div>
            <div class="footer_widget">
              <div class="footer_icon_inst"></div>
            </div>
          </div>

          <div class="footer_block_column">
            <div class="footer_inner">
              <p class="footer_header">Подписка на новости</p>
            </div>
            <div class="footer_item">
              <p class="footer_list">
                Получайте все самые последние новости о мероприятиях в
                Экспофоруме.
              </p>
            </div>
            <div class="footer_block_input">
              <input
                type="text"
                class="footer_input"
                placeholder="Введите ваш e-mail"
              />
              <div class="footer_btn_chat"></div>
              <div class="footer_btn_chat_icon"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Footer",
};
</script>
<style lang="scss" scoped>
.footer {
  width: 100%;
  height: 476px;
  background: #30bcc9;
  position: relative;
  &_container {
    display: flex;
    width: 100%;
    justify-content: center;
  }
  &_wrapper {
    display: flex;
    width: 1114px;
    height: 476px;
    align-items: center;
  }
  &_column {
    display: flex;
    flex-direction: column;
    width: 14rem;
    margin-bottom: 1rem;
  }
  &_column_one {
    display: flex;
    flex-direction: column;
    width: 14rem;
    margin-left: 6rem;
    margin-bottom: 19px;
  }
  &_column_two {
    display: flex;
    flex-direction: column;
    width: 14rem;
    margin-left: 6rem;
    margin-bottom: 3.9rem;
  }
  &_column_tree {
    display: flex;
    flex-direction: column;
    width: 14rem;
    margin-left: 3rem;
    margin-bottom: 8.3rem;
  }

  &_block_column {
    margin-top: 2rem;
  }
  &_inner {
    margin-top: 1rem;
  }
  &_header {
    font-family: "Plumb";
    font-style: normal;
    font-weight: 500;
    font-size: 21px;
    line-height: 130%;
    letter-spacing: -0.01em;
    color: #ffffff;
  }
  &_item {
    margin-top: 1rem;
  }
  &_link {
    font-family: "Circe";
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 135%;
    text-decoration-line: underline;
    overflow: hidden;
    color: #ffc41e;
  }
  &_list {
    font-family: "Circe";
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 135%;
    color: #e0e0e0;
    overflow: hidden;
  }
  &_icon {
    width: 164px;
    height: 51px;
    margin-top: 1rem;
    background: url("../assets/img/block_footer/Group.png");
    background-size: cover;
  }
  &_icon_one {
    width: 164px;
    height: 47px;
    margin-top: 1rem;
    background: url("../assets/img/block_footer/Frame.png");
    background-size: cover;
  }
  &_hero {
    display: flex;
    width: 12rem;
  }
  &_socials {
    display: flex;
    justify-content: center;
  }
  &_widget {
    display: flex;
    justify-content: center;
  }
  &_icon_youtube {
    width: 35px;
    height: 25px;
    margin-top: 1rem;
    margin-right: 13px;
    background: url("../assets/img/block_footer/Vector (2).png");
    background-size: cover;
  }
  &_icon_vk {
    width: 44px;
    height: 25px;
    margin-top: 1rem;
    margin-left: 5px;
    background: url("../assets/img/block_footer/Vector (3).png");
    background-size: cover;
  }
  &_icon_f {
    width: 14px;
    height: 25px;
    margin-top: 1rem;
    margin-left: 5px;
    background: url("../assets/img/block_footer/Vector (4).png");
    background-size: cover;
  }
  &_icon_inst {
    width: 25px;
    height: 25px;
    margin-top: 1rem;
    background: url("../assets/img/block_footer/instagram.png");
    background-size: cover;
  }
  &_block_input {
    display: flex;
    margin-top: 1rem;
  }
  &_input {
    width: 600px;
    height: 40px;
    border: none;
  }
  input::placeholder {
    background: #ffffff;
    padding-left: 1rem;
  }
  &_btn_chat {
    width: 136px;
    height: 40px;
    background: #f6404f;
  }
  &_btn_chat_icon {
    width: 18px;
    height: 18px;
    margin-top: 13px;
    margin-left: 12rem;
    position: absolute;
    background: url("../assets/img/block_footer/Vector.png");
    background-size: cover;
  }
}
</style>
