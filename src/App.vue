<template>
  <div id="nav">
    <header class="header">
      <div class="wrapper menu">
        <div class="menu_start">
          <router-link
            to="/"
            class="menu_icons"
          >
            <img
              src="img/menu-logo.png"
              alt="logo"
            >
          </router-link>
          <a
            class="menu_icons"
            href="#"
          ><svg
            class="svg"
            width="27"
            height="28"
            viewBox="0 0 27 28"
            xmlns="http://www.w3.org/2000/svg"
          ><path d="M19.0596 17.6259C20.6713 15.8658 21.6282 13.6048 21.7698 11.2225C21.9113 8.84018 21.2288 6.48173 19.8369 4.54318C18.445 2.60463 16.4285 1.20404 14.126 0.576619C11.8234 -0.0508009 9.3751 0.13316 7.19217 1.09761C5.00923 2.06205 3.22463 3.74825 2.13804 5.87302C1.05145 7.9978 0.729054 10.4318 1.225 12.7661C1.72094 15.1005 3.00501 17.1932 4.86158 18.6927C6.71814 20.1922 9.03413 21.0072 11.4206 21.0009C13.673 21.004 15.8645 20.27 17.6606 18.9109L25.4086 26.7179C25.4941 26.807 25.5965 26.8781 25.7099 26.927C25.8232 26.9759 25.9452 27.0017 26.0686 27.0029C26.1923 27.0033 26.3148 26.9782 26.4283 26.9292C26.5419 26.8801 26.6441 26.8082 26.7286 26.7179C26.9025 26.537 26.9997 26.2958 26.9997 26.0449C26.9997 25.794 26.9025 25.5528 26.7286 25.3719L19.0596 17.6259ZM2.88662 10.5009C2.89946 8.81563 3.41094 7.17187 4.35659 5.77685C5.30224 4.38183 6.63972 3.29801 8.20044 2.662C9.76115 2.02599 11.4752 1.86627 13.1266 2.20298C14.7779 2.53969 16.2926 3.35775 17.4797 4.55404C18.6668 5.75033 19.4732 7.27129 19.7972 8.92519C20.1212 10.5791 19.9483 12.2919 19.3002 13.8476C18.6522 15.4034 17.5581 16.7325 16.1559 17.6674C14.7536 18.6023 13.1059 19.1011 11.4206 19.1009C9.14916 19.0901 6.97482 18.1784 5.37484 16.566C3.77486 14.9537 2.87998 12.7724 2.88662 10.5009Z" /></svg></a>
        </div>
        <nav class="menu_navigation">
          <ul class="menu_list">
            <li class="menu_icons">
              <a
                class="svg"
                href="#"
              ><svg
                width="32"
                height="23"
                viewBox="0 0 32 23"
                xmlns="http://www.w3.org/2000/svg"
              ><path d="M0 23V20.31H32V23H0ZM0 12.76V10.07H32V12.76H0ZM0 2.69V0H32V2.69H0Z" /></svg></a>
            </li>
            <li class="menu_icons to_disclose">
              <a
                class="svg"
                href="#"
              ><svg
                width="29"
                height="29"
                viewBox="0 0 29 29"
                xmlns="http://www.w3.org/2000/svg"
              ><path d="M14.5 19.937C19 19.937 22.656 15.464 22.656 9.968C22.656 4.472 19 0 14.5 0C13.3631 0.0217413 12.2463 0.303398 11.2351 0.823397C10.2239 1.34339 9.34507 2.08794 8.66602 3C7.12663 4.99573 6.30819 7.45381 6.34399 9.974C6.34399 15.465 10 19.937 14.5 19.937ZM14.5 1.813C18 1.813 20.844 5.472 20.844 9.969C20.844 14.466 17.998 18.125 14.5 18.125C11.002 18.125 8.15603 14.465 8.15503 9.969C8.15403 5.473 11 1.813 14.5 1.813ZM20.844 18.125C20.6036 18.125 20.373 18.2205 20.203 18.3905C20.033 18.5605 19.9375 18.7911 19.9375 19.0315C19.9375 19.2719 20.033 19.5025 20.203 19.6725C20.373 19.8425 20.6036 19.938 20.844 19.938C22.526 19.9399 24.1386 20.6088 25.3279 21.7982C26.5172 22.9875 27.1861 24.6 27.188 26.282C27.1875 26.5221 27.0918 26.7523 26.922 26.9221C26.7522 27.0918 26.5221 27.1875 26.282 27.188H2.71997C2.47985 27.1875 2.24975 27.0918 2.07996 26.9221C1.91016 26.7523 1.81449 26.5221 1.81396 26.282C1.81608 24.6001 2.48517 22.9877 3.67444 21.7985C4.86371 20.6092 6.47608 19.9401 8.15796 19.938C8.39824 19.938 8.62868 19.8425 8.79858 19.6726C8.96849 19.5027 9.06396 19.2723 9.06396 19.032C9.06396 18.7917 8.96849 18.5613 8.79858 18.3914C8.62868 18.2215 8.39824 18.126 8.15796 18.126C5.99541 18.1279 3.92201 18.9875 2.39258 20.5164C0.863144 22.0453 0.00264777 24.1185 0 26.281C0.000794067 27.0019 0.287502 27.693 0.797241 28.2027C1.30698 28.7125 1.99811 28.9992 2.71899 29H26.282C27.0027 28.9989 27.6936 28.7121 28.2031 28.2024C28.7126 27.6927 28.9992 27.0017 29 26.281C28.9974 24.1187 28.1372 22.0457 26.6083 20.5168C25.0793 18.9878 23.0063 18.1276 20.844 18.125Z" /></svg></a>
            </li>


            <Cart ref="cart" />
          </ul>
        </nav>
        <nav class="navigation_side_none">
          <!-- class="navigation_side" Для открытия навигации -->
          <div class="navigation_side_box">
            <p class="navigation_side_heading">
              MENU
            </P>
            <button class="navigation_side_button">
              <img
                src="img/close.svg"
                alt="close"
              >
            </button>
          </div>
          <ul>
            <li class="navigation_side_list pinktext">
              MEN
              <ul class="navigation_side_sublist">
                <li>Accessories</li>
                <li>Bags</li>
                <li>Denim</li>
                <li>T-Shirts</li>
              </ul>
            </li>
            <li class="navigation_side_list pinktext">
              WOMEN
              <ul class="navigation_side_sublist">
                <li>Accessories</li>
                <li>Jackets & Coats</li>
                <li>Polos</li>
                <li>T-Shirts</li>
                <li>Shirts</li>
              </ul>
            </li>
            <li class="navigation_side_list pinktext">
              KIDS
              <ul class="navigation_side_sublist">
                <li>Accessories</li>
                <li>Jackets & Coats</li>
                <li>Polos</li>
                <li>T-Shirts</li>
                <li>Shirts</li>
                <li>Bags</li>
              </ul>
            </li>
          </ul>
        </nav>
      </div>
    </header>

    <router-view />

    <footer class="footer">
      <div class="feature">
        <h2 class="hidden">
          Перечень преимуществ
        </h2>
        <div class="wrapper feature_content">
          <div class="feature_card">
            <img
              src="img/feature-delivery.png"
              alt="delivery"
            >
            <h3 class="feature_heading">
              Free Delivery
            </h3>
            <p class="feature_text">
              Worldwide delivery on all. Authorit tively morph next-generation innov tion with extensive models.
            </p>
          </div>

          <div class="feature_card">
            <img
              src="img/featute-sale.png"
              alt="sale"
            >
            <h3 class="feature_heading">
              Sales & discounts
            </h3>
            <p class="feature_text">
              Worldwide delivery on all. Authorit tively morph next-generation innov tion with extensive models.
            </p>
          </div>
          <div class="feature_card">
            <img
              src="img/feature-quality.png"
              alt="quality"
            >
            <h3 class="feature_heading">
              Quality assurance
            </h3>
            <p class="feature_text">
              Worldwide delivery on all. Authorit tively morph next-generation innov tion with extensive models.
            </p>
          </div>
        </div>
      </div>

      <div class="feedback">
        <div class="wrapper feedback_container">
          <div class="feedback_comments">
            <h2 class="hidden">
              Отзывы
            </h2>
            <img
              class="feedback_photo"
              src="img/photo.png"
              alt="photo"
            >
            <blockquote class="feedback_text">
              “Vestibulum quis porttitor dui! Quisque viverra nunc mi, <span style="font-style:italic"> a pulvinar purus condimentum“</span>
            </blockquote>
          </div>
          <section class="subscribe">
            <h2 class="subscribe_heading">
              SUBSCRIBE<br>FOR OUR NEWSLETTER AND PROMOTION
            </h2>
            <form
              class="subscribe_form"
              action="#"
            >
              <input
                class="subscribe_form_field"
                type="email"
                required
                placeholder="Enter Your Email"
              >
              <input
                class="subscribe_form_button"
                type="submit"
                value="Subscribe"
              >
            </form>
          </section>
        </div>
      </div>

      <div class="copyright">
        <div class="wrapper copyright_content">
          <p class="copyright_text">
            © 2021  Brand  All Rights Reserved.
          </p>
          <div class="social">
            <a
              class="social_icons"
              href="#"
              target="blank"
            ><i class="fab fa-facebook-f" /></a>
            <a
              class="social_icons"
              href="#"
              target="blank"
            ><i class="fab fa-instagram" /></a>
            <a
              class="social_icons"
              href="#"
              target="blank"
            ><i class="fab fa-pinterest-p" /></a>
            <a
              class="social_icons"
              href="#"
              target="blank"
            ><i class="fab fa-twitter" /></a>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import Cart from "@/components/Cart.vue";

export default {
  name: 'App',
    components: {
    Cart,
    }
}
</script>