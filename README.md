# CSS Basic

- [ ] block / inline

```
body {
    background-color: tomato;
}
div {
    display: inline;
    height: 100px; /* none prop with inline */
    width: 100px; /* none prop with inline */
    background-color: white;
}
span {
    display: block;
    background-color: aqua;
}
```

- [ ] margin
- [ ] padding
- [ ] border
- [ ] classes

- [ ] inline-block

## Flex

- [ ] flex
  1. 부모요소에만 속성을 명시
  2. 메인(main)축 / 교차(cross)축
- [ ] justify-content
- [ ] align-items

- [ ] flex-direction: row;
- [ ] flex-wrap:nowrap;

## Positions

- [ ] position: fixed;
- [ ] position: relative;
- [ ] position: absolute; /_ with relateve_/

## Pseudo selectors

- [ ] \*:last-child
- [ ] \*:first-child
- [ ] \*:nth-child(n)
- [ ] \*:nth-child(odd|even)
- [ ] \*:nth-child(2n | 3n+1)
- [ ] \*:active
- [ ] \*:hover
- [ ] \*:focus
- [ ] \*:visitied
- [ ] \*:focus-within /_ eg. form _/

## Custom Properties (Variables)

```
:root{
    --main-color:#ff0000;
}
*{
    color : val(--main-color);
}
```

- [ ] transition : color 10s ease-in-out
      https://matthewlein.com/tools/ceaser
- [ ] transform : rotateZ(30deg)
      // transform MDN
- [ ] animation
      // https://animista.net/

```
@keyframes myFlip {
    from {
        transform: rotateZ(0);
    }
    to {
        transform: rotateZ(360deg);
    }
}
div{
    animation: myFlip 2s ease-in-out infinite;
}
```
