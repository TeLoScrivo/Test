@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap");
@import url("https://eject37.github.io/DiscordTheme/HideTrash.css");
@import url("https://eject37.github.io/DiscordTheme/ScrollBar.css");
@import url("https://eject37.github.io/DiscordTheme/RoundUserPanel.css");
@import url("https://eject37.github.io/DiscordTheme/OldMicrophone.css");
@import url("https://eject37.github.io/DiscordTheme/ChangeSearchBarToIcon.css");
@import url("https://eject37.github.io/DiscordTheme/RegionFlags.css");

:root {
    --app-bg: url(https://i.imgur.com/rZRpRuv.gif);
    --blur-bg: 80px;
    --brightness-bg: 0.3;
    --border-main: 1px solid rgba(255, 255, 255, 0.1);
}

.theme-dark {
    /* Border в чате на сообщениях где код */
    --background-secondary-alt: rgba(255, 255, 255, 0.05);
    --background-tertiary: var(--background-secondary-alt);
    /* Бейджики  уведомлений */
    --status-danger: rgba(202, 90, 99, 0.9);
    /* ссылки*/
    --text-link: rgb(125, 170, 233);
    /* много где */
    --background-primary: rgba(245, 245, 245, 0.1);
    /* много где используется*/
    --background-secondary: rgba(255, 255, 255, 0.05);
    /* загруска сообщений в чате*/
    --bg-overlay-chat: rgba(255, 255, 255, 0.05);
    /* контекстное меню КРАСНАЯ кнопкА при наведении */
    --button-danger-background: rgba(250, 100, 135, 0.25);
    /* наводишься там где мьют микро слева снизу */
    --background-modifier-selected: rgba(190, 190, 190, 0.25);
    --background-floating: rgba(190, 190, 190, 0.25);
    --status-positive-background: rgba(190, 190, 190, 0.25);
    /* bar */
    --control-brand-foreground-new: rgba(100, 100, 100, 0.8);

    --text-brand: white;
}
:root {
    /* Шрифт */
    --font-primary: "Montserrat", Arial, sans-serif;
    --font-display: "Montserrat", Arial, sans-serif;
    --font-headline: "Montserrat", Arial, sans-serif;
    --status-positive: rgba(255, 255, 255, 0.7);
    --text-positive: rgba(255, 255, 255, 0.67);
    /* Цвет загрузки демок и прочего */
    --primary-700: rgba(200, 200, 200, 0.1);
    /* bar */
    --brand-500: rgba(100, 100, 100);
    /* Бордер чекбоксов, спиннер */
    --brand-400: rgba(170, 170, 170, 0.4);
    /* текст какой то */
    --brand-560: rgb(220, 220, 220);
    /* контекстное меню кнопки при наведении */
    --brand-530: rgba(230, 240, 255, 0.15);
    /* контекстное меню когда зажал */
    --brand-600: rgba(255, 255, 255, 0.3);
    /* мьют микро */
    --red-400: rgba(202, 90, 116, 0.7);
    /* стрелочка наводишься там где вайфай  */
    --green-360: rgba(230, 240, 255, 0.15);
    /* задний цвет там где сервер выбираешь */
    --primary-630: rgba(230, 240, 255, 0.15);
    /* можно выключить микрофон */
    --primary-860: rgba(202, 90, 99, 0.9);
    /* мьют микро на панели снизу слева */
    --important-messages-color: #fdbdbd;
    /* Длина и отступ панели табов в настройках */
    --custom-standard-sidebar-view-sidebar-content-width: 217px;
    --custom-standard-sidebar-view-standard-padding: 100px;
}

/* Шрифт */
:root:lang(bg),
:root:lang(el),
:root:lang(ru),
:root:lang(uk) {
    --font-primary: "Montserrat", Arial, sans-serif;
    --font-display: "Montserrat", Arial, sans-serif;
    --font-headline: "Montserrat", Arial, sans-serif;
}

/* гифка для всего дс */
body {
    background: var(--app-bg) no-repeat;
    background-position: 15%;
    background-size: 105% 105%;
}

/* добавляет блюр и затемнение на задний фон */
.bg__960e4 {
    backdrop-filter: blur(var(--blur-bg)) brightness(var(--brightness-bg));
}

/* Credits */
.info__2debe::before {
    content: "Theme by jAba & Eject";
    color: var(--text-muted);
    font-size: 14px;
    padding-bottom: 10px;
    display: block;
}

/* убирает задний цвет для гифки */
.chatContent_f75fb0,
.chat_f75fb0,
.sidebar_c48ade,
.panel__5dec7,
.container_e131a9,
.container__37e49,
.wrapper_ef3116,
.callContainer_cb9592,
.wrapper_cb9592,
.panels_c48ade,
.privateChannels__35e86,
.scroller__99e7c,
.themedBackground__74017,
.themed__9293f,
.bg__960e4,
#app-mount,
.app__160d8,
.codeView__4d95d.hljs,
.menu_c1e9c4:not(.menu_ad5fac),
.embedFull__623de,
.container_c8ffbb,
.members_c8ffbb,
.container__2637a,
.member_c8ffbb,
.sidebarRegionScroller__23e6b,
.standardSidebarView__23e6b,
.layer__960e4,
.contentRegionScroller__23e6b,
.contentRegion__23e6b,
.container__133bf,
.nowPlayingColumn__133bf,
.container__7d20c,
.inset_bf1984,
.stackedBars__74017,
.background__1fed1,
.fieldList__1fed1,
.premiumBackground__65c15,
.overlayBackground_c69a7b,
.bannerNormal_ab876d,
.userProfileInnerThemedNonPremium_c69a7b,
.container__0b563,
.header__0b563m,
.mediaBarInteractionVolume_f7877e,
.medium__49fc1,
.modal__56d1c,
.authBoxExpanded_dc6abe,
.childWrapperNoHoverBg__6e9f8,
.scroller__5d7c9,
.thin_d125d2.scrollerBase_d125d2.fade_d125d2,
.brand_b3f026,
.streamPreview__2f4f7 {
    background: transparent !important;
}

/* фиксит 4px title bar */
.withFrame__421ed {
    margin-top: 0;
    padding-top: 4px;
}

/* убирает залупу */
.form_f75fb0:before, /*градиент возле чатбокса*/
.form_f75fb0:after,
.children__9293f:after,/* какой то градиент сверху хз */
.protip_ac6cb0, /* нахуй оно надо (в найти или начать беседу) */ 
.block__30cbe, /* нахуй оно надо (в закрепах) */
.tutorial__73f2a.shown__73f2a, /* нахуй оно надо (подсказка в найти или начать беседу) */
.userSettingsSecurityImage__2666b,
.ready_a2f514, /* нахуй оно надо (моя учетная запись)*/ 
.content_f75fb0:before,/* черная полосаааа*/
.container__8279f, /*реклама*/
.footerImage__98b95,.tipTitle_a2f514,.buttonContainer_e6e74f,.statusBubbleOuter_af9888::after,
.statusBubbleOuter_af9888::before,.art_a55fdc {
    display: none !important;
}

/* Выделение текста */
::selection {
    background: rgba(94, 98, 106, 0.4) !important;
}

/* Кнопки в голосовом чате (офф микро, дать демку, выйти из звонка) */
#app-mount .staticButton_f1ceac,
#app-mount .contextMenuNub_f1ceac {
    background-color: rgba(255, 255, 255, 0.1) !important; /*off call*/
    color: rgb(255, 255, 255) !important;
}
#app-mount .staticButton_f1ceac:hover {
    background-color: rgba(255, 255, 255, 0.2) !important; /*off call*/
}

