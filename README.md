# 🌱 Garden Fertilizer Calculator

A simple, user-friendly calculator that helps home gardeners convert soil test recommendations into practical measurements for their garden beds.

## 🎯 What It Does

Converts professional soil test results (like "Apply 1.5 lbs/1000 ft² Nitrogen") into easy kitchen measurements (like "Apply 1 cup of blood meal to your 40 sq ft bed").

Perfect for home gardeners with beds ranging from 10-200 square feet who want to accurately apply fertilizers without doing complex math.

## ✨ Features

- **3-Step Simple Interface**: Enter soil test results → Select fertilizer → Enter bed size → Get results
- **Smart Unit Selection**: Automatically displays the most practical measurement (tablespoons, cups, ounces, or pounds)
- **Common Fertilizers Pre-loaded**: Quick selection for blood meal, bone meal, urea, and more
- **Bed Size Calculator**: Built-in length × width calculator
- **Works Offline**: No internet connection required after initial load
- **Mobile Friendly**: Use it right in your garden on phone or tablet
- **No Installation**: Just open in any web browser

## 🚀 How to Use

### Online (Recommended)
Visit: **[https://fertilizer-calculator.github.io/Fertilizer-Calculator/]**

### Offline
1. Download `index.html`
2. Double-click to open in your browser
3. Works completely offline!

## 📖 Example Usage

**Scenario:** Your soil test says "Apply 1.5 lbs/1000 ft² Nitrogen"

**Steps:**
1. Enter **1.5** in Application Rate
2. Select **Blood Meal (13% N)** from dropdown (or enter 13 manually)
3. Enter your bed size (e.g., 4 ft × 10 ft = **40** sq ft)
4. **Result:** "Apply 0.9 cups to your 40 sq ft bed"

That's it! No complex calculations needed.

## 🔢 Understanding Fertilizer Numbers

Fertilizer bags show three numbers like **21-0-0** or **10-10-10**:
- **First number** = Nitrogen (N) %
- **Second number** = Phosphorus (P) %
- **Third number** = Potassium (K) %

Example: A bag labeled 21-0-0 means 21% Nitrogen. Enter **21** in the Fertilizer % field.

## 🌾 Common Fertilizers

### Nitrogen Sources
- **Organic:** Blood meal (13%), Feather meal (10%), Fish emulsion (5%)
- **Synthetic:** Ammonium sulfate (21%), Urea (46%)

### Phosphorus Sources
- **Organic:** Bone meal (15%), Rock phosphate (3%)
- **Synthetic:** Triple superphosphate (45%)

### Potassium Sources
- **Organic:** Kelp meal (varies), Wood ash (varies)
- **Synthetic:** Muriate of potash (60%)

## 🛠️ Technical Details

- **Technology:** Pure HTML/CSS/JavaScript - no dependencies
- **Browser Support:** Works in all modern browsers (Chrome, Firefox, Safari, Edge)
- **File Size:** ~15 KB (single file)
- **Privacy:** All calculations done locally - no data sent anywhere

## 📐 Calculation Verification

The calculator uses standard agronomic formulas:

1. Convert soil test recommendation to per-square-foot basis: `(lbs/1000) × 16 = oz/sq ft`
2. Adjust for fertilizer percentage: `oz_pure ÷ (percentage/100) = oz_product`
3. Multiply by bed area: `oz_product × sq_ft = total_oz`

All calculations have been verified against professional soil test calculators and work backwards to confirm accuracy.

## 💡 Tips for Best Results

- **Always get a soil test** before applying fertilizers - guessing can harm plants
- **Measure carefully** - over-application can burn plants
- **Apply evenly** - divide bed into sections for uniform coverage
- **Water after application** - helps nutrients reach roots
- **Use kitchen scale** for amounts over 1 pound for better accuracy

## 🤝 Contributing

Found a bug or have a suggestion? Feel free to:
- Open an issue on GitHub
- Submit a pull request
- Send feedback

## 📄 License

This project is released into the public domain. Use it freely for any purpose.

## 🙏 Credits

Created to help home gardeners make sense of soil test results and apply fertilizers accurately and safely.

## 📞 Support

If you have questions about:
- **Using the calculator**: See the built-in instructions on the calculator page
- **Interpreting soil tests**: Consult with your local agricultural extension office
- **Fertilizer recommendations**: Always follow your soil test lab's recommendations

---

**Happy Gardening! 🌻**

Last updated: February 2026
