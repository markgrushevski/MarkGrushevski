<div class="header">
 <img alt="Flying bee" src="./assets/bee.gif"/>
 <img alt="Most used languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=markgrushevski&layout=donut&langs_count=6&theme=transparent&hide_border=true"/>
</div>

<h1>My</h1>
<label style="display: block; text-align: end; color: #60606060; text-decoration-line: underline; cursor: pointer;"><input type="checkbox" style="cursor: pointer;"/>stop anim</label>

<div class="body">
 <div class="body__row" style="z-index: 4">
  <img alt="Typescript" src="./assets/ts.svg" title="Typescript"/>
  <img alt="Javascript" src="./assets/js.svg" title="Javascript"/>
  <img alt="HTML" src="./assets/html5.svg" title="HTML"/>
  <img alt="CSS" src="./assets/css3.svg" title="CSS"/>
  <img alt="Scss" src="./assets/sass.svg" title="Scss"/>
 </div>

 <div class="body__row" style="z-index: 3">
  <img alt="Git" src="./assets/git.svg" title="Git" />
  <img alt="Postman" src="./assets/postman.svg" title="Postman" />
  <img alt="Photoshop" src="./assets/ps.svg" title="Photoshop" />
  <img alt="Figma" src="./assets/figma.svg" title="Figma" />
  <img alt="Vite" src="./assets/vitejs.svg" title="Vite" />
  <img alt="Pinia" src="./assets/pinia.svg" title="Pinia" />
  <img alt="Vue" src="./assets/vuejs.svg" title="Vue"/>
 </div>

 <div class="body__row" style="z-index: 2">
  <!--<img alt="Jest" src="./assets/jest.svg" title="Jest" />-->
  <!--<img alt="Storybook" src="./assets/storybook.svg" title="Storybook" />-->
  <img alt="Vuetify" src="./assets/vuetify.svg" title="Vuetify" />
  <img alt="Rollup" src="./assets/rollup.svg" title="Rollup" />
  <img alt="NodeJS" src="./assets/nodejs.svg" title="NodeJS" />
  <img alt="NestJS" src="./assets/nestjs.svg" title="NestJS" />
  <img alt="Grafana" src="./assets/grafana.svg" title="Grafana" />
 </div>
</div>

<h1 style="text-align: end">Tech stack</h1>

<div class="body">

</div>

<style>

.header {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.body {
    position: relative;

    width: 100%;
    height: min-content;

    display: flex;
    flex-direction: column;
    gap: 16px;

    overflow: hidden;
}

.body__row {
    position: relative;

    width: 100%;
    height: 60px;

    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 24px;
}

.body__row::before {
    content: '';
    box-sizing: content-box;

    position: absolute;
    left: 0;
    z-index: -1;

    width: 50%;
    height: 50%;
}

.body__row:nth-of-type(odd)::before {
    top: 0;
    border-bottom: 1px solid #60606060;
    border-bottom-left-radius: 100px;
}

.body__row:nth-of-type(even)::before {
    top: 50%;
    border-top: 1px solid #60606060;
    border-top-left-radius: 100px;
}

.body__row::after {
    content: '';
    box-sizing: content-box;

    position: absolute;
    left: 50%;
    z-index: -1;

    width: 50%;
    height: 50%;
}

.body__row:nth-of-type(odd)::after {
    top: 50%;
    border-top: 1px solid #60606060;
    border-top-right-radius: 100px;
}

.body__row:nth-of-type(even)::after {
    top: 0;
    border-bottom: 1px solid #60606060;
    border-bottom-right-radius: 100px;
}

.body__row:nth-of-type(odd) {
    flex-direction: row;
}

.body__row:nth-of-type(even) {
    flex-direction: row-reverse;
}

.body__row img {
    --delay-step: 0.6;
    --delay: 1.75;
    --w-img: 48px;
    --gap-img: 24px;

    position: absolute;
    top: 12.5%;

    width: var(--w-img);
    height: var(--w-img);

    transition: all 0.225s ease-out;

    animation-duration: 15s;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
}

.body__row:nth-of-type(odd) img:nth-of-type(1) {
    left: 0;
    animation-delay: calc((var(--delay) - var(--delay-step) * 0) * 1s);
}

.body__row:nth-of-type(odd) img:nth-of-type(2) {
    left: calc(1 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 1) * 1s);
}

.body__row:nth-of-type(odd) img:nth-of-type(3) {
    left: calc(2 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 2) * 1s);
}

.body__row:nth-of-type(odd) img:nth-of-type(4) {
    left: calc(3 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 3) * 1s);
}

.body__row:nth-of-type(odd) img:nth-of-type(5) {
    left: calc(4 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 4) * 1s);
}

.body__row:nth-of-type(odd) img:nth-of-type(6) {
    left: calc(5 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 5) * 1s);
}

.body__row:nth-of-type(odd) img:nth-of-type(7) {
    left: calc(6 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 6) * 1s);
}

.body__row:nth-of-type(odd) img:nth-of-type(8) {
    left: calc(7 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 7) * 1s);
}