/* демка */
.callContainer_cb9592 {
    background: linear-gradient(
        rgba(0, 0, 0, 0.15),
        rgb(0, 0, 0, 0.1)
    ) !important;
    box-shadow: inset 0 0 10px rgba(100, 100, 100, 0.1);
    border-radius: 10px;
    border: var(--border-main);
    margin-left: 10px;
    margin-right: 10px;
    margin-top: 10px;
}
/* фикс демки в полном экране */
.callContainer_cb9592:has(.actionRow__6981d) {
    margin: 0;
    border-radius: 0;
    border: none;
    box-shadow: none;
}

/* меняет градиент при навидиении там где демка */
.gradientContainer_bfe55a {
    background-image: linear-gradient(
        rgba(255, 255, 255, 0.04) 0%,
        rgba(0, 0, 0, 0) 50%
    );
}

/* ввод сообщений (chatbox) */
.channelTextArea_f75fb0 {
    background: rgba(255, 255, 255, 0.03) !important;
    border: var(--border-main);
    border-radius: 15px;
    box-shadow: inset 0 0 5px rgba(100, 100, 100, 0.2);
}
.scrollerSpacer__36d07 {
    height: 25px;
}
.form_f75fb0 {
    margin-top: 0;
}

/* Пользователи слева в списке, справа на серверах, каналы на серверах */
.interactive_bf202d,
.member_c8ffbb,
.layout__91a9d,
.modeSelected__2ea32 .link__2ea32,
.wrapper__2ea32 .link__2ea32 {
    transition: 0.1s;
    margin-left: 5px;
    width: 95%;
    border-radius: 10px;
}
.selected_bf202d,
.interactive_bf202d:hover,
.member_c8ffbb:hover,
.modeSelected__2ea32 .link__2ea32,
.modeSelected__2ea32:hover .link__2ea32 {
    background: linear-gradient(
        rgba(184, 184, 184, 0.225),
        rgba(255, 255, 255, 0.144)
    );
    margin-left: 7px;
}
.modeSelected__2ea32 .link__2ea32,
.wrapper__2ea32 .link__2ea32 {
    transition: none;
}

