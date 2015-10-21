##  CSS - prefixos de extensão

Normalmente, alguns browsers não possuem a implementação de todas as propriedades do CSS e para que seja possível, é necessário utilizar os prefixos de cada browser.

```css
-moz-, -ms-, -webkit-, -o- e -khtml-*
```

um exemplo seria a propriedade `flex`:

```css
.my-flex-class {
  width: 20%;            /* For old syntax, otherwise collapses. */
  -webkit-box-flex: 1;   /* OLD - iOS 6-, Safari 3.1-6 */
      -webkit-flex: 1;   /* Safari 6.1+. iOS 7.1+, BB10 */
          -ms-flex: 1;   /* IE 10 */
              flex: 1;   /* NEW, Spec - Firefox, Chrome, Opera */
}
```
