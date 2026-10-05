# Statistical Physics 1: Interactive Demos
**경상국립대학교 물리학과 통계물리1 교과목 보조자료**

Landing page for the interactive web demos that accompany *Statistical Physics 1* (통계물리1) in the Department of Physics, Gyeongsang National University.

**Live page:** https://lshlj82.github.io/statistical-physics-1/

Created by Claude Opus 5.5, based on the lecture notes by Prof. Sang Hoon Lee.
이상훈 교수의 강의 노트를 바탕으로 Claude Opus 5.5가 만들었습니다.

## Demos · 데모 목록

| # | Demo | 데모 | Links |
|---|------|------|-------|
| 1 | Temperature and Energy | 온도와 에너지 | [demo](https://lshlj82.github.io/temperature-energy/) · [source](https://github.com/lshlj82/temperature-energy) |
| 2 | Heat and Work | 열과 일 | [demo](https://lshlj82.github.io/heat-work/) · [source](https://github.com/lshlj82/heat-work) |
| 3 | Rates of Processes | 과정의 빠르기 | [demo](https://lshlj82.github.io/nonequilibrium-basics/) · [source](https://github.com/lshlj82/nonequilibrium-basics) |
| 4 | Microstates and Macrostates | 미시 상태와 거시 상태 | [demo](https://lshlj82.github.io/statphys-basics/) · [source](https://github.com/lshlj82/statphys-basics) |
| 5 | Large Systems and Entropy | 큰 계와 엔트로피 | [demo](https://lshlj82.github.io/large-numbers-and-entropy/) · [source](https://github.com/lshlj82/large-numbers-and-entropy) |
| 6 | What Temperature Really Is | 온도란 무엇인가 | [demo](https://lshlj82.github.io/interaction-and-temperature/) · [source](https://github.com/lshlj82/interaction-and-temperature) |
| 7 | Pressure and Chemical Potential | 압력과 화학 퍼텐셜 | [demo](https://lshlj82.github.io/pressure-and-chemical-potential/) · [source](https://github.com/lshlj82/pressure-and-chemical-potential) |
| 8 | Heat Engine | 열기관 | [demo](https://lshlj82.github.io/heat-engine/) · [source](https://github.com/lshlj82/heat-engine) |
| 9 | Thermodynamic Potentials | 열역학 퍼텐셜 | [demo](https://lshlj82.github.io/thermodynamic-potentials/) · [source](https://github.com/lshlj82/thermodynamic-potentials) |
| 10 | Phase Transformation | 상변화 | [demo](https://lshlj82.github.io/phase-transformation/) · [source](https://github.com/lshlj82/phase-transformation) |

## About the page · 페이지 소개

The page is a single self-contained `index.html` with no build step. Its header animates two Einstein solids, A with 40 oscillators and B with 60, sharing 100 energy quanta. Quanta hop at random so that every microstate is equally likely. Starting with all the energy in A, the system relaxes to the macrostate with the largest multiplicity *Ω*<sub>A</sub>*Ω*<sub>B</sub> and fluctuates around it, where the two solids have the same temperature. Plots show *q*<sub>A</sub> over time and a histogram of *q*<sub>A</sub> against *Ω*<sub>A</sub>*Ω*<sub>B</sub>. The run restarts every 75 seconds.

The page supports light and dark mode and adapts to phone screens. For visitors who have reduced motion turned on, it shows a still frame instead of the animation.

페이지는 빌드 과정 없이 `index.html` 파일 하나로 이루어져 있습니다. 상단에서는 진동자 40개인 아인슈타인 고체 A와 60개인 고체 B가 에너지 양자 100개를 나눠 갖는 모습을 보여줍니다. 처음에 에너지를 모두 A에 몰아 두어도, 계는 겹침수 *Ω*<sub>A</sub>*Ω*<sub>B</sub>가 가장 큰 거시 상태, 곧 두 고체의 온도가 같아지는 곳으로 옮겨 가 그 주위에서 요동합니다.

## Running locally · 로컬에서 실행

Open `index.html` in any modern browser. Fonts load from Google Fonts when online and fall back to system fonts otherwise.

## Deploying · 배포

1. Put `index.html` and this `README.md` at the root of the repository.
2. In **Settings → Pages**, set the source to the `main` branch, root folder.
3. The page will be served at `https://lshlj82.github.io/<repository-name>/`.

## References · 참고문헌

- Daniel V. Schroeder, *An Introduction to Thermal Physics* (Oxford University Press, 2021; originally Addison Wesley Longman, 2000).
- Prof. Sang Hoon Lee, lecture notes for Statistical Physics 1. (이상훈 교수, 통계물리1 강의 노트)