/* Строка поиска слева сверху */
.searchBarComponent__35e86 {
    margin-left: 7px;
    width: 94% !important;
}

/* Контекстное меню Blur */
.menu_c1e9c4:not(.menu_ad5fac, [id="account"], [id="status"]):before {
    position: absolute;
    content: " ";
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    backdrop-filter: blur(20px);
    pointer-events: none;
    z-index: -1;
}
/* профиля когда тыкаешь */
.banner__68edb.divider_c3e427.biteSizeBanner_c3e427,
.banner__68edb.divider_c3e427.fullSizeBanner_c3e427.roundedBanner_c3e427,
.fullSizeInnerThemed_c69a7b {
    background: rgba(255, 255, 255, 0.03) !important;
}

.container_fcf29c {
    background: rgba(255, 255, 255, 0.03) !important;
    backdrop-filter: blur(20px);
    box-shadow: inset 0 0 15px rgba(100, 100, 100, 0.1) !important;
}

/* профиль слева снизу */
.biteSizeInnerThemed_c69a7b {
    background: rgba(255, 255, 255, 0.03) !important;
}
/* фикс когда открыта картинка */
#image-context[class*="menu_c1e9c4"] {
    backdrop-filter: blur(15px) brightness(var(--brightness-bg));
}
.menu_c1e9c4:not(.menu_ad5fac) .submenu_c1e9c4:before {
    width: calc(100% - 16px);
    left: 8px;
}

/* панель пользователя */
[class^="sidebar_"] [class^="panels_"] {
    box-shadow: 0 0 3px 1px rgba(0, 0, 0, 0.45),
        inset 0 0 10px rgba(100, 100, 100, 0.2);
}
[class^="sidebar_"] [class^="panels_"] [class^="container_"],
[class^="sidebar_"] [class^="panels_"] [class^="panel_"] {
    background-color: rgba(100, 100, 100, 0.04) !important;
}

/* Загружаемые файлы и разные фоны в сообщениях */
.fileWrapper__0ccae.newMosaicStyle_b52bef,
.newMosaicStyle__4d95d .codeView__4d95d,
.newMosaicStyle__4d95d .footer__4d95d,
.newMosaicStyle__4d95d .textContainer__4d95d,
.grid__623de,
.wrapper_d5f3cd,
.markup__75297 code,
.content__908e2 {
    background: rgba(100, 100, 100, 0.15);
}

/*блюр*/
.wrapper_f7ecac,
.quickswitcher_ac6cb0,
.tooltipPrimary__382e7,
.tooltipGreen__382e7,
.newMessagesBar__0f481,
.tooltipGrey__382e7,
.streamPreview__2f4f7 button,
#emoji-picker-tab-panel,
.root__2dbe1.elevationHigh__2b2f1,
.container_fcf29c,
.body__6da2d,
.bar__7aaec,
#popout_353,
#popout_459,
.streamPreview__6da2d,
.popout_af3b89 {
    backdrop-filter: blur(10px) !important;
}

/* При наведении в чате на сообщение справа тул панель с действиями */
.wrapper_f7ecac {
    border-radius: 10px;
    border: 1px solid var(--background-secondary-alt);
    background: rgba(165, 165, 165, 0.15);
}

/* Ссылки в чате */
a.anchor_edefb8 > span:not(.username__703b9) {
    background: linear-gradient(
        90deg,
        rgb(78, 208, 255),
        rgb(230, 98, 230),
        rgb(171, 189, 56)
    );
    color: transparent;
    background-clip: text;
}

