# Glassmorphism

![image screen](https://user-images.githubusercontent.com/3937792/105679223-ba0df080-5f20-11eb-843c-7bb2385c6fcc.png)

Iseng aja sambil nunggu online meeting dimulai.

style CSS untuk efek glassmorphism:

```css
section .color {
    position: absolute;
    filter: blur(150px);
}

section .color:nth-child(1) {
    top: -350px;
    width: 600px;
    height: 600px;
    background: #9c88ff;
}

section .color:nth-child(2) {
    bottom: -150px;
    left: 100px;
    width: 500px;
    height: 500px;
    background: #fbc531;
}

section .color:nth-child(3) {
    bottom: 50px;
    right: 100px;
    width: 500px;
    height: 500px;
    background: #e84118;
}
```

