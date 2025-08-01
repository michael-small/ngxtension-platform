<h1 align="center">ngxtension - Angular Extensions</h1>
<p align="center">
<img src="/docs/public/ngxt-blue.svg" width="100px" height="100px">
</p>

[![NPM Version](https://img.shields.io/npm/v/ngxtension?style=flat-square)](https://npmjs.org/package/ngxtension)
[![NPM](https://img.shields.io/npm/dw/ngxtension?logo=npm&style=flat-square)](https://npmjs.org/package/ngxtension)

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-50-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

A modern collection of utilities for [Angular](https://angular.dev) – signals, forms, effects, DOM helpers, and more.

---

## ✨ Features & Utilities

- **Signal Utilities**: Advanced computed, derived, and async signals, signal history, lazy signals, and more.
- **DOM & Event Helpers**: Click outside, gestures, resize observer, active element, host binding, and more.
- **Forms**: Control value accessor helpers, control error, form events, if-validator, etc.
- **RxJS & Effects**: Auto effects, explicit effects, create effect, rx-effect, take-latest-from, etc.
- **Injection & DI**: Create injectable, create injection token, assert injector, inject-destroy, inject-lazy, inject-network, and more.
- **Array & Object Utilities**: Filter array, map array, reduce array, merge-from, not-pattern, etc.
- **Routing**: Inject params, inject query params, inject route data/fragment, navigation-end, linked-query-param.
- **Internationalization**: Utilities for i18n and formatting.
- **SVG & UI**: SVG sprite helpers, repeat pipe, trackBy helpers, and more.

> **See the [full documentation](https://ngxtension.netlify.app/) for a complete list and usage examples.**

---

## 🚀 Installation

```bash
npm install ngxtension
# or with pnpm
pnpm add ngxtension
```

### For Angular CLI or Nx workspaces

After installing, run the init schematic:

```bash
ng generate ngxtension-plugin:init
# or with Nx
nx generate ngxtension-plugin:init
```

---

## 📦 Usage

Import the utilities you need:

```ts
import { linkedQueryParam } from 'ngxtension/linked-query-param';
import { injectParams } from 'ngxtension/inject-params';
```

All utilities are tree-shakable and designed for Angular 16+.

---

## 📚 Documentation

- **Full API & Guides:** [ngxtension.netlify.app](https://ngxtension.netlify.app/)
- **Changelog:** [CHANGELOG.md](https://github.com/ngxtension/ngxtension-platform/blob/main/CHANGELOG.md)

---

## Version Compatibility Table

| ngxtension Version | Release Date | Angular Version Support |
|-------------------|--------------|------------------------|
| **5.x** | 2025-03-14 | >=16.0.0 |
| **4.x** | 2024-07-15 | >=16.0.0 |
| **3.x** | 2024-04-24 | >=16.0.0 |
| **2.x** | 2024-02-02 | >=16.0.0 |
| **1.x** | 2023-11-09 | >=16.0.0 |

---

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://nartc.me/"><img src="https://avatars.githubusercontent.com/u/25516557?v=4?s=100" width="100px;" alt="Chau Tran"/><br /><sub><b>Chau Tran</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=nartc" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://eneajaho.me"><img src="https://avatars.githubusercontent.com/u/25394362?v=4?s=100" width="100px;" alt="Enea Jahollari"/><br /><sub><b>Enea Jahollari</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=eneajaho" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/develite98"><img src="https://avatars.githubusercontent.com/u/43846216?v=4?s=100" width="100px;" alt="Phong Cao"/><br /><sub><b>Phong Cao</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=develite98" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.tiepphan.com/"><img src="https://avatars.githubusercontent.com/u/7151365?v=4?s=100" width="100px;" alt="Tiep Phan"/><br /><sub><b>Tiep Phan</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=tieppt" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://twitter.com/dmorosinotto"><img src="https://avatars.githubusercontent.com/u/3982050?v=4?s=100" width="100px;" alt="Daniele Morosinotto"/><br /><sub><b>Daniele Morosinotto</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=dmorosinotto" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://houseofangular.io/"><img src="https://avatars.githubusercontent.com/u/67691339?v=4?s=100" width="100px;" alt="Mateusz Stefańczyk"/><br /><sub><b>Mateusz Stefańczyk</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=va-stefanek" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/tomer953"><img src="https://avatars.githubusercontent.com/u/1807493?v=4?s=100" width="100px;" alt="Tomer953"/><br /><sub><b>Tomer953</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=tomer953" title="Documentation">📖</a> <a href="https://github.com/ngxtension/ngxtension-platform/commits?author=tomer953" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://thomaslaforge.dev/home"><img src="https://avatars.githubusercontent.com/u/30832608?v=4?s=100" width="100px;" alt="Laforge Thomas"/><br /><sub><b>Laforge Thomas</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=tomalaforge" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://yon.fun/"><img src="https://avatars.githubusercontent.com/u/6537167?v=4?s=100" width="100px;" alt="Ion Prodan"/><br /><sub><b>Ion Prodan</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=wanoo21" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/amirhosseinfaraji"><img src="https://avatars.githubusercontent.com/u/15232909?v=4?s=100" width="100px;" alt="AmirHossein"/><br /><sub><b>AmirHossein</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=amirhosseinfaraji" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/LcsGa"><img src="https://avatars.githubusercontent.com/u/58547290?v=4?s=100" width="100px;" alt="Lucas Garcia"/><br /><sub><b>Lucas Garcia</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=LcsGa" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://nevzatopcu.medium.com"><img src="https://avatars.githubusercontent.com/u/33401667?v=4?s=100" width="100px;" alt="Nevzat Topçu"/><br /><sub><b>Nevzat Topçu</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=nevzatopcu" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://ksgn.dev"><img src="https://avatars.githubusercontent.com/u/498197?v=4?s=100" width="100px;" alt="Pascal Küsgen"/><br /><sub><b>Pascal Küsgen</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=Pascalmh" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://dalenguyen.me"><img src="https://avatars.githubusercontent.com/u/14116156?v=4?s=100" width="100px;" alt="Dale Nguyen"/><br /><sub><b>Dale Nguyen</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=dalenguyen" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/vneogi199"><img src="https://avatars.githubusercontent.com/u/20491952?v=4?s=100" width="100px;" alt="Vinit Neogi"/><br /><sub><b>Vinit Neogi</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=vneogi199" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.joshmorony.com"><img src="https://avatars.githubusercontent.com/u/2578009?v=4?s=100" width="100px;" alt="Josh Morony"/><br /><sub><b>Josh Morony</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=joshuamorony" title="Documentation">📖</a> <a href="https://github.com/ngxtension/ngxtension-platform/commits?author=joshuamorony" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/cskiwi"><img src="https://avatars.githubusercontent.com/u/847540?v=4?s=100" width="100px;" alt="Glenn Latomme"/><br /><sub><b>Glenn Latomme</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=cskiwi" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://jeevanmahesha.github.io"><img src="https://avatars.githubusercontent.com/u/34814862?v=4?s=100" width="100px;" alt="Jeevan "/><br /><sub><b>Jeevan </b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=JeevanMahesha" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/diegovilar"><img src="https://avatars.githubusercontent.com/u/759416?v=4?s=100" width="100px;" alt="Diego Vilar"/><br /><sub><b>Diego Vilar</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=diegovilar" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/gianmarcogiummarra"><img src="https://avatars.githubusercontent.com/u/9169021?v=4?s=100" width="100px;" alt="Gianmarco Giummarra"/><br /><sub><b>Gianmarco Giummarra</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=gianmarcogiummarra" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://jamm.dev"><img src="https://avatars.githubusercontent.com/u/526352?v=4?s=100" width="100px;" alt="Evgeniy OZ"/><br /><sub><b>Evgeniy OZ</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=e-oz" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://beta.ajitpanigrahi.com"><img src="https://avatars.githubusercontent.com/u/19947758?v=4?s=100" width="100px;" alt="Ajit Panigrahi"/><br /><sub><b>Ajit Panigrahi</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=ajitzero" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/palexcast"><img src="https://avatars.githubusercontent.com/u/15246162?v=4?s=100" width="100px;" alt="Alexander Castillo"/><br /><sub><b>Alexander Castillo</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=palexcast" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/fiorelozere"><img src="https://avatars.githubusercontent.com/u/47506023?v=4?s=100" width="100px;" alt="Fiorelo Zere"/><br /><sub><b>Fiorelo Zere</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=fiorelozere" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.creativeid.nl"><img src="https://avatars.githubusercontent.com/u/4688582?v=4?s=100" width="100px;" alt="Robert Mulder"/><br /><sub><b>Robert Mulder</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=robbaman" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://nelsonguti.dev/"><img src="https://avatars.githubusercontent.com/u/62297014?v=4?s=100" width="100px;" alt="Nelson Gutierrez"/><br /><sub><b>Nelson Gutierrez</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=nelsongutidev" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.justinrassier.com"><img src="https://avatars.githubusercontent.com/u/1228424?v=4?s=100" width="100px;" alt="Justin Rassier"/><br /><sub><b>Justin Rassier</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=justinrassier" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/rlmestre"><img src="https://avatars.githubusercontent.com/u/277805?v=4?s=100" width="100px;" alt="Rafael Mestre"/><br /><sub><b>Rafael Mestre</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=rlmestre" title="Documentation">📖</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/swami-sanapathi"><img src="https://avatars.githubusercontent.com/u/40539126?v=4?s=100" width="100px;" alt="Swami"/><br /><sub><b>Swami</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=swami-sanapathi" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.twitch.tv/geometricjim"><img src="https://avatars.githubusercontent.com/u/708229?v=4?s=100" width="100px;" alt="Jim Drury (he/him)"/><br /><sub><b>Jim Drury (he/him)</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=geometricpanda" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/RobbyRabbitman"><img src="https://avatars.githubusercontent.com/u/54601487?v=4?s=100" width="100px;" alt="Robby Rabbitman"/><br /><sub><b>Robby Rabbitman</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=RobbyRabbitman" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.rainerhahnekamp.com"><img src="https://avatars.githubusercontent.com/u/5721205?v=4?s=100" width="100px;" alt="Rainer Hahnekamp"/><br /><sub><b>Rainer Hahnekamp</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=rainerhahnekamp" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://riegler.fr"><img src="https://avatars.githubusercontent.com/u/1300985?v=4?s=100" width="100px;" alt="Matthieu Riegler"/><br /><sub><b>Matthieu Riegler</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=JeanMeche" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/isthatME"><img src="https://avatars.githubusercontent.com/u/37561224?v=4?s=100" width="100px;" alt="isthatME"/><br /><sub><b>isthatME</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=isthatME" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/kkachniarz220"><img src="https://avatars.githubusercontent.com/u/50884231?v=4?s=100" width="100px;" alt="kkachniarz"/><br /><sub><b>kkachniarz</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=kkachniarz220" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://dafnik.me"><img src="https://avatars.githubusercontent.com/u/16242839?v=4?s=100" width="100px;" alt="Dominik"/><br /><sub><b>Dominik</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=Dafnik" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.linkedin.com/in/trong-nguyen/"><img src="https://avatars.githubusercontent.com/u/62984954?v=4?s=100" width="100px;" alt="Trong Nguyen"/><br /><sub><b>Trong Nguyen</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=nguyenphutrong" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Kiskae"><img src="https://avatars.githubusercontent.com/u/546681?v=4?s=100" width="100px;" alt="Kiskae"/><br /><sub><b>Kiskae</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=Kiskae" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/mauriziocescon"><img src="https://avatars.githubusercontent.com/u/3672842?v=4?s=100" width="100px;" alt="Maurizio Cescon"/><br /><sub><b>Maurizio Cescon</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=mauriziocescon" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/leonelvsc"><img src="https://avatars.githubusercontent.com/u/2332029?v=4?s=100" width="100px;" alt="Leonel Franchelli"/><br /><sub><b>Leonel Franchelli</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=leonelvsc" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://codepen.io/lorenzodianni/"><img src="https://avatars.githubusercontent.com/u/7217805?v=4?s=100" width="100px;" alt="Lorenzo D'Ianni"/><br /><sub><b>Lorenzo D'Ianni</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=lorenzodianni" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.berger-engineering.io"><img src="https://avatars.githubusercontent.com/u/29756792?v=4?s=100" width="100px;" alt="Michael Berger"/><br /><sub><b>Michael Berger</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=mikelgo" title="Code">💻</a> <a href="https://github.com/ngxtension/ngxtension-platform/commits?author=mikelgo" title="Documentation">📖</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/illunix"><img src="https://avatars.githubusercontent.com/u/42069493?v=4?s=100" width="100px;" alt="Maksymilian Szokalski"/><br /><sub><b>Maksymilian Szokalski</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=illunix" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Ostromecky"><img src="https://avatars.githubusercontent.com/u/37908305?v=4?s=100" width="100px;" alt="Paweł Ostromecki"/><br /><sub><b>Paweł Ostromecki</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=Ostromecky" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/mattmoos"><img src="https://avatars.githubusercontent.com/u/25790637?v=4?s=100" width="100px;" alt="Matthias Moos"/><br /><sub><b>Matthias Moos</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=mattmoos" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/ShacharHarshuv"><img src="https://avatars.githubusercontent.com/u/4821858?v=4?s=100" width="100px;" alt="Shahar Har-Shuv"/><br /><sub><b>Shahar Har-Shuv</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=ShacharHarshuv" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/MillerSvt"><img src="https://avatars.githubusercontent.com/u/143048525?v=4?s=100" width="100px;" alt="Svyatoslav Zaytsev"/><br /><sub><b>Svyatoslav Zaytsev</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=MillerSvt" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/szheleshchenko"><img src="https://avatars.githubusercontent.com/u/78230221?v=4?s=100" width="100px;" alt="Sergei Zheleshchenko"/><br /><sub><b>Sergei Zheleshchenko</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=szheleshchenko" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://andreasdorner.de"><img src="https://avatars.githubusercontent.com/u/66420187?v=4?s=100" width="100px;" alt="Andreas Dorner"/><br /><sub><b>Andreas Dorner</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=endlacer" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/PForever"><img src="https://avatars.githubusercontent.com/u/24297126?v=4?s=100" width="100px;" alt="Igor Ganov"/><br /><sub><b>Igor Ganov</b></sub></a><br /><a href="https://github.com/ngxtension/ngxtension-platform/commits?author=PForever" title="Code">💻</a></td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td align="center" size="13px" colspan="7">
        <img src="https://raw.githubusercontent.com/all-contributors/all-contributors-cli/1b8533af435da9854653492b1327a23a4dbd0a10/assets/logo-small.svg">
          <a href="https://all-contributors.js.org/docs/en/bot/usage">Add your contributions</a>
        </img>
      </td>
    </tr>
  </tfoot>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

## License

MIT