/* друзья */
.wrapper__00943,
.section__00943 {
    background: rgba(100, 100, 100, 0.15);
}
.outer_bf1984.interactive_bf1984:hover,
.theme-dark .outer_bf1984.active_bf1984 {
    background: rgba(100, 100, 100, 0.3) !important;
}
.actionButton_f8fa06 {
    background: rgba(100, 100, 100, 0.3) !important;
}
/* друзья */

/* поиск нажатие */
.quickswitcher_ac6cb0 {
    background: rgba(100, 100, 100, 0.15);
    box-shadow: inset 0 0 15px rgba(255, 255, 255, 0.1);
    padding: 3%;
    padding-right: 34px;
}
.input_ac6cb0 {
    background: rgba(100, 100, 100, 0.1);
    width: 103.4%;
}
.scroller_ac6cb0 {
    background: rgba(100, 100, 100, 0.15);
}

/* Если тебя упомянули */
.mentioned__5126c {
    background: rgba(226, 226, 226, 0.08) !important;
}
/* Линия слева в сообщении в котором тебя упомянули */
.mentioned__5126c:before {
    background-color: rgba(226, 226, 226, 0.16);
}

/* теги когда тэгаешь кого то */
.autocomplete__13533 {
    background-color: rgba(35, 35, 35, 0.2) !important;
    backdrop-filter: blur(15px);
    border-radius: 10px;
    border: 1px solid var(--background-secondary-alt);
}

/* ответить , вы просматриваете старые сообщения*/
.replyBar__841c8,
.jumpToPresentBar__0f481 {
    background: rgba(100, 100, 100, 0.07);
    border-bottom: 1px solid rgba(228, 228, 228, 0.03);
}
.jumpToPresentBar__0f481 {
    backdrop-filter: blur(20px);
    border-radius: 10px;
    border: 1px solid var(--background-secondary-alt);
}

/* авторизованные пользователи */
.cardPrimary__73069 {
    background: rgba(100, 100, 100, 0.07);
}
/* семейный центр */
.container__5dbf8,
.container__8e680,
.container__5b321 {
    background: rgba(100, 100, 100, 0.1);
    border: 1px solid var(--background-secondary-alt);
}

/* Настройки > Профили > Попробуйте нитро */
.premiumFeatureBorder__65c15 {
    background: rgba(100, 100, 100, 0.15) !important;
    border: 1px solid var(--background-secondary-alt);
}
/* категория приложений */
.directoryContainer_da3f59 {
    backdrop-filter: blur(var(--blur-bg)) brightness(var(--brightness-bg));
}

/* textbox */
.input__0f084,
.input__0f084:hover {
    background: rgba(100, 100, 100, 0.2) !important;
    border: 1px solid var(--background-secondary-alt);
}
.input__0f084.focused__0f084,
.input__0f084:focus {
    border: 1px solid rgba(255, 255, 255, 0.15);
}
/* Настройки > Профили > Обо мне (textbox) */
.bioTextArea__6a919 {
    background: rgba(100, 100, 100, 0.2) !important;
    border: var(--border-main);
}

/* предпросмотр профиля */
.userProfileInnerThemedNonPremium_c69a7b {
    border: var(--border-main);
}

/* SelectBox (Настройки > Конфиденциальность) */
.lookFilled__3f413.select__3f413 {
    background: rgba(100, 100, 100, 0.2) !important;
    border: var(--border-main);
}
/* open select box  */
.popout__3f413 {
    background: rgba(100, 100, 100, 0.2) !important;
    backdrop-filter: blur(20px);
    border: var(--border-main);
}
/* Width fix  */
.popout__3f413.scrollerBase_d125d2 {
    overflow: auto !important;
}

/* фильтр спама */
.itemFilled__001a7 {
    background: rgba(100, 100, 100, 0.2) !important;
}

/* Toogle ON */
.container__87bf1.checked__87bf1 {
    background-color: rgba(255, 255, 255, 0.4) !important;
}
/* Toogle OFF */
.container__87bf1 {
    background-color: rgba(100, 100, 100, 0.4) !important;
}

/* Настройки > Самая нижняя панель */
.card__73069:not(.outline__73069) {
    background-color: rgba(100, 100, 100, 0.15) !important;
}

/* интеграция */
.connection_c7f964,
.accountButtonInner_c7f964,
.accountBtnInner__750de {
    background-color: rgba(100, 100, 100, 0.2) !important;
}

