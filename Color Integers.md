# Color Integers

In the world of computer graphics, colors are often represented by integers within the range of 0 to 16,777,215. This range is derived from the 24-bit color model, which allocates 8 bits for each of the three primary colors: red, green, and blue (RGB).

Each primary color can have a value between 0 and 255, leading to (256 x 256 x 256 = 16,777,216) possible combinations. The integer value for a color is typically calculated by combining the values of these three components. For instance, a color represented by (R, G, B) can be converted to an integer using the formula:

\[ \text{Color Integer} = (R \times 256^2) + (G \times 256) + B \]

Here’s how it breaks down:

- **0** represents the color black (RGB: 0, 0, 0).
- **16,777,215** represents the color white (RGB: 255, 255, 255).

Intermediate values correspond to other colors, with different combinations of red, green, and blue intensities producing the full spectrum of visible colors. This system allows for precise color representation and manipulation in digital media, making it fundamental in fields like graphic design, digital art, and computer science.

0 - 16777215 

| Color   | Integer    |
| ------- | ---------- |
| White   | 16777215   |
| Black   | 0          |
| Gray    | 8421504    |
| Silver  | 12632256   |
| Red     | 255        |
| Yellow  | 65535      |
| Lime    | 65280      |
| Aqua    | 16776960   |
| Blue    | 16711680   |
| Maroon  | 128        |
| Green   | 32768      |
| Olive   | 32896      |
| Navy    | 8388608    |
| Purple  | 8388736    |
| Teal    | 8421376    |