.body__row:nth-of-type(odd) img:nth-of-type(9) {
    left: calc(8 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 8) * 1s);
}

.body__row:nth-of-type(odd) img:nth-of-type(10) {
    left: calc(9 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 9) * 1s);
}

.body__row:nth-of-type(even) img:nth-of-type(1) {
    right: 0;
    animation-delay: calc((var(--delay) - var(--delay-step) * 0) * 1s);
}

.body__row:nth-of-type(even) img:nth-of-type(2) {
    right: calc(1 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 1) * 1s);
}

.body__row:nth-of-type(even) img:nth-of-type(3) {
    right: calc(2 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 2) * 1s);
}

.body__row:nth-of-type(even) img:nth-of-type(4) {
    right: calc(3 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 3) * 1s);
}

.body__row:nth-of-type(even) img:nth-of-type(5) {
    right: calc(4 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 4) * 1s);
}

.body__row:nth-of-type(even) img:nth-of-type(6) {
    right: calc(5 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 5) * 1s);
}

.body__row:nth-of-type(even) img:nth-of-type(7) {
    right: calc(6 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 6) * 1s);
}

.body__row:nth-of-type(even) img:nth-of-type(8) {
    right: calc(7 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 7) * 1s);
}

.body__row:nth-of-type(even) img:nth-of-type(9) {
    right: calc(8 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 8) * 1s);
}

.body__row:nth-of-type(even) img:nth-of-type(10) {
    right: calc(9 * (var(--w-img) + var(--gap-img)));
    animation-delay: calc((var(--delay) - var(--delay-step) * 9) * 1s);
}

:not(:has(:checked)) .body:hover .body__row:nth-of-type(odd) img {
    top: calc(12.5% * -8);
    left: 0;
    opacity: 0;
    animation-name: slideRight;
}

:not(:has(:checked)) .body:hover .body__row:nth-of-type(even) img {
    top: calc(12.5% * -8);
    right: 0;
    opacity: 0;
    animation-name: slideLeft;
}

:has(:checked) .body__row img:hover {
    cursor: help;
}

.body__row img:active {
    animation-play-state: paused;
}

@keyframes slideRight {
    from {
        opacity: 1;
    }

    5% {
        top: 12.5%;
        left: 0;
    }

    30.5% {
        top: 12.5%;
        left: calc(95% - var(--w-img));
    }
    31.75% {
        top: calc(12.5% * 3);
        left: calc(97.5% - var(--w-img));
    }
    33% {
        top: calc(12.5% * 6);
        left: calc(100% - var(--w-img));
    }
    34.25% {
        top: calc(12.5% * 9);
        left: calc(97.5% - var(--w-img));
    }
    35.5% {
        top: calc(12.5% * 11);
        left: calc(95% - var(--w-img));
    }

    63.5% {
        top: calc(12.5% * 11);
        left: 5%;
    }
    64.75% {
        top: calc(12.5% * 13);
        left: 2.5%;
    }
    66% {
        top: calc(12.5% * 16);
        left: 0;
    }
    67.25% {
        top: calc(12.5% * 19);
        left: 2.5%;
    }
    68.5% {
        top: calc(12.5% * 21);
        left: 5%;
    }

    96.5% {
        top: calc(12.5% * 21);
        left: calc(95% - var(--w-img));
    }
    97.75% {
        top: calc(12.5% * 23);
        left: calc(97.5% - var(--w-img));
    }
    99% {
        display: none;
        top: calc(12.5% * 31);
        left: calc(100% - var(--w-img));
    }

    to {
        display: none;
        top: calc(12.5% * -6);
        left: 0;
        opacity: 1;
    }
}

@keyframes slideLeft {
    from {
        opacity: 1;
    }

    5% {
        top: 12.5%;
        right: 0;
    }

    30.5% {
        top: 12.5%;
        right: calc(95% - var(--w-img));
    }
    31.75% {
        top: calc(12.5% * 3);
        right: calc(97.5% - var(--w-img));
    }
    33% {
        top: calc(12.5% * 6);
        right: calc(100% - var(--w-img));
    }
    34.25% {
        top: calc(12.5% * 9);
        right: calc(97.5% - var(--w-img));
    }
    35.5% {
        top: calc(12.5% * 11);
        right: calc(95% - var(--w-img));
    }

    63.5% {
        top: calc(12.5% * 11);
        right: 5%;
    }
    64.75% {
        top: calc(12.5% * 13);
        right: 2.5%;
    }
    66% {
        top: calc(12.5% * 16);
        right: 0;
    }
    67.25% {
        top: calc(12.5% * 19);
        right: 2.5%;
    }
    68.5% {
        top: calc(12.5% * 21);
        right: 5%;
    }

    96.5% {
        top: calc(12.5% * 21);
        right: calc(95% - var(--w-img));
    }
    97.75% {
        top: calc(12.5% * 23);
        right: calc(97.5% - var(--w-img));
    }
    99% {
        display: none;
        top: calc(12.5% * 31);
        right: calc(100% - var(--w-img));
    }

    to {
        display: none;
        top: calc(12.5% * -6);
        right: 0;
        opacity: 1;
    }
}
</style>