/* WARNING (Настройки > Горячие клавиши) */
.vc-backup-restore-card,
.warning__6436f {
    border: 1px solid rgba(240, 230, 100, 0.4);
}

/* Настройки > Зарегистрированные игры (верхняя панель)  */
.notDetected_cc46f0 {
    background-color: rgba(100, 100, 100, 0.1) !important;
    border: var(--border-main);
}

/* Blue + Red Buttons */
button[class*="lookFilled__201d5"] {
    background-color: rgba(150, 150, 150, 0.25) !important;
    border-radius: 7px;
}
button[class*="lookFilled__201d5"]:hover {
    background-color: rgba(150, 150, 150, 0.35) !important;
}
/* Кнопка деавторизировать */
.lookOutlined__201d5.colorRed__201d5 {
    border: var(--border-main);
}
.lookOutlined__201d5.colorRed__201d5:hover {
    background-color: rgba(190, 30, 60, 0.3);
    border: 1px solid rgba(190, 30, 60, 0.4);
}

/* MessageBox`ы  */
.container__468a6.root__49fc1,
.modalSize_e1cc86.root__49fc1,
.small__49fc1,
.medium__49fc1 {
    background-color: rgba(100, 100, 100, 0.2) !important;
    backdrop-filter: blur(25px);
    border-radius: 10px;
}
.footer__49fc1,
.message__89466 {
    background-color: rgba(100, 100, 100, 0.1) !important;
    border-radius: 10px;
}

/* Настройки > Левая панель (табы) */
.side_b3f026 .selected_b3f026 {
    background-color: rgba(100, 100, 100, 0.3) !important;
}
.side_b3f026 .item_b3f026 {
    border-radius: 10px;
}

/* Закрепленные сообщения */
.messagesPopoutWrap__45690,
.container__55c99 {
    background-color: rgba(100, 100, 100, 0.1) !important;
    backdrop-filter: blur(35px);
}
.messageGroupWrapper__45690 {
    background-color: rgba(100, 100, 100, 0.1) !important;
}
.messagesPopoutWrap__45690 {
    margin-top: -15px; /* Фикс для margin области разговора (демки) что бы дискорд не прыгал */
}
/* чат */
.themedBackground__74017 {
    background-color: transparent;
}

.uploadDropModal_dbca3c .bgScale_dbca3c {
    background-color: rgba(100, 100, 100, 0.3) !important;
    backdrop-filter: blur(10px);
}
.uploadDropModal_dbca3c .inner_dbca3c .instructions_dbca3c {
    display: none !important;
}
/* Открытый поиск в диалоге (когда уже просматриваешь найденные сообщения) */
.searchResultsWrap_a9e706 {
    background-color: rgba(100, 100, 100, 0.2) !important;
}
.searchResult__02a39 {
    background-color: rgba(100, 100, 100, 0.1) !important;
    border: var(--border-main);
}

/* Кнопка + (Добавить сервер) */
.circleIconButton__5bc7e {
    background-color: rgba(200, 205, 210, 0.1) !important;
    color: rgba(200, 200, 200, 0.8) !important;
}

/* Поиск в чате справа сверху при наведении */
.searchBar__97492:hover,
.focused__97492 .searchBar__97492,
.open__97492 .searchBar__97492 {
    background-color: rgba(100, 100, 100, 0.25);
    backdrop-filter: blur(20px);
}

/* кнопка пригласить на сервер друга */
.inviteRowButton__67dba,
.lookOutlined__201d5.colorGreen__201d5:hover {
    background-color: rgba(100, 100, 100, 0.25);
    border: var(--border-main) !important;
    width: 110px;
    border-radius: 6px;
}

/* когда кто то говорит */
.border__2f4f7.speaking__2f4f7 {
    box-shadow: inset 0 0 20px rgba(130, 130, 130, 0.7);
}
/* когда кто то говорит */

/* устройстав задний цвет */
.sessionIcon__803f2,
.legacySession__803f2 .sessionIcon__803f2 {
    filter: invert();
    background-color: rgba(100, 100, 100, 0.25) !important;
}

/* BETA где то в настройках */
.textBadge_f05120 {
    background-color: rgba(100, 100, 100, 0.5) !important;
}

/* ссылки при клике которые не обычные ссылки */
.fileNameLink__0ccae,
.link__50a54,
.lookLink__201d5 {
    background: linear-gradient(90deg, rgb(255, 84, 132), rgb(137, 90, 255));
    color: transparent;
    background-clip: text;
}

