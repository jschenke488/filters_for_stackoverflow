```html
<!--Hello Dev! Welcome to our new Filter's bar. If you need direct access to our secret keys, please go to https://s.tk/StackOverflowSecrets. (DON'T SHARE OUTSIDE THE COMPANY)-->
<label for="js-expand-theme-selector" class="af-bar af-bar--smol ps-sticky b0 l100 ml-auto mr32 px16 py12 btr-md bg-black flex__center z-nav-fixed c-pointer f:outline-ring js-smol-bar">
    <button id="expand-theme-selector" class="v-visible-sr">Expand theme selector</button>
    <!--Smol Brain Bar SBB-->
    <img class="af-logo-img mr8" src="https://cdn.sstatic.net/Img/april-fools-2022/assets/logo-minimized.svg?v=7684b7c8e9a4" alt="filters for Stack Overflow logo"/>
    <img class="af-logo-img" src="https://cdn.sstatic.net/Img/april-fools-2022/assets/logo-glasses.svg?v=c4f4fb1d2e55" alt="filters for Stack Overflow logo"/>
</label>

<div class="ps-sticky b0 px16 w100 bg-black-800 bt bc-black-800 fc-white z-nav-fixed af-bar af-bar__big af-bar__shown js-big-bar">
    <!--Medium Brain Popover MBP-->
    <div id="js-medium-brain-popover" class="s-popover ws7 wmx75 m-auto p16">
        <div class="s-popover--arrow s-popover--arrow__bc"></div>
        <button class="s-popover--close s-btn s-btn__muted js-close-popup" aria-label="Close" data-action="1">
            <svg aria-hidden="true" class="svg-icon iconClearSm" width="14" height="14" viewbox="0 0 14 14"><path d="M12 3.41 10.59 2 7 5.59 3.41 2 2 3.41 5.59 7 2 10.59 3.41 12 7 8.41 10.59 12 12 10.59 8.41 7 12 3.41Z"/></svg>
        </button>
        <div class="d-flex sm:w100 ai-center sm:fd-column">
            <div class="flex--item mr24 sm:mr0 sm:mb12">
                <div class="bs-md bg-black-025 bar-md overflow-hidden ps-relative us-none pe-none">
                    <img src="https://cdn.sstatic.net/Img/april-fools-2022/popover-animation/hotdog.svg?v=5e78a44d2679" class="af-theme-image" id="af-theme-1"/>
                    <img src="https://cdn.sstatic.net/Img/april-fools-2022/popover-animation/bookface.svg?v=7d53d52e7a56" class="af-theme-image" id="af-theme-2"/>
                    <img src="https://cdn.sstatic.net/Img/april-fools-2022/popover-animation/3d.svg?v=0782417cc591" class="af-theme-image" id="af-theme-3"/>
                    <img src="https://cdn.sstatic.net/Img/april-fools-2022/popover-animation/default.svg?v=f3d19783e6e0" class="af-theme-image-base d-block"/>
                </div>
            </div>
            <div class="flex--item">
                <h2 class="mb8">
                    <span class="s-label--status ml0 s-label--status__beta va-middle mr4">New</span>
                    Introducing Filters for Stack Overflow
                </h2>
                <p class="fs-body2 fc-black-700">Filters aren’t just for selfies anymore. Introducing Filters for Stack Overflow - the best way to beautify the site where you spend 10 hours a day.</p>
                <div>
                    <a href="https://stackoverflow.blog/2022/03/31/time-to-get-on-trend-filters/" target="_blank" class="s-btn s-btn__primary js-learn-more-about-filters">Learn more about Filters</a>
                    <button class="s-btn js-close-popup" data-action="2" data-revert="true">Revert and hide this feature</button>
                </div>
            </div>
        </div>
    </div>

    <!--Big Brain Bar BBB-->
    <div id="js-af-popover" class="d-flex w100 gs16 py8 flex__center" data-controller="s-popover" aria-controls="js-medium-brain-popover" data-s-popover-placement="top" data-s-popover-hide-on-outside-click="never" data-should-autoshow-popover="true">
        <div class="flex--item d-flex fl-equal sm:fl-initial">
            <div class="af-logo-container d-flex ai-center p8 mn8">
                <img class="af-logo-img mr8 sm:d-none" src="https://cdn.sstatic.net/Img/april-fools-2022/assets/logo-expanded.svg?v=8dcf8ddcd242" alt="filters for Stack Overflow logo"/>
                <img class="af-logo-img sm:d-inline-block sm:hmx100 w-auto" src="https://cdn.sstatic.net/Img/april-fools-2022/assets/logo-glasses.svg?v=c4f4fb1d2e55" alt="filters for Stack Overflow logo"/>
            </div>
        </div>
        <div class="flex--item sm:d-none d-flex jc-center fl-equal">
            <div class="d-flex gs16 gsx ai-center jc-center mx-auto">
                    <input id="js-theme-1" type="radio" class="v-visible-sr js-af2022-theme-selector" name="af2022-theme" value="1"/>
                    <label for="js-theme-1" class="af-theme-button flex--item c-pointer js-af2022-hover" role="button" data-horse="Default" data-squid="Stack Overflow">
<svg aria-hidden="true" class="svg-icon iconNotInterested" width="18" height="18" viewbox="0 0 18 18"><path d="M9 17A8 8 0 1 1 9 1a8 8 0 0 1 0 16Zm0-2a6 6 0 0 0 4.89-9.48L5.52 13.9C6.5 14.59 7.7 15 9 15Zm-4.89-2.52 8.37-8.37a6 6 0 0 0-8.37 8.37Z"/></svg>                        <span class="v-visible-sr">Default theme</span>
                    </label>
                    <input id="js-theme-2" type="radio" class="v-visible-sr js-af2022-theme-selector" name="af2022-theme" value="2"/>
                    <label for="js-theme-2" class="af-theme-button flex--item c-pointer js-af2022-hover" role="button" data-horse="3D glasses" data-squid="Digital Dimension Designers">
                            <img src="https://cdn.sstatic.net/Img/april-fools-2022/themes/theme-threed.svg?v=075b37d82fa2" alt="3D glasses theme logo"/>
                        <span class="v-visible-sr">3D glasses theme</span>
                    </label>
                    <input id="js-theme-3" type="radio" class="v-visible-sr js-af2022-theme-selector" name="af2022-theme" value="3"/>
                    <label for="js-theme-3" class="af-theme-button flex--item c-pointer js-af2022-hover" role="button" data-horse="Bookface" data-squid="Tom">
                            <img src="https://cdn.sstatic.net/Img/april-fools-2022/themes/theme-bookface.svg?v=5ec8fc034721" alt="Bookface theme logo"/>
                        <span class="v-visible-sr">Bookface theme</span>
                    </label>
                    <input id="js-theme-4" type="radio" class="v-visible-sr js-af2022-theme-selector" name="af2022-theme" value="4"/>
                    <label for="js-theme-4" class="af-theme-button flex--item c-pointer js-af2022-hover" role="button" data-horse="Hot dog stand" data-squid="The Delicious One">
                            <img src="https://cdn.sstatic.net/Img/april-fools-2022/themes/theme-hotdogstand.svg?v=27e5364436b9" alt="Hot dog stand theme logo"/>
                        <span class="v-visible-sr">Hot dog stand theme</span>
                    </label>
                    <input id="js-theme-5" type="radio" class="v-visible-sr js-af2022-theme-selector" name="af2022-theme" value="5" checked="checked"/>
                    <label for="js-theme-5" class="af-theme-button flex--item c-pointer js-af2022-hover" role="button" data-horse="Frisa Lank" data-squid="Child of the ’90s">
                            <img src="https://cdn.sstatic.net/Img/april-fools-2022/themes/theme-frisalank.svg?v=36988ec4a727" alt="Frisa Lank theme logo"/>
                        <span class="v-visible-sr">Frisa Lank theme</span>
                    </label>
                    <input id="js-theme-6" type="radio" class="v-visible-sr js-af2022-theme-selector" name="af2022-theme" value="6"/>
                    <label for="js-theme-6" class="af-theme-button flex--item c-pointer js-af2022-hover" role="button" data-horse="MariOverflow" data-squid="Luigi Luigi">
                            <img src="https://cdn.sstatic.net/Img/april-fools-2022/themes/theme-marioverflow.svg?v=5c06ec84236f" alt="MariOverflow theme logo"/>
                        <span class="v-visible-sr">MariOverflow theme</span>
                    </label>
                    <input id="js-theme-7" type="radio" class="v-visible-sr js-af2022-theme-selector" name="af2022-theme" value="7"/>
                    <label for="js-theme-7" class="af-theme-button flex--item c-pointer js-af2022-hover" role="button" data-horse="Terminal" data-squid="Neo">
                            <img src="https://cdn.sstatic.net/Img/april-fools-2022/themes/theme-terminal.svg?v=d8f89c515be8" alt="Terminal theme logo"/>
                        <span class="v-visible-sr">Terminal theme</span>
                    </label>
                    <input id="js-theme-8" type="radio" class="v-visible-sr js-af2022-theme-selector" name="af2022-theme" value="8"/>
                    <label for="js-theme-8" class="af-theme-button flex--item c-pointer js-af2022-hover" role="button" data-horse="Top Secret" data-squid="Agents J &amp; K">
                            <img src="https://cdn.sstatic.net/Img/april-fools-2022/themes/theme-topsecret.svg?v=5259a41d3acf" alt="Top Secret theme logo"/>
                        <span class="v-visible-sr">Top Secret theme</span>
                    </label>
                    <input id="js-theme-9" type="radio" class="v-visible-sr js-af2022-theme-selector" name="af2022-theme" value="9"/>
                    <label for="js-theme-9" class="af-theme-button flex--item c-pointer js-af2022-hover" role="button" data-horse="Windows 3.1" data-squid="Ms. Dos">
                            <img src="https://cdn.sstatic.net/Img/april-fools-2022/themes/theme-win31.svg?v=dd0b56d001ee" alt="Windows 3.1 theme logo"/>
                        <span class="v-visible-sr">Windows 3.1 theme</span>
                    </label>
            </div>
        </div>
        <div class="flex--item d-none sm:d-inline-block fl-equal sm:fl-grow1">
            <div class="s-select">
                <select class="ta-center js-af2022-theme-selector">
                        <option value="1">
                            Default by Stack Overflow
                        </option>
                        <option value="2">
                            3D glasses by Digital Dimension Designers
                        </option>
                        <option value="3">
                            Bookface by Tom
                        </option>
                        <option value="4">
                            Hot dog stand by The Delicious One
                        </option>
                        <option value="5" selected="selected">
                            Frisa Lank by Child of the &#x2019;90s
                        </option>
                        <option value="6">
                            MariOverflow by Luigi Luigi
                        </option>
                        <option value="7">
                            Terminal by Neo
                        </option>
                        <option value="8">
                            Top Secret by Agents J &amp; K
                        </option>
                        <option value="9">
                            Windows 3.1 by Ms. Dos
                        </option>
                </select>
            </div>
        </div>
        <div class="flex--item d-flex ai-center jc-end fl-equal sm:fl-initial">
                <div class="af-author-container bl bc-black-700 pl16 wmn1 sm:d-none">
                    <div class="p8 mn8">
                        <div class="fw-bold fw-body1 js-current-theme-name" data-current="Frisa Lank">Frisa Lank</div>
                        <div class="fs-fine js-current-theme-author" data-current="Child of the ’90s">Child of the &#x2019;90s</div>
                    </div>
                </div>
                <div class="flex--item af-minimize-bar-container">
                    <div class="ml24 sm:m0">
                        <button type="button" class="flex--item s-btn s-btn__icon s-btn__muted mxn8 js-big-bar-minimize"><svg aria-hidden="true" class="svg-icon iconClear" width="18" height="18" viewbox="0 0 18 18"><path d="M15 4.41 13.59 3 9 7.59 4.41 3 3 4.41 7.59 9 3 13.59 4.41 15 9 10.41 13.59 15 15 13.59 10.41 9 15 4.41Z"/></svg></button>
                    </div>
                </div>
        </div>
    </div>
</div>

<script type="application/json" data-role="module-args" data-module-name="entry-points/april-fools-2022.mod">{"ShowClass":"af-bar__shown","ShowSmolBar":false,"CurrentTheme":5,"IsRandomized":false,"RandomizedBodyClass":"js-april-fools-2022-random-can-you-believe-they-did-it-this-way"}</script>
<script defer src="https://cdn.sstatic.net/Js/april-fools-2022.en.js?v=de2ecf5207a9"></script>
```
