Элемент `.scrolling-wrapper-flexbox` предназначен для 
отображения списка элементов в виде прокручиваемой полосы с 
использованием flexbox.

Этот компонент позволяет легко создавать длинные списки 
элементов, которые могут быть прокручены горизонтально по 
мере их роста. Он поддерживает горизонтальную прокрутку и 
адаптируется к различным размерам экрана.

```html
<ul class="scrolling-wrapper-flexbox">
    <li class="card">Обеспыливание</li>
    <li class="card">Обеспыливание</li>
    <li class="card">Обеспыливание</li>
    <!-- Добавьте больше элементов -->
</ul>
```

```css
.scrolling-wrapper-flexbox {
    display: flex;
    flex-wrap: nowrap;
    overflow-x: auto;
}
```