/* ToolTip */
.tooltipPrimary__382e7,
.tooltipGreen__382e7 {
    background-color: rgba(100, 100, 100, 0.2) !important;
    border-radius: 10px;
}

/* цвет профиля когда тыкаешь сверху */
.popoutBanner_c3e427,
.banner__68edb.modalBanner_c3e427 {
    background-color: rgba(100, 100, 100, 0.2) !important;
}
.userPopoutInner_c69a7b:before {
    position: absolute;
    content: " ";
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    backdrop-filter: blur(20px);
    pointer-events: none;
    z-index: -1;
}

/* идет загрузка файла */
.fileWrapper__0ccae {
    background-color: rgba(100, 100, 100, 0.1) !important;
}
/* вставка файла в чат */
.upload_aa605f {
    background-color: rgba(100, 100, 100, 0.2) !important;
    border-radius: 10px;
}
/* Green Ico demka ON */
.upperBadge_cc5dd2 > .iconBadge__650eb {
    background-color: transparent !important;
    background-color: rgb(71, 71, 71) !important;
}

/* Шрифт для плагина который показывает сколько времени я в голосовом канале */
.text-xs-normal__46d75 span {
    font-family: var(--font-primary) !important;
}

/* шрифт ГОЛОСОВАЯ СВЯЗЬ ПОДКЛЮЧЕНА */
.contents__201d5 {
    font-weight: 500;
}

/* ачивмент в профиле */
.profileBadges_f89da9 {
    background-color: rgba(140, 140, 140, 0.2) !important;
}

/* квадрат загрузки */
.loadingPopout__58f1c {
    border-radius: 10px;
}
.container_a2f514.fixClipping_efbae7 {
    backdrop-filter: blur(30px);
}
/* сверху в чате новые сообщения */
.newMessagesBar__0f481 {
    background: rgba(255, 255, 255, 0.1);
    border: var(--border-main);
}

/* форумы на сервере */
.mainCard_f369db {
    background: rgba(255, 255, 255, 0.1);
}
.container_faa96b:hover {
    background: rgba(255, 255, 255, 0.2);
}

/* сообщение при входе в дс */
.tip_a2f514 {
    color: transparent;
    max-width: 1000px !important;
}
.tip_a2f514::before {
    content: "Animated Glass Theme";
    color: white !important;
    display: flex;
    justify-content: center;
    font-size: 40px;
    font-family: "Montserrat", sans-serif;
    font-weight: bold;
}

.tip_a2f514::after {
    animation: slidein 1s;
    content: "Updated: 20.08.2024 ";
    color: white !important;
    display: flex;
    justify-content: center;
    font-size: 20px;
    font-family: "Montserrat", sans-serif;
    font-weight: bold;
}

@keyframes slidein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}

/* чат ?????? */
.chat_f75fb0.content_f75fb0.container__0b563 {
    background: rgba(255, 0, 0, 1) !important;
}

/* просмотр каналов на сервере */
.channelRow_e4503a {
    background: rgba(255, 255, 255, 0.1) !important;
}

/* в вашем списке каналов нет этого канала НА СЕРВЕРЕ  */
.chatHeaderBar_dc83f5 {
    background: rgba(255, 255, 255, 0.1) !important;
}

/* ПОМЕТКА БОТА БОТ */
.botTagRegular__82f07 {
    background: rgba(255, 255, 255, 0.15) !important;
}

/* прN наведении на упоминание */
.interactive:hover {
    background: rgba(255, 255, 255, 0.15) !important;
}

/* Поставленная реакция на сообщение */
.reactionMe__23977 {
    background: rgba(255, 255, 255, 0.15) !important;
}

/* ветки на серверах */
.container_d9c882 {
    backdrop-filter: blur(25px);
}

/* Иконка дискорда слева сверху */
.wrapper__6e9f8:hover .childWrapper__6e9f8,
.wrapper__6e9f8.selected__6e9f8 .childWrapper__6e9f8 {
    background: rgba(255, 255, 255, 0.1) !important;
    box-shadow: inset 0 0 10px rgba(255, 255, 255, 0.1) !important;
}

/* Кнопки в контекстном меню */
.colorDefault_c1e9c4.focused_c1e9c4 {
    border-radius: 10px;
}

/* удалить сообщение в контекстом меню */
.colorDanger_c1e9c4 {
    color: rgb(202, 90, 116);
}

/* способы скама на нитро на маманта */
.paymentPane__01014,
.paginator__01014,
.payment_e9cb00 {
    background: rgba(255, 255, 255, 0.015) !important;
}

