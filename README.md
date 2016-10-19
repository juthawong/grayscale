# При наведении мыши плавно делает Ч/Б элемент цветным

## Установка через composer
```json
{
	"require": {
		"narical/grayscale":"~1"
	}
}
```

## Использование
Есть поддержка автоматического подключения с помощь. [infrajs/collect](https://github.com/infrajs/collect)
Можно подключить вручную:
```html
<link rel="stylesheet" href="/vendor/narical/grayscale/grayscale.css">
```

HTML-элементу необходимо задать класс ```grayscale``` - он начинает отображается в оттенках серого,
при наведении мыши плавно становясь цветным.
