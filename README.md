* Описание
* Основные возможности и используемые технологии
* Минимальные требования
* Начало работы
* Gulp-задачи
	* `default`
	* `build`
	* `watch`
	* `serve`
	* `pug`
	* `images`
	* `pngSprites`
	* `svgSprites`
	* `scss`
	* `jsMain`
	* `jsVendor`
	* `copy`
	* `lint`
	* `lintJs`
	* `lintPug`
	* `lintScss`
	* `zip`
* Структура
	* `src`
	* `src/images`
	* `src/images/sprites`
	* `src/images/sprites/png`
	* `src/images/sprites/svg`
	* `src/js`
	* `src/js/vendor`
	* `src/js/detect.js`
	* `src/js/globals.js`
	* `src/js/main.js`
	* `src/js/vendor.js`
	* `src/pug`
	* `src/pug/mixins`
	* `src/pug/mixins/svg.pug`
	* `src/pug/base.pug`
	* `src/resources`
	* `src/resources/fonts`
	* `src/scss`
	* `src/scss/functions`
	* `src/scss/functions/_sprites.scss`
	* `src/scss/mixins`
	* `src/scss/mixins/_retina.scss`
	* `src/scss/mixins/_sprites.scss`
	* `src/scss/mixins/_triangle.scss`
	* `src/scss/vendor`
	* `src/scss/_base.scss`
	* `src/scss/_fonts.scss`
	* `src/scss/_functions.scss`
	* `src/scss/_mixins.scss`
	* `src/scss/_sprites.hbs`
	* `src/scss/_sprites.scss`
	* `src/scss/_variables.scss`
	* `src/scss/_vendor.scss`
	* `src/scss/main.scss`
	* `src/index.pug`
	* `.babelrc`
	* `.editorconfig`
	* `.eslintignore`
	* `.eslintrc`
	* `.gitignore`
	* `.npmrc`
	* `.pug-lintrc.json`
	* `.stylelintrc`
	* `bitbucket-pipelines.yml`
	* `gulpfile.babel.js`
	* `package.json`
	* `README.md`
	* `router-config.js`
* Подключение сторонних библиотек
* Работа с изображениями
	* Работа с PNG-спрайтами
	* Работа с SVG-спрайтами
* Работа с шаблонизатором Pug
	* Базовый шаблон и создание страниц
		* `vars`
		* `meta`
		* `links`
		* `content`
		* `scripts`
	* Правила написания кода и использование линтера
* Работа со стилями
	* Правила написания кода
		* БЭМ
		* Классы состояний
		* Порядок CSS-свойств
		* Переменные
		* `@mixin` и `@extend`
		* Вендорные префиксы
	* Использование линтера
* Работа со скриптами
	* Правила написания кода
		* Глобальные переменные
		* Короткие именна переменных
		* Именование jQuery-переменных
		* jQuery-селекторы
		* Обработка событий с помощью jQuery
	* Использование линтера
* Работа с дополнительными ресурсами
	* Работа со шрифтами
		* Подключение шрифта с помощью Google Fonts
		* Конвертирование шрифта и подключение с помощью `@font-face`.