/* панель эмодзи */
.contentWrapper__08434 {
    backdrop-filter: blur(20px);
}
.popoutContainer__0f481 {
    background: rgba(255, 255, 255, 0.05) !important;
}

/* выбор контекстого меню галочки фон */
.colorDefault_c1e9c4.focused_c1e9c4 path {
    fill: rgba(255, 255, 255, 0.3);
}

/* фон выбора сервера  */
.regionSelectPopout__5621e {
    backdrop-filter: blur(15px);
    border-radius: 10px;
    background: rgba(255, 255, 255, 0.1) !important;
    border: var(--border-main);
}

/* добавить в друзья главный экран */
.tabBar__133bf .addFriend__133bf.addFriend__133bf.addFriend__133bf:hover {
    background: rgba(255, 255, 255, 0.25) !important;
}

/* добавить в друзья бордер */
.addFriendInputWrapper__72ba7:focus-within {
    border: var(--border-main);
}

/* сведение 0 сервере */
.container__13b2a {
    backdrop-filter: blur(20px);
    border-radius: 10px;
    border: var(--border-main);
}

/* зажатие на удалить сообщения */
.colorDanger_c1e9c4:active:not(.hideInteraction_c1e9c4) {
    background: rgba(202, 90, 116, 0.6) !important;
}
/* фикс бордера в контекстном меню при зажатии и отведении */
.colorDefault_c1e9c4:active:not(.hideInteraction_c1e9c4) {
    border-radius: 10px;
}

/* плагин membercount */
.vc-membercount-widget {
    --color-online: rgba(108, 255, 223, 0.7);
}

/* когда демку можно включить */
.colorable_f1ceac.primaryDark_f1ceac .centerIcon_f1ceac {
    color: rgb(255, 255, 255);
}

/* можно выключить демку */
.colorable_f1ceac.white_f1ceac,
.colorable_f1ceac.white_f1ceac .centerIcon_f1ceac {
    color: rgba(202, 90, 99, 0.9);
}

/* линия под ссылками */
.anchor_edefb8 {
    text-decoration-color: rgba(255, 255, 255, 0.45) !important;
}

/* Черная линия в чате в разговоре */
.resizeHandle__4b144 {
    background-color: transparent;
}

/* Уведомление о обновлении VenCord */
.vc-notification {
    backdrop-filter: blur(20px);
}

/* фон сообщений при наведении */
.message__5126c:hover {
    background: rgba(190, 190, 190, 0.03) !important;
}

.popout__4c91, /* статус действий на сервере	 */ 
.reactionTooltip_b49891  /* наведение на реакцию */ {
    backdrop-filter: blur(15px) brightness(0.6);
}

/* добавить учетную запись */
.authBoxExpanded_dc6abe,
.modal__56d1c {
    background: rgba(255, 255, 255, 0.05) !important;
    backdrop-filter: blur(15px);
}

/* Add server */
.circleIconButton__5bc7e:hover > .circleIcon__5bc7e {
    animation: ani-rotate 1s linear infinite;
}
/* статистика пинга  */
.debugPanelStandalone__50387 {
    backdrop-filter: blur(15px);
    border-radius: 15px;
}

/* верхний цвет откртия профиля */
.settingsBanner_c3e427 {
    background-color: rgba(100, 100, 100, 0.2) !important;
}
/* полоска за которую перетягиваешь звук */
.grabber_a562c8 {
    background-color: rgb(150 150, 150) !important;
    border: var(--border-main);
}
/* выбор звуков пердежа */
.picker__09f65 {
    backdrop-filter: blur(15px) !important;
}
/* Настройки > склад подарков */
.giftCardButton_da4aee {
    background-color: rgba(100, 100, 100, 0.2) !important;
    border: var(--border-main) !important;
}
.giftCardButton_da4aee:hover {
    background-color: rgba(100, 100, 100, 0.4) !important;
}
/* линия прокрутки */
.bar_a562c8,
.markDash_a562c8 {
    background: rgba(67, 67, 67, 0.52) !important;
}

/* линия прокрутки */
article.embedWrapper_b7e1cb.embedFlexGrow_b7e1cb.embedFull__623de.embed__623de.markup__75297 {
    border-color: rgba(200, 200, 200, 0.35) !important;
}

/* почта */
.recentMentionsPopout__95796 {
    backdrop-filter: blur(20px);
    border-radius: 10px;
}

