<script setup lang="ts"></script>

<template>
  <header class="header">
    <nav class="navbar">
      <div class="container">
        <div class="navbar-content d-flex justify-content-between">
          <div class="nav d-flex align-items-center">
            <div class="logo">
              <img
                src="../public/images/logo.svg"
                alt="logo"
                class="logo--svg"
              />
            </div>
              <div class="local-icon">
                <img
                  src="../public/images/geo.svg"
                  alt="local"
                  class="local--svg"
                />
              </div>
              <div class="d-flex flex-column">
                <p class="local--title">Яндекс Карты</p>
                <div class="d-flex align-items-center">
                  <img
                    src="../public/images/stars.svg"
                    alt="star"
                    class="star--svg"
                  />
                  <p class="number">5,0</p>
                </div>
                <p class="review">81 отзыв • 100 оценок</p>
              </div>
            </div>
          </div>
          <div class="burger">
            <div class="burger__item"></div>
            <div class="burger__item"></div>
            <div class="burger__item"></div>
          </div>

          <div class="nav--end d-flex align-items-center">
            <p class="address">
              Производство кухонь на заказ <br /><span class="span"
                >Анапа, ул. Крылова, д. 27</span
              >
            </p>
            <div class="d-flex">
              <img
                src="../public/images/whatsapp.svg"
                alt="icon"
                class="icon"
              />
              <img
                src="../public/images/telegram.svg"
                alt="icon"
                class="icon"
              />
            </div>
            <a href="tel:+7 (988)-311-77-88" class="phone-number"
              >+7 (988)-311-77-88</a
            >
            <button class="nav--btn">Заказать звонок</button>
          </div>
        </div>
    </nav>

    <div class="container">
      <div class="secure-items">
        <div class="secure--item d-flex align-items-center">
          <p class="secure--txt">
            Огромный выбор <br />
            бытовой техники
          </p>
          <img
            src="../public/images/secure.svg"
            alt="secure"
            class="secure--svg"
          />
        </div>
        <div class="secure--item1 d-flex align-items-center">
          <p class="secure--txt">
            Изысканный гарнитур<br />
            любого размера
          </p>
          <img
            src="../public/images/secure.svg"
            alt="secure"
            class="secure--svg"
          />
        </div>
        <div class="secure--item2 d-flex align-items-center">
          <p class="secure--txt">
            Выдающиеся <br />
            сорта древесины
          </p>
          <img
            src="../public/images/secure.svg"
            alt="secure"
            class="secure--svg"
          />
        </div>
      </div>
    </div>

    <div class="line--line">
      <div class="line"></div>
    </div>

    <div class="container">
      <div class="main">
        <h1 class="main--title">Изготовим роскошную дизайнерскую кухню</h1>
        <div class="price d-flex align-items-center">
          <img
            src="../public/images/wallet.svg"
            alt="wallet"
            class="price--img"
          />
          <p class="price--desc">
            Цена на 12-24% ниже, <br />
            <span class="price__span">чем у посредников</span>
          </p>
        </div>
        <div class="main-end">
          <p class="btn--title">Рассчитаем стоимость кухни-мечты</p>
          <img
            src="../public/images/pointer.svg"
            alt="pointer"
            class="pointer"
          />
          <button class="main--btn">Заказать расчёт</button>
        </div>
      </div>
    </div>
  </header>

  <div class="advantages__img">
    <img src="../public/images/kitchen.png" alt="" class="advantages--img" />
  </div>
  <section class="section__advantages">
    <div class="container">
      <div class="advantages">
        <div class="advantages-head">
          <h4 class="advantages--title">Наши преимущества</h4>
        </div>
        <div class="advantages__row row d-flex mt-5">
          <div class="col-12 col-xl-4 col-md-6 mt-4">
            <div class="advantages__block d-flex align-items-start">
              <img
                src="../public/images/иконка кухни.svg"
                alt="icon"
                class="advantages__block--icon"
              />
              <p class="advantages__block--text">
                C 2000 г на рынке <br />
                <span class="advantages__span"
                  >наши кухни выбрали 10 000+ семей</span
                >
              </p>
            </div>
          </div>
          <div class="col-12 col-xl-4 col-md-6 mt-4">
            <div class="advantages__block d-flex align-items-start">
              <img
                src="../public/images/icon calendar.svg"
                alt="icon"
                class="advantages__block--icon"
              />
              <p class="advantages__block--text">
                Сжатые сроки <br />
                <span class="advantages__span"
                  >изготовление кухни от 20 дней</span
                >
              </p>
            </div>
          </div>
          <div class="col-12 col-xl-4 col-md-6 mt-4">
            <div class="advantages__block d-flex align-items-start">
              <img
                src="../public/images/icon design projects.svg"
                alt="icon"
                class="advantages__block--icon"
              />
              <p class="advantages__block--text">
                Дизайн проект <br />
                <span class="advantages__span">бесплатно за 30 минут</span>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section__work">
    <div class="container">
      <div class="work__head">
        <h4 class="work--title">Посмотрите наши работы</h4>
      </div>

      <div class="dropdowns d-flex mt-4">
        <div class="drop">
          <button class="drop--btn">
          ПЛАНИРОВКА
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="21"
            height="9"
            viewBox="0 0 21 9"
            fill="none"
          >
            <path
              d="M10.5 8.5L0.540707 0.249998L20.4593 0.25L10.5 8.5Z"
              fill="#002B45"
            />
          </svg>
        </button>
        <button class="drop--btn">
          СТИЛЬ КУХНИ
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="21"
            height="9"
            viewBox="0 0 21 9"
            fill="none"
          >
            <path
              d="M10.5 8.5L0.540707 0.249998L20.4593 0.25L10.5 8.5Z"
              fill="#002B45"
            />
          </svg>
        </button>
        <button class="drop--btn">
          ЦВЕТ
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="21"
            height="9"
            viewBox="0 0 21 9"
            fill="none"
          >
            <path
              d="M10.5 8.5L0.540707 0.249998L20.4593 0.25L10.5 8.5Z"
              fill="#002B45"
            />
          </svg>
        </button>
        </div>
        
        <div class="work__button">
          <button class="work__btn">применить</button>
          <button class="work__btn">сбросить</button>
        </div>
        
      </div>

      <div class="work__row row mt-5">
        <div class="work__col col-12 col-lg-6 mb-4">
          <div class="work__block d-flex align-items-center">
          <div class="work--col">
            <div class="work__img">
              <img
                src="../public/images/col kitchen.png"
                alt=""
                class="work--img"
              />
              <div class="darkblue">
                <img src="../public/images/slider.png" alt="" class="slider" />
              </div>
            </div>
          </div>
          <div class="work--col">
            <div class="card">
              <div class="card--head">
                <h6 class="card--title">Кухня 097 минимализм</h6>
                <p class="card--sub">
                  Угловая белая кухня со столешницей под бетон.
                </p>
              </div>
              <div class="card__price d-flex justify-content-between mt-5">
                <p class="card__price--txt">
                  Эконом  <br /><span class="work--span">168 000 р.</span>
                </p>
                <p class="card__price--txt">
                  Стандарт  <br /><span class="work--span">217 000 р.</span>
                </p>
                <p class="card__price--txt">
                  Премиум <br /><span class="work--span">270 000 р.</span>
                </p>
              </div>
              <p class="width">
                Длина кухни: <span class="w--span">4900 мм</span>
              </p>

              <div class="card__btns mt-5">
                <button class="card--btn">Подробнее</button>
                <button class="card--btn">Расчет стоимости</button>
              </div>
            </div>
          </div>
        </div>
        </div>
        
        <div class="work__col col-12 col-lg-6 mb-4">
          <div class="work__block d-flex align-items-center">
          <div class="work--col">
            <div class="work__img">
              <img
                src="../public/images/col kitchen.png"
                alt=""
                class="work--img"
              />
              <div class="darkblue">
                <img src="../public/images/slider.png" alt="" class="slider" />
              </div>
            </div>
          </div>
          <div class="work--col">
            <div class="card">
              <div class="card--head">
                <h6 class="card--title">Кухня 097 минимализм</h6>
                <p class="card--sub">
                  Угловая белая кухня со столешницей под бетон.
                </p>
              </div>
              <div class="card__price d-flex mt-5">
                <p class="card__price--txt">
                  Эконом  <br /><span class="work--span">168 000 р.</span>
                </p>
                <p class="card__price--txt">
                  Стандарт  <br /><span class="work--span">217 000 р.</span>
                </p>
                <p class="card__price--txt">
                  Премиум <br /><span class="work--span">270 000 р.</span>
                </p>
              </div>
              <p class="width">
                Длина кухни: <span class="w--span">4900 мм</span>
              </p>

              <div class="card__btns mt-5">
                <button class="card--btn">Подробнее</button>
                <button class="card--btn">Расчет стоимости</button>
              </div>
            </div>
          </div>
        </div>
        </div>

        <div class="work__col col-12 col-lg-6 mb-4">
          <div class="work__block d-flex align-items-center">
          <div class="work--col">
            <div class="work__img">
              <img
                src="../public/images/col kitchen.png"
                alt=""
                class="work--img"
              />
              <div class="darkblue">
                <img src="../public/images/slider.png" alt="" class="slider" />
              </div>
            </div>
          </div>
          <div class="work--col">
            <div class="card">
              <div class="card--head">
                <h6 class="card--title">Кухня 097 минимализм</h6>
                <p class="card--sub">
                  Угловая белая кухня со столешницей под бетон.
                </p>
              </div>
              <div class="card__price d-flex mt-5">
                <p class="card__price--txt">
                  Эконом  <br /><span class="work--span">168 000 р.</span>
                </p>
                <p class="card__price--txt">
                  Стандарт  <br /><span class="work--span">217 000 р.</span>
                </p>
                <p class="card__price--txt">
                  Премиум <br /><span class="work--span">270 000 р.</span>
                </p>
              </div>
              <p class="width">
                Длина кухни: <span class="w--span">4900 мм</span>
              </p>

              <div class="card__btns mt-5">
                <button class="card--btn">Подробнее</button>
                <button class="card--btn">Расчет стоимости</button>
              </div>
            </div>
          </div>
        </div>
        </div>

        <div class="work__col col-12 col-lg-6 mb-4">
          <div class="work__block d-flex align-items-center">
          <div class="work--col">
            <div class="work__img">
              <img
                src="../public/images/col kitchen.png"
                alt=""
                class="work--img"
              />
              <div class="darkblue">
                <img src="../public/images/slider.png" alt="" class="slider" />
              </div>
            </div>
          </div>
          <div class="work--col">
            <div class="card">
              <div class="card--head">
                <h6 class="card--title">Кухня 097 минимализм</h6>
                <p class="card--sub">
                  Угловая белая кухня со столешницей под бетон.
                </p>
              </div>
              <div class="card__price d-flex mt-5">
                <p class="card__price--txt">
                  Эконом  <br /><span class="work--span">168 000 р.</span>
                </p>
                <p class="card__price--txt">
                  Стандарт  <br /><span class="work--span">217 000 р.</span>
                </p>
                <p class="card__price--txt">
                  Премиум <br /><span class="work--span">270 000 р.</span>
                </p>
              </div>
              <p class="width">
                Длина кухни: <span class="w--span">4900 мм</span>
              </p>

              <div class="card__btns mt-5">
                <button class="card--btn">Подробнее</button>
                <button class="card--btn">Расчет стоимости</button>
              </div>
            </div>
          </div>
        </div>
        </div>
      </div>
    </div>
  </section>

</template>

<style scoped></style>
