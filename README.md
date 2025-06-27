# Frontend Mentor - QR code component

![Design preview for the QR code component coding challenge](./preview.jpg)

---

### 🧠 What I've learned from this project:

- Centering a div within the viewport: I learned how to precisely center an element using absolute positioning and CSS transforms:

```css
position: absolute;
top: 50%;
left: 50%;
transform: translate(-50%, -50%);
```

- Using REM units for scalable design: I adopted rem units for sizing and spacing to ensure consistency and scalability across different screen sizes. Since rem is relative to the root font size, it allows for more responsive and accessible layouts.

```css
.qr-image {
    width: 18rem;
    height: 18rem;
    border-radius: 1.25rem;
    margin-bottom: 1.5rem;
}
```

- Implementing fallback fonts: I applied a font stack to ensure graceful degradation if the preferred font is unavailable:

```css
.card-title {
    font-family: "Outfit", Times;
}
```

- Using box-sizing: border-box for predictable layout behavior: Setting box-sizing: border-box helped ensure that an element’s width and height include padding and borders, preventing unexpected layout shifts.
