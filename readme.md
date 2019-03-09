# Spin

```html
<div class="spin"/>
```

```css
@keyframes spin-effect {
    0% {
        transform: rotate(0deg);
    }

    100% {
        transform: rotate(360deg);
    }
}

.spin {
    display: inline-block; // has width and height 
    width: 30px;
    height: 30px;
    border: 4px solid #eee;
    border-radius: 50%;
    border-left-color: #7983ff;
    animation: spin-effect 1.2s linear infinite;
}
```

## Animation

* animation-name
* animation-time: the length of time it takes for an animation to complete one cycle