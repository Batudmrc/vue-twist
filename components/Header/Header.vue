<template>
  <header class="site-header sticky">
    <div class="site-header-grid display-grid align-items-center">
      <div class="ga1">
        <div class="header-logo obj-desktop align-center">
          <h1 class="inline-block">
            <a href="/"
              ><img
                alt="Twist"
                title="Twist"
                src="https://img2-twist.mncdn.com/Twist/frontend/images/logo.svg"
            /></a>
          </h1>
        </div>
      </div>

      <div class="ga2">
        <div
          class="
            header-mobile
            display-flex
            justify-between
            align-items-center
            obj-mobile
          "
        >
          <div class="ga0 hs-back">
            <a class="back-page" href="javascript:history.go(-1)">
              <svg class="icon-drop-left">
                <use
                  xlink:href="/Content/Styles/base/icons.svg#drop-left"
                ></use></svg
            ></a>
          </div>

          <div class="ga1">
            <a
              class="open-search ems-search-trigger"
              href="javascript:void(0);"
            >
              <svg class="icon-search">
                <use
                  xlink:href="/Content/Styles/base/icons.svg#search"
                ></use></svg
            ></a>
          </div>

          <div class="ga2">
            <a class="header-mobile-logo" href="/"
              ><img
                alt="Twist"
                title="Twist"
                src="https://img2-twist.mncdn.com/Twist/frontend/images/logo.svg" /></a
            ><a href="/"> <div class="mobilePageTitle"></div></a>
          </div>

          <div class="ga3">
            <a
              class="go-cart display-flex justify-between align-items-center"
              href="/sepet"
            >
              <svg class="icon-basket">
                <use
                  xlink:href="/Content/Styles/base/icons.svg#basket"
                ></use></svg
              ><b class="qty shopping-cart-qty">0</b></a
            >
          </div>

          <div class="ga4">
            <a
              data-target="body"
              data-ready="menu-ready"
              data-animate="menu-animate"
              data-type="toggle"
              class="open-menu"
              href="javascript:void(0);"
            >
              <svg class="icon-menu">
                <use
                  xlink:href="/Content/Styles/base/icons.svg#menu"
                ></use></svg
            ></a>
          </div>
        </div>

        <div class="menu ems-menu main-menu ems-menu-activeted">
          <div class="menu-top obj-mobile">
            <div class="menu-basket">
              <a
                class="go-cart display-flex justify-between align-items-center"
                href="/sepet"
              >
                <svg class="icon-basket">
                  <use
                    xlink:href="/Content/Styles/base/icons.svg#basket"
                  ></use></svg
                ><b class="qty shopping-cart-qty">0</b></a
              >
            </div>

            <div
              data-target="body"
              data-ready="menu-ready"
              data-animate="menu-animate"
              data-type="remove"
              class="menu-close"
            >
              <a class="menu-overlay" href="javascript:void(0)">
                <svg class="icon icon-close">
                  <use
                    xlink:href="/Content/Styles/base/icons.svg#close"
                  ></use></svg
              ></a>
            </div>
          </div>

          <ul class="lvl-1 display-flex">

            <li class="sub-items" style="order: 0">
              <a
                target="_self"
                class="header-height relative align-items-center display-flex"
                href="/Products/NewProducts"
                rel=" "
                >YEPYENİ
              </a>
              <div class="sub absolute transition animated fadeIn faster">
                <ul class="lvl-2 columnCount2">
                  <li class="" style="order: 0">
                    <a target="_self" class="" href="/en-yeniler" rel=" "
                      >Yepyeni <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="" style="order: 1">
                    <a target="_self" class="" href="/elbise-modelleri" rel=" "
                      >Elbise <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="" style="order: 2">
                    <a target="_self" class="" href="/bluz-modelleri" rel=" "
                      >Bluz <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="" style="order: 3">
                    <a
                      target="_self"
                      class=""
                      href="/kadin-pantolon-modelleri"
                      rel=" "
                      >Pantolon <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="" style="order: 4">
                    <a target="_self" class="" href="/ayakkabi" rel=" "
                      >Ayakkabı <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="" style="order: 5">
                    <a target="_self" class="" href="/aksesuar" rel=" "
                      >Aksesuar <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="" style="order: 6">
                    <a target="_self" class="" href="/ultra-cool" rel=" "
                      >ULTRA COOL <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="" style="order: 7">
                    <a target="_self" class="" href="/yeni-akim" rel=" "
                      >YENİ AKIM <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="" style="order: 8">
                    <a target="_self" class="" href="/dama-oyunu" rel=" "
                      >DAMA OYUNU <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="" style="order: 9">
                    <a target="_self" class="" href="/yeni-normal" rel=" "
                      >YENİ NORMAL
                      <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="" style="order: 10">
                    <a target="_self" class="" href="/parizyen-akim" rel=" "
                      >PARİZYEN AKIM
                      <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="" style="order: 11">
                    <a target="_self" class="" href="/yesil-otesi" rel=" "
                      >YEŞİL VE ÖTESİ
                      <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                </ul>
              </div>
            </li>
            <li class="sub-items" style="order: 1">
              <a
                target="_self"
                class="header-height relative align-items-center display-flex"
                href="/Products/Collection"
                rel=" "
                >KOLEKSİYON
              </a>

              <div class="sub absolute transition animated fadeIn faster">
                <ul class="lvl-2 columnCount3">
                  <li class="showSubLVL sub-items" style="order: 0">
                    <a
                      target="_self"
                      class=""
                      href="javascript:void(0);"
                      rel=" "
                      >Temalar <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >

                    <ul class="lvl-3 columnCount1">
                      <li class="" style="order: 1">
                        <a target="_self" class="" href="/ultra-cool" rel=" "
                          >ULTRA COOL
                        </a>
                      </li>
                      <li class="" style="order: 2">
                        <a target="_self" class="" href="/yeni-akim" rel=" "
                          >YENİ AKIM
                        </a>
                      </li>
                      <li class="" style="order: 3">
                        <a target="_self" class="" href="/parizyen-akim" rel=" "
                          >PARİZYEN AKIM
                        </a>
                      </li>
                      <li class="" style="order: 4">
                        <a target="_self" class="" href="/dama-oyunu" rel=" "
                          >DAMA OYUNU
                        </a>
                      </li>
                      <li class="" style="order: 5">
                        <a target="_self" class="" href="/yeni-normal" rel=" "
                          >YENİ NORMAL
                        </a>
                      </li>
                      <li class="" style="order: 6">
                        <a target="_self" class="" href="/yesil-otesi" rel=" "
                          >YEŞİL VE ÖTESİ
                        </a>
                      </li>
                      <li class="" style="order: 7">
                        <a
                          target="_self"
                          class=""
                          href="/haftanin-favorisi"
                          rel=" "
                          >BEST SELLERS
                        </a>
                      </li>
                    </ul>
                  </li>
                  <li class="showSubLVL sub-items" style="order: 1">
                    <a target="_self" class="" href="/giyim" rel=" "
                      >Giyim <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >

                    <ul class="lvl-3 columnCount2">
                      <li class="" style="order: 0">
                        <a
                          target="_self"
                          class=""
                          href="/elbise-modelleri"
                          rel=" "
                          >Elbise
                        </a>
                      </li>
                      <li class="" style="order: 1">
                        <a
                          target="_self"
                          class=""
                          href="/kadin-triko-kazak"
                          rel=" "
                          >KAZAK
                        </a>
                      </li>
                      <li class="" style="order: 2">
                        <a
                          target="_self"
                          class=""
                          href="/kadin-sweatshirt-modelleri"
                          rel=" "
                          >SWEATSHIRT
                        </a>
                      </li>
                      <li class="" style="order: 3">
                        <a
                          target="_self"
                          class=""
                          href="/kot-pantolon-modelleri"
                          rel=" "
                          >JEAN
                        </a>
                      </li>
                      <li class="" style="order: 4">
                        <a
                          target="_self"
                          class=""
                          href="/kadin-gomlek-modelleri"
                          rel=" "
                          >GÖMLEK
                        </a>
                      </li>
                      <li class="" style="order: 4">
                        <a
                          target="_self"
                          class=""
                          href="/bluz-modelleri"
                          rel=" "
                          >BLUZ
                        </a>
                      </li>
                      <li class="" style="order: 5">
                        <a
                          target="_self"
                          class=""
                          href="/etek-modelleri"
                          rel=" "
                          >ETEK
                        </a>
                      </li>
                      <li class="hideSubLVL" style="order: 7">
                        <a
                          target="_self"
                          class=""
                          href="/kadin-yelek-modelleri"
                          rel=" "
                          >Yelek
                        </a>
                      </li>
                      <li class="" style="order: 8">
                        <a
                          target="_self"
                          class=""
                          href="/kadin-ceket-modelleri"
                          rel=" "
                          >CEKET
                        </a>
                      </li>
                      <li class="" style="order: 9">
                        <a
                          target="_self"
                          class=""
                          href="/kadin-tshirt-modelleri"
                          rel=" "
                          >T-SHIRT
                        </a>
                      </li>
                      <li class="" style="order: 10">
                        <a
                          target="_self"
                          class=""
                          href="/tulum-modelleri"
                          rel=" "
                          >TULUM
                        </a>
                      </li>
                      <li class="" style="order: 11">
                        <a
                          target="_self"
                          class=""
                          href="/kadin-pantolon-modelleri"
                          rel=" "
                          >PANTOLON
                        </a>
                      </li>
                      <li class="" style="order: 12">
                        <a
                          target="_self"
                          class=""
                          href="/kadin-jogger-pantolon-modelleri"
                          rel=" "
                        >
                          JOGGER PANTOLON
                        </a>
                      </li>
                      <li class="" style="order: 13">
                        <a target="_self" class="" href="/kadin-sort" rel=" ">
                          ŞORT
                        </a>
                      </li>
                    </ul>
                  </li>
                  <li class="hideSubLVL" style="order: 3">
                    <a target="_self" class="" href="/dis-giyim" rel=" "
                      >Dış Giyim <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="hideSubLVL" style="order: 14">
                    <a target="_self" class="" href="/ayakkabi" rel=" "
                      >Ayakkabı <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="hideSubLVL" style="order: 14">
                    <a target="_self" class="" href="/taki" rel=" "
                      >Takı <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="hideSubLVL" style="order: 15">
                    <a target="_self" class="" href="/aksesuar" rel=" "
                      >Aksesuar <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                </ul>
              </div>
            </li>
            <li class="hideLVL" style="order: 2">
              <a
                target="_self"
                class="header-height relative align-items-center display-flex"
                href="/ShopByLook"
                rel=" "
                >SHOP BY LOOK
              </a>
            </li>
            <li class="" style="order: 3">
              <a
                target="_self"
                class="header-height relative align-items-center display-flex"
                href="/TwistZone"
                rel=" "
                >TWIST ZONE
              </a>
            </li>
            <li class="hideLVL twisterpicks-button" style="order: 4">
              <a
                target="_self"
                class="header-height relative align-items-center display-flex"
                href="/twisterpicks"
                rel=" "
              >
                #TWISTERSPICKS
              </a>
            </li>
            <li class="sub-items" style="order: 4">
              <a
                target="_self"
                class="header-height relative align-items-center display-flex"
                href="/Products/Outlet"
                rel=" "
                >Outlet
              </a>

              <div class="sub absolute transition animated fadeIn faster">
                <ul class="lvl-2 columnCount3">
                  <li class="showSubLVL sub-items" style="order: 0">
                    <a target="_self" class="" href="/outlet-giyim" rel=" "
                      >Giyim <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >

                    <ul class="lvl-3 columnCount2">
                      <li class="" style="order: 1">
                        <a
                          target="_self"
                          class=""
                          href="/outlet-elbise-modelleri"
                          rel=" "
                          >Elbise
                        </a>
                      </li>
                      <li class="" style="order: 2">
                        <a
                          target="_self"
                          class=""
                          href="/outlet-kadin-ceket-modelleri"
                          rel=" "
                          >Ceket
                        </a>
                      </li>
                      <li class="" style="order: 3">
                        <a
                          target="_self"
                          class=""
                          href="/outlet-tulum-modelleri"
                          rel=" "
                          >TULUM
                        </a>
                      </li>
                      <li class="" style="order: 4">
                        <a
                          target="_self"
                          class=""
                          href="/outlet-kadin-triko-kazak"
                          rel=" "
                          >Kazak
                        </a>
                      </li>
                      <li class="" style="order: 5">
                        <a
                          target="_self"
                          class=""
                          href="/outlet-kadin-tshirt-modelleri"
                          rel=" "
                          >T-Shirt
                        </a>
                      </li>
                      <li class="" style="order: 6">
                        <a
                          target="_self"
                          class=""
                          href="/outlet-kadin-sweatshirt-modelleri"
                          rel=" "
                          >Sweatshirt
                        </a>
                      </li>
                      <li class="" style="order: 7">
                        <a
                          target="_self"
                          class=""
                          href="/outlet-bluz-modelleri"
                          rel=" "
                          >Bluz
                        </a>
                      </li>
                      <li class="" style="order: 8">
                        <a
                          target="_self"
                          class=""
                          href="/outlet-kadin-gomlek-modelleri"
                          rel=" "
                          >Gömlek
                        </a>
                      </li>
                      <li class="" style="order: 9">
                        <a
                          target="_self"
                          class=""
                          href="/outlet-kadin-sort"
                          rel=" "
                          >Şort
                        </a>
                      </li>
                      <li class="" style="order: 10">
                        <a
                          target="_self"
                          class=""
                          href="/outlet-etek-modelleri"
                          rel=" "
                          >Etek
                        </a>
                      </li>
                      <li class="" style="order: 11">
                        <a
                          target="_self"
                          class=""
                          href="/outlet-kot-pantolon-modelleri"
                          rel=" "
                          >Jean
                        </a>
                      </li>
                      <li class="" style="order: 12">
                        <a
                          target="_self"
                          class=""
                          href="/outlet-kadin-pantolon-modelleri"
                          rel=" "
                          >Pantolon
                        </a>
                      </li>
                    </ul>
                  </li>
                  <li class="hideSubLVL" style="order: 0">
                    <a target="_self" class="" href="/outlet-dis-giyim" rel=" "
                      >Dış Giyim <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="hideSubLVL" style="order: 1">
                    <a target="_self" class="" href="/outlet-ayakkabi" rel=" "
                      >Ayakkabı <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="hideSubLVL" style="order: 2">
                    <a target="_self" class="" href="/outlet-taki" rel=" "
                      >Takı <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                  <li class="" style="order: 3">
                    <a target="_self" class="" href="/outlet-aksesuar" rel=" "
                      >Aksesuar <span class="lvl-close lvl-close-plus">+</span
                      ><span class="lvl-close lvl-close-minus">-</span></a
                    >
                  </li>
                </ul>
              </div>
            </li>
            <li
              class="hideLVL m-bttm-15 m-top-30 corplvl obj-mobile"
              style="order: 5"
            >
              <a
                target="_self"
                class="header-height relative align-items-center display-flex"
                href="/bddk-bilgi-icerigi"
                rel=" "
                >BDDK ONAYI
              </a>
            </li>
            <li class="hideLVL corplvl m-bttm-15 obj-mobile" style="order: 6">
              <a
                target="_blank"
                class="header-height relative align-items-center display-flex"
                href="https://mths.ttr.com.tr/firmabilgileri.aspx?mersis=4790044094000012"
                rel="noreferrer nofollow "
                >BİLGİ TOPLUMU HİZMETLERİ
              </a>
            </li>
            <li class="hideLVL corplvl m-bttm-15 obj-mobile" style="order: 7">
              <a
                target="_self"
                class="header-height relative align-items-center display-flex"
                href="/gizlilik-bildirgesi/"
                rel=" "
                >VERİLERİN KORUNMASI
              </a>
            </li>
            <li class="hideLVL corplvl m-bttm-15 obj-mobile" style="order: 8">
              <a
                target="_self"
                class="header-height relative align-items-center display-flex"
                href="/gizlilik-bildirgesi/"
                rel=" "
                >GİZLİLİK BİLDİRGESİ
              </a>
            </li>
            <li class="hideLVL corplvl m-bttm-60 obj-mobile" style="order: 9">
              <a
                target="_self"
                class="header-height relative align-items-center display-flex"
                href="/kullanim-kosullari/"
                rel=" "
                >KULLANIM SÖZLEŞMESİ
              </a>
            </li>
            <li class="hideLVL corplvl m-bttm-30 obj-mobile" style="order: 10">
              <a
                target="_blank"
                class="header-height relative align-items-center display-flex"
                href="https://twitter.com/TwistTurkiye"
                rel="noreferrer nofollow "
                >TWITTER
              </a>
            </li>
            <li class="hideLVL corplvl m-bttm-30 obj-mobile" style="order: 12">
              <a
                target="_blank"
                class="header-height relative align-items-center display-flex"
                href="https://www.facebook.com/twist.turkiye"
                rel="nofollow noreferrer "
                >FACEBOOK
              </a>
            </li>
            <li class="hideLVL corplvl m-bttm-30 obj-mobile" style="order: 13">
              <a
                target="_blank"
                class="header-height relative align-items-center display-flex"
                href="https://www.instagram.com/twistturkiye/"
                rel="nofollow noreferrer "
                >INSTAGRAM
              </a>
            </li>
          </ul>

          <ul class="menu-user-info obj-mobile display-flex align-items-center">
            <div class="homeBtn"><a href="/">ANASAYFA</a></div>

            <li class="ems-obj-logoff">
              <a
                class="btn-menu-title"
                href="javascript:document.location.href='/giris?returnUrl=' + window.location.pathname;"
                >ÜYE GİRİŞİ / YENİ ÜYELİK</a
              >
            </li>

            <li class="ems-obj-login sub-items">
              <a
                data-target="body"
                data-ready="mini-user-ready"
                data-animate="mini-user-animate"
                data-type="toggle"
                class="btn-menu-title"
                href="javascript:void(0);"
              >
                <svg class="icon icon-drop-left">
                  <use
                    xlink:href="/Content/Styles/base/icons.svg#drop-left"
                  ></use>
                </svg>
                HESABIM</a
              >

              <div class="sub memberLogonMobi"></div>
            </li>
          </ul>
          <div class="top-menu-append obj-mobile"></div>
        </div>
      </div>
      <div class="ga3">
        <div class="mini-lang obj-desktop dropdown">
          <div class="dropdown-header header-height">
            <span id="multiIcon-tr-TR"
              ><img border="0" /><b class="emos_invisible"></b
            ></span>
          </div>
          <ul class="sub">
            <!-- /default.aspx?lang=en-US -->

            <li>
              <a class="multiLink-tr-TR selected" href="/"
                ><span id="multiIcon-tr-TR"
                  ><img border="0" /><b class="emos_invisible"></b></span
              ></a>
            </li>
          </ul>
          <div class="mod-lang-footer"></div>
        </div>
      </div>
      <div class="ga4"></div>

      <div>
        <HeaderSearch />
      </div>

      <div>
        <HeaderUyelik />
      </div>

      <div>
        <HeaderSepet />
      </div>
    </div>
  </header>
</template>