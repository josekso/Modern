![Modern Theme](https://github.com/josekso/Modern/blob/main/Modern-theme.png)

# Modern Theme for Home Assistant

A clean, minimalist, and highly polished user interface for Home Assistant. This theme focuses on soft neumorphic shadows, subtle gradients, and high scannability to bring a premium, modern feel to your smart home dashboard.


## 🌟 Features

* **Advanced State Contrast (New):** Cards intuitively shift appearance based on their state to dramatically improve visibility:
  * **ON / Active:** The card turns crisp white, making active devices immediately pop out.
  * **OFF / Inactive:** The card blends softly with a shaded background, cleanly receding into the layout.

![Buttons](https://github.com/josekso/Modern/blob/main/buttons.png)

  * **🚨 Error / Unavailable Status:** Cards change to a soft red background when a device hits an error or goes unavailable, allowing for immediate troubleshooting.

![Error button](https://github.com/josekso/Modern/blob/main/error.png)

* **Dual Mode:** Seamless support for both **Light** and **Dark** modes.
* **Neumorphic Depth:** Beautifully crafted card shadows and soft background contrasts.
* **Card-Mod Power:** Leveraging `card-mod` to fine-tune states, sliders, and borders for a cohesive layout.
* **Optimized Typography:** Designed to look stunning with modern, geometric sans-serif typefaces.

---

## 🎨 Typography

For the ultimate visual experience, this theme is optimized to work with the following typography options from Google Fonts:

* **[Google Sans](https://fonts.google.com/specimen/Google+Sans):** Clean, professional, and balanced geometric shapes.
* **[Figtree](https://fonts.google.com/specimen/Figtree?preview.script=Latn&query=figtree):** A crisp, highly legible alternative that looks incredible on dashboards.

---

## 🛠️ Prerequisites & Dependencies

To ensure all elements, custom states, and styling render exactly as shown in the screenshots, you **must install** the following frontend plugin via HACS:

1.  **Card-mod** by `@thomasloven` (Available in HACS).

---

## 🚀 Installation

### Option 1: Custom Repository (HACS)
1. Go to **HACS** in your Home Assistant instance.
2. Click the **three dots** in the top-right corner and select **Custom repositories**.
3. Paste the URL of this repository.
4. Select **Theme** as the category and click **Add**.
5. Find **Modern Theme** in the list and click **Download**.

### Option 2: Manual Installation
1. Download the `themes/modern.yaml` file from this repository.
2. Paste it into your Home Assistant directory under `themes/modern/modern.yaml`.
3. Add the following to your `configuration.yaml` if you haven't already:
   ```yaml
   frontend:
     themes: !include_dir_merge_named themes

---

## 📷 Captures
   
![Light mode](https://github.com/josekso/Modern/blob/main/light-mode.png)
![Dark mode](https://github.com/josekso/Modern/blob/main/dark-mode.png)
