#Reflection
1. Explain the difference between flex-direction: row and flex-direction: column.
The main difference is which the Main Axis points. In Flexbox, your items always follow the Main Axis, while the Cross Axis runs perpendicular to it. Row has a horizontal main axis and vertical cross axis. Column has a vertical main axis and a horizontal cross axis.
2. Why is it important to use relative units (like %, vh, or rem) instead of fixed pixels (px) for
responsive design?
It is important because those units are scalable, so if you had to resize them varying on the device or screen size, the image will match the frame it is in and scale into it rather than cutting out the frame edges.
3. I asked ChatGPT "How would I style this grid (gave it code context) consistent to the other css" and it did not give me any logical errors. A block it gave me was this: .projects-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr); /* 3 columns on desktop */
  grid-gap: 16px; /* consistent spacing */
  margin-top: 12px;
}
but I did not have to change anything.