# 📚 Reglas y Conceptos de Fuentes en CSS 🎨

> _Como si fuésemos hechiceros del código, dibujamos con letras lo que antes era solo un lienzo en blanco..._ ✨

---

## 📥 Importación de fuentes externas

```css
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
```

💡 *Traemos desde las tierras de Google Fonts a nuestra fiel compañera: Roboto.*

```css
.roboto-font {
  font-family: "Roboto", sans-serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
  font-variation-settings:
    "wdth" 100;
}
```

---

## 🎀 Fuentes personalizadas (como invocar magia única)

```css
@font-face {
  font-family: 'BarbieFont1';
  src: url('../fonts/Retro_Dolly.otf');
}
```

```css
.barbie-font {
  font-family: 'BarbieFont1', sans-serif;
  font-weight: normal;
  font-style: normal;
  font-size: 46px;
  color: #ff69b4;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}
```

```css
@font-face {
  font-family: 'HarryFont';
  src: url('../fonts/HARRYP__.TTF');
}

.harry-font {
  font-family: 'HarryFont', sans-serif;
  font-weight: normal;
  font-style: normal;
  font-size: 46px;
  color: #ffcc00;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}
```

---

## 🌈 Variables en `:root`

```css
:root {
  --color-fondo: #f0f0f0;
  --color-texto: #333;
  --color-parrafos: #666;
  --color-enlace: #0066cc;
  --color-enlace-hover: #00509e;
  --color-sombra: rgba(0, 0, 0, 0.5);
  --font-primary: 'Arial', sans-serif;
  --font-secondary: 'Georgia', serif;
  --font-code: 'Courier New', monospace;
}
```

💬 *Es como tener un grimorio central donde definimos nuestros hechizos de estilo.*

---

## 🔠 Fuentes en el `body`

```css
body {
  font-family: "Times New Roman", Times, serif;
  font-weight: 100;
  font-size: 16px;
}
```

---

## 🧱 Encabezados

```css
h1,h2,h3,h4,h5,h6 {
  font-family: var(--font-primary);
  font-weight: bold;
  color: var(--color-texto);
}
```

---

## 📝 Párrafos

```css
p {
  font-family: var(--font-secondary);
  font-size: 1em;
  color: var(--color-parrafos);
}
```

---

## 💫 Estilos decorativos

```css
.sombreado {
  text-shadow: 3px 3px 5px #00f;
}

.espaciado-letras {
  letter-spacing: 10px;
}

.espaciado-palabras {
  word-spacing: 20px;
}
```

---

## 📐 Alineación de texto

```css
.alineacion-derecha { text-align: right; }
.alineacion-centro { text-align: center; }
.alineacion-izquierda { text-align: left; }
.alineacion-justificada { text-align: justify; }
```

---

## ✏️ Decoración del texto

```css
.subrayado { text-decoration: underline; }
.subrayado-encima { text-decoration: overline; }
.tachado { text-decoration: line-through; }
.parpadeante { text-decoration: blink; }
```

---

## 🧙‍♂️ Transformaciones de texto

```css
.mayusculas { text-transform: uppercase; }
.minúsculas { text-transform: lowercase; }
.oracion { text-transform: capitalize; }
```

---

## 🧾 Sangría y orientación

```css
.sangria { text-indent: 20px; }

.orientacion-horizontal {
  writing-mode: horizontal-tb;
}

.orientacion-vertical {
  writing-mode: vertical-rl;
}
```

---

> _El código es poesía visual, donde cada fuente es una voz distinta narrando la historia del diseño._ 🎤✨
