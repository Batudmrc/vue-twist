<template>
  <div class="ga7">
    <div class="mini-cart obj-desktop">
      <div
        data-target="body"
        data-ready="mini-cart-ready"
        data-animate="mini-cart-animate"
        data-type="remove"
        class="ems-overlay mini-cart-overlay"
      ></div>
      <div
        data-target="body"
        data-ready="mini-cart-ready"
        data-animate="mini-cart-animate"
        data-type="toggle"
        class="
          ems-cart-trigger
          mini-cart-info
          header-height
          display-flex
          align-items-center
        "
      >
        <span class="qty shopping-cart-qty" id="lblUrunAdet">0</span
        ><span>SEPETİM</span>
      </div>
      <div class="mini-cart-sub absolute transition mini-cart-content">
        <span>
          <div class="sub-header">
            Sepet <span class="mcq m-lft-5"><i>0</i> Ürün</span>
            <a
              onclick="targetElement.clicked(this);"
              href="javascript:void(0);"
              data-target="body"
              data-ready="mini-cart-ready"
              data-animate="mini-cart-animate"
              data-type="remove"
              class="sub-close"
            >
              <svg class="icon-close">
                <use xlink:href="/Content/Styles/base/icons.svg#close"></use>
              </svg>
            </a>
          </div>
        </span>

        <div class="kutuSepet_urunYok" id="divKutuSepet_urunYok">
          <div
            class="
              message-empty-card
              align-center
              inline-block
              width100
              m-top-10
            "
          >
            <svg class="icon-basket m-rght-5">
              <use xlink:href="/Content/Styles/base/icons.svg#basket"></use>
            </svg>
            <p>Sepetin Henüz Boş!</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>