/* контекстное меню мышкой  навелся */
.colorDefault_c1e9c4.focused_c1e9c4 {
    background: rgba(255, 255, 255, 0.1);
}

.colorDefault_c1e9c4:active:not(.hideInteraction_c1e9c4) {
    background: rgba(255, 255, 255, 0.15);
}

/* реакция на сообщение */
#emoji-picker-tab-panel {
    border: var(--border-main) !important;
}

.tooltipBrand__382e7 {
    background: rgba(255, 255, 255, 0.1) !important;
}

/* когда кто то звонит */
.root__2dbe1.elevationHigh__2b2f1 {
    background: rgba(255, 255, 255, 0.1) !important;
    border-radius: 10px;
}

/* Стеклеянные окна */
.searchBarComponent__35e86, /* Строка поиска слева сверху */
.menu_c1e9c4:not(.menu_ad5fac), /* Контекстное меню */ 
.searchBar_c7e907,   /* поиск в настройках */ 
.searchBarComponent__35e86  /*поиск в главном менбю*/ {
    background: rgba(190, 190, 190, 0.05) !important;
    border-radius: 10px !important;
}

/* профиль когда тыкаешь снизу слева */
.biteSizeInner_c69a7b::before {
    position: absolute;
    content: " ";
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    backdrop-filter: blur(20px);
    pointer-events: none;
    z-index: -1;
}

/* цветовая панель в зависимости от цвета аватарки */
.banner__68edb {
    background-color: rgba(255, 255, 255, 0.1) !important;
}

/* добавить статус */
.statusBubbleShape_af9888 {
    background-color: rgba(255, 255, 255, 0.05);
}

.allow__344e6.selected__344e6 {
    background-color: rgba(255, 255, 255, 0.25);
}

.passthrough__344e6.selected__344e6 {
    background-color: rgba(255, 255, 255, 0.15);
}

/* наве6стись на канал сервера */
.popout__76f04 {
    backdrop-filter: blur(20px);
    border: var(--border-main);
    border-radius: 10px;
}

#popout_2709 {
    backdrop-filter: blur(20px);
    border-radius: 10px;
}

#app-mount
    div[class*="controlButton__1405b"]
    button[aria-label="Прекратить просмотр"]
    svg
    path {
    fill: rgba(202, 90, 99, 0.9) !important;
}

.statusBubbleSingleLineWithTextShape_af9888 {
    background-color: rgba(255, 255, 255, 0.05) !important;
}

#app-mount div > div[aria-label="Другие настройки"] {
    background: transparent !important;
    box-shadow: inset 0 0 10px rgb(100, 100, 100, 0.7);
}

.vc-settings-quickActions-pill:hover {
    background-color: rgba(255, 255, 255, 0.1) !important;
}

/* Скрываем снизу слева помойку от 16.11.2024 */
.footer__214dc,
.footer__214dc {
    display: none !important;
}

.inner_c0bea0.biteSize_c0bea0 {
    background-color: rgba(146, 146, 146, 0.1);
    backdrop-filter: blur(15px);
}

.statusBubbleWithTextPadding_af9888 {
    background-color: rgba(146, 146, 146, 0.15) !important;
}
.scroller_affa7e {
    width: 110%;
}

.header_c656ac {
    background-color: rgba(0, 0, 0, 0.1);
    backdrop-filter: blur(30px);
}

.inner_c0bea0.fullSize_c0bea0 {
    background: none;
}

.accountProfilePopoutWrapper__37e49 {
    border: 1px solid rgba(255, 255, 255, 0.3);
    border-radius: 10px;
}

.rootWithShadow__49fc1 {
    background-color: rgba(255, 255, 255, 0.1) !important;
    backdrop-filter: blur(10px);
    border-radius: 10px;
    box-shadow: 0 0 25px rgba(255, 255, 255, 0.15);
}
.footerSeparator__49fc1 {
    background-color: rgba(255, 255, 255, 0.1) !important;
}
.focusLock__49fc1 {
    box-shadow: inset 0 0 5px rgba(150, 150, 150, 0.1);
    border-radius: 10px;
}

.modalCloseButton_a55fdc {
    right: -90%;
    position: relative !important;
    width: 10%;
}

@keyframes ani-rotate {
    0% {
        transform: rotate(0);
    }
    100% {
        transform: rotate(360deg);
    }
}

.scrollerBase_d125d2 {
  -ms-overflow-style: none;  /* IE and Edge */
  scrollbar-width: none;  /* Firefox */
}
