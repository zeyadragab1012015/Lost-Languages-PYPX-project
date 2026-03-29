# Lost-Languages-PYPX-project

A tiny starter sketch you can run in **Processing (Java mode)**.

## Processing example (Java mode)

Paste this into a Processing sketch:

```java
void setup() {
  size(600, 400);
  smooth();
  textAlign(CENTER, CENTER);
  textSize(28);
}

void draw() {
  background(20, 28, 40);

  // Pulsing color
  float t = millis() * 0.002;
  float pulse = (sin(t) + 1) * 0.5;
  fill(120 + 120 * pulse, 180, 255);

  text("Hello, Processing!", width / 2, height / 2);
}
```

## How to apply this code (step-by-step)

1. Install and open the **Processing IDE**.
2. In the top-right mode selector, choose **Java** (this example is Java mode).
3. Click **File → New** to create a new sketch.
4. Replace the default code in the editor with the code block above.
5. Save the sketch (for example, `LostLanguagesDemo`).
   - Processing will create a sketch folder and a `.pde` file with the same name.
6. Click the **Run** button (triangle icon).
7. A new window should open and display **"Hello, Processing!"**.

## Notes

- This snippet is for **Processing Java mode**.
- It will not run in **Processing Python Mode** without conversion.
