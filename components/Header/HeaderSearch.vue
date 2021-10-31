<template>
  <div class="ga5">
    <div class="mini-search ems-search ems-search-activeted">
      <div
        data-target="body"
        data-ready="mini-search-ready"
        data-animate="mini-search-animate"
        data-type="remove"
        class="ems-overlay mini-search-overlay"
      ></div>

      <div
        class="
          mini-search-info
          ems-search-trigger
          obj-desktop
          header-height
          display-flex
          align-items-center
        "
        id="plhAramaHeader"
      >
        <span>ARA</span>
      </div>

      <div class="mini-search-sub absolute transition">
        <span>
          <a
            class="sub-close"
            href="javascript:void(0);"
            data-target="body"
            data-ready="mini-search-ready"
            data-animate="mini-search-animate"
            data-type="remove"
          >
            <svg class="icon-close obj-desktop">
              <use xlink:href="/Content/Styles/base/icons.svg#close"></use>
            </svg>
            <svg class="icon-drop-left obj-mobile">
              <use
                xlink:href="/Content/Styles/base/icons.svg#drop-left"
              ></use></svg
          ></a>
        </span>

        <div class="form">
          <div class="form-inner">
            <div
              class="
                mini-search-input
                display-flex
                justify-between
                flex-field-wrap
              "
            >
              <div class="field field-single">
                <div class="form-label obj-desktop" id="plhFreeLabel1">
                  <span></span>
                </div>
                <div class="form-obj search-input ems-search-input">
                  <input
                    id="txtARM_KEYWORD"
                    name="txtARM_KEYWORD"
                    type="text"
                    maxlength="55"
                    autocomplete="off"
                    data-max="3"
                    value=""
                    placeholder="Arama yapmak için tıklayınız"
                    class="ems-styler-activeted act-iStyler"
                  />

                  <div
                    class="mini-search-btn ems-search-submit-button"
                    id="plhBtnAra"
                  >
                    <a class="btnDefault btnArama" href="javascript:void(0);">
                      <span>
                        <svg class="icon-search">
                          <use
                            xlink:href="/Content/Styles/base/icons.svg#search"
                          ></use></svg
                      ></span>
                    </a>
                  </div>

                  <div
                    class="searchSuggestDiv ems-search-results"
                    id="search_suggest"
                  ></div>
                </div>
              </div>
            </div>
            <div class="field no-result" rel="lbfSonuc0"></div>
            <div class="field popular-search-words-append">
              <div class="popular-search-words" banner-id="id-18012">
                <div class="ems-section-wrapper">
                  <div class="ems-section-inner">
                    <div class="ems-section-title">POPÜLER ARAMALAR</div>
                  </div>
                </div>
                <div
                  class="swiper-container not-trigger"
                  data-duration="0"
                  data-swiper="widgetAuto"
                  data-total="$prmDataUriQty$"
                >
                  <div class="swiper-inner">
                    <ul class="swiper-wrapper">
                      <li class="swiper-slide sticky">
                        <a target="_self" href="/arama?q=ayakkabi" rel=" "
                          >Ayakkabı
                        </a>
                      </li>
                      <li class="swiper-slide sticky">
                        <a target="_self" href="/arama?q=elbise" rel=" "
                          >Elbise
                        </a>
                      </li>
                      <li class="swiper-slide sticky">
                        <a target="_self" href="/arama?q=aksesuar" rel=" "
                          >Aksesuar
                        </a>
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>