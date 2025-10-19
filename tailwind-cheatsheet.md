# 🌈 Tailwind CSS Cheat Sheet

## 🎨 Colors
```html
text-blue-500     <!-- Text color -->
bg-gray-100       <!-- Background color -->
border-red-400    <!-- Border color -->
```

---

## ✍️ Typography
```html
text-xl           <!-- Text size -->
font-semibold     <!-- Font weight -->
italic            <!-- Italic text -->
tracking-wide     <!-- Letter spacing -->
leading-loose     <!-- Line height -->
```

---

## 📏 Spacing (Padding & Margin)
```html
p-4               <!-- Padding on all sides -->
px-8              <!-- Horizontal padding -->
py-2              <!-- Vertical padding -->
m-6               <!-- Margin on all sides -->
mx-auto           <!-- Center horizontally -->
space-x-4         <!-- Horizontal spacing between children -->
space-y-2         <!-- Vertical spacing between children -->
```

---

## 🧱 Layouts

### 🔹 Flexbox
```html
flex flex-col             <!-- Flex container (column direction) -->
justify-center            <!-- Center vertically -->
items-center              <!-- Center horizontally -->
flex-row                  <!-- Horizontal direction -->
justify-between           <!-- Space between items -->
items-center              <!-- Align items center vertically -->
flex-wrap                 <!-- Wrap items to next line -->
```

### 🔹 Grid
```html
grid grid-cols-3          <!-- 3 columns -->
gap-4                     <!-- Gap between cells -->
col-span-2                <!-- Element spans 2 columns -->
row-span-1                <!-- Element spans 1 row -->
```

---

## 🌈 Backgrounds & Gradients
```html
bg-gradient-to-r           <!-- Gradient left → right -->
from-purple-500            <!-- Gradient start color -->
to-pink-500                <!-- Gradient end color -->
bg-cover                   <!-- Background image covers all -->
bg-center                  <!-- Center background image -->
```

---

## 🔲 Borders & Radius
```html
border                     <!-- Adds border -->
border-gray-300            <!-- Border color -->
rounded-lg                 <!-- Large rounded corners -->
border-dashed              <!-- Dashed border -->
rounded-full               <!-- Fully rounded (circle) -->
```

---

## 📱 Responsive Breakpoints
| Prefix | Min Width | Example Usage |
|---------|------------|---------------|
| `sm:` | ≥ 640px | `sm:text-sm` |
| `md:` | ≥ 768px | `md:text-base` |
| `lg:` | ≥ 1024px | `lg:text-lg` |
| `xl:` | ≥ 1280px | `xl:text-xl` |
| `2xl:` | ≥ 1536px | `2xl:text-2xl` |

Example:
```html
sm:p-2 md:p-4 lg:p-6
```

---

## 📐 Sizing & Position
```html
min-h-screen w-full       <!-- Full height and width -->
relative z-2              <!-- Relative position with z-index -->
absolute top-0 left-0     <!-- Absolute positioning -->
flex min-h-screen flex-col <!-- Full-screen flex container -->
flex flex-1               <!-- Flexible element fills remaining space -->
```

---

## ✅ Common Layout Examples

### Center Content
```html
<div class="flex items-center justify-center min-h-screen">
  <p class="text-xl font-semibold text-blue-500">Centered Text</p>
</div>
```

### Simple Grid
```html
<div class="grid grid-cols-3 gap-4">
  <div class="bg-gray-100 p-4">1</div>
  <div class="bg-gray-100 p-4">2</div>
  <div class="bg-gray-100 p-4">3</div>
</div>
```

---

**💡 Tip:** Combine classes freely — Tailwind is fully composable.  
Example:  
```html
<button class="bg-gradient-to-r from-purple-500 to-pink-500 text-white font-semibold py-2 px-6 rounded-lg shadow-lg">
  Click Me
</button>
```

---

📘 *Made for quick reference by Iván Bazaga*
