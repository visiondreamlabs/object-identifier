# 🔍 Object Identifier

A lightweight yet powerful web-based object recognition application that runs entirely in your browser. Using state-of-the-art machine learning, it identifies animals, plants, everyday objects, and more in real-time.

## 🚀 Key Features

* **Live Detection:** Use your webcam for instant identification of objects around you.
* **File Upload:** Upload any image file from your computer or mobile device.
* **Smart Clipboard Support:** Paste images directly from your clipboard using `CTRL+V` or the dedicated "Paste" button.
* **Multilingual Support (CZ/EN):** Features an extensive dictionary (`TRANSLATIONS`) that maps hundreds of MobileNet classes into Czech.
* **Privacy Focused:** All processing happens locally on your machine. No images are ever sent to a server.

## 🛠️ Built With

* **TensorFlow.js:** For running machine learning models in the browser.
* **MobileNet v2:** A deep convolutional neural network optimized for speed and efficiency.
* **HTML5/CSS3/JS:** A clean, responsive frontend with no external dependencies required.
* **Inter Font:** Modern, highly readable typography.

## 📦 How to Run

The application requires no backend installation or complex setup.

1. Download the `index.html` file.
2. Open it in any modern web browser.
3. Wait a few seconds for the neural network to initialize.
4. Start identifying!

## 💡 How It Works

The app utilizes the **MobileNet** model, a lightweight architecture trained on the **ImageNet** dataset. A custom `translateTerm()` function handles the localization, ensuring that raw English class names are displayed in their Czech equivalents when available.

---
**Note:** For the camera feature to work, the application must be served via `localhost` or a secure `https` connection due to browser security policies.

# 🔍 Rozpoznávač objektů

Jednoduchá, ale výkonná webová aplikace pro rozpoznávání objektů v reálném čase přímo v prohlížeči. Aplikace využívá strojové učení k identifikaci zvířat, rostlin, předmětů denní potřeby a mnoho dalšího.

## 🚀 Klíčové vlastnosti

* **Živá detekce:** Použijte svou webkameru pro okamžitou identifikaci objektů kolem vás.
* **Nahrávání souborů:** Nahrajte libovolný obrázek z počítače nebo telefonu.
* **Chytrá schránka (Clipboard):** Podpora vkládání obrázků přímo pomocí `CTRL+V` nebo tlačítka pro vložení.
* **České rozhraní:** Obsahuje rozsáhlý slovník (`TRANSLATIONS`), který překládá stovky anglických názvů z modelu MobileNet do češtiny.
* **Soukromí na prvním místě:** Veškeré výpočty probíhají lokálně ve vašem prohlížeči. Žádné obrázky se neposílají na server.

## 🛠️ Použité technologie

* **TensorFlow.js:** Knihovna pro spouštění modelů strojového učení v JavaScriptu.
* **MobileNet v2:** Předtrénovaná hluboká konvoluční neurální síť optimalizovaná pro prohlížeč.
* **HTML5/CSS3/JS:** Čistý frontend bez nutnosti instalace dalších závislostí.
* **Inter Font:** Moderní a čitelná typografie.

## 📦 Jak aplikaci spustit

Aplikace nevyžaduje žádný backend ani složitou instalaci.

1. Stáhněte soubor `index.html`.
2. Otevřete jej v jakémkoliv moderním webovém prohlížeči (Chrome, Edge, Firefox, Safari).
3. Počkejte pár sekund na načtení neurální sítě (zobrazí se indikátor).
4. Začněte rozpoznávat!

## 💡 Jak to funguje?

Aplikace využívá model **MobileNet**, což je lehký model vytrénovaný na databázi **ImageNet**. V kódu je implementována funkce `translateTerm()`, která mapuje surové anglické názvy na jejich české ekvivalenty pomocí interní mapy v JavaScriptu.

---
**Poznámka:** Pro správnou funkci kamery je nutné aplikaci spouštět buď na `localhost` nebo přes zabezpečený protokol `https`.
