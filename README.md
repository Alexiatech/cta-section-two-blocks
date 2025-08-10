# cta-section-two-blocks
Leapforce case opdracht

```css
button:hover {
  background-color: white; /* Nieuwe hoverkleur */
  color: black;
  transition: background-color 0.3s ease, color 0.3s ease;
}

.box {
  opacity: 0;
  transform: translateX(50px);
  animation: slideInRight 0.8s ease forwards;
  animation-delay: 0.7s;
}

@keyframes slideInRight {
  to {
    opacity: 1;
    transform: translateX(0);
  }
}
```
