# ✏️ PencilSketchFX

**An interactive image stylization tool built with OpenCV**  
Turn your photos into elegant pencil sketches with real-time controls!

![Demo GIF](demo.gif)

---

## 🌟 Features

- 🎛️ **Interactive Sliders**  
  Adjust **blur intensity** (`ksize`) and **gamma correction** for personalized sketch results.

- 🧠 **Custom Gamma Correction**  
  Fine-tunes contrast and lightness for more expressive effects.

- ⚙️ **Real-Time Preview**  
  Watch your image update live as you tweak the controls.

- 📷 **Easy to Use**  
  Just load an image and start experimenting!

---

## 🧪 How It Works

1. **Grayscale Conversion**  
   Converts the original image to grayscale.

2. **Blurring**  
   Applies a `GaussianBlur` with customizable `ksize`.

3. **Division Highlighting**  
   Uses `cv2.divide(gray, blurred)` to emphasize edges — mimicking pencil strokes.

4. **Gamma LUT Correction**  
   Applies a gamma correction Look-Up Table (LUT) to control sketch brightness and contrast.


