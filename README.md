# Glassmorphism

![image screen]()

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

