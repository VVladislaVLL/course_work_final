# Plants vs Zombies

Демо: https://course-work-game.netlify.app/

Документация движка: https://github.com/VVladislaVLL/course_work_final/blob/main/src/engine/docs.md

Для запуска игры:

` $ npm install `

` $ npm run start `


## Стек технологий

![стек технологий](https://user-images.githubusercontent.com/70816049/107280288-947cfd00-6a71-11eb-896f-bab65ec1ff4a.png)

Игра написана на TypeScript для более прозрачного кода и избежания ошибок.

Для сборки проекта используется Webpack и разного плана загрузчики для картинок, музыки, трансформации SCSS в CSS.

Для отлова ошибок ESLint с конфигурацией airbnb-typescript/base. Эта настройка позволяет использовать TypeScript в полной мере в отличие от airbnb-base.

Для хранения данных игра обращается к LocalStorage

Для отрисовки всех элементов игры задействован HTML5 элемент canvas. Он позволяет содавать анимации при помощи покадровой отрисовки на canvas-элементе.

В данной игре используется кастомный движок на основе canvas.

Для добавления полей ввода на canvas использован [canvasinput](https://www.npmjs.com/package/canvasinput)
