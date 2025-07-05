
# 🎇 particles.js – Dynamic Particle Effects Made Easy

`particles.js` is a lightweight, customizable JavaScript library for crafting visually rich, interactive particle systems with ease. Whether you're adding subtle ambient motion or bold effects, this tool helps bring your UI to life.

---

## 🚀 Quick Start

### 1. Add the HTML Container
```html
<div id="particles-js"></div>
```

### 2. Load the Library
```html
<script src="particles.js"></script>
```

### 3. Initialize with Your Configuration
```javascript
particlesJS.load('particles-js', 'assets/particles.json', function () {
  console.log('callback - particles.js config loaded');
});
```

### 4. Example `particles.json`
```json
{
  "particles": {
    "number": {
      "value": 80,
      "density": {
        "enable": true,
        "value_area": 800
      }
    },
    "color": { "value": "#ffffff" },
    "shape": {
      "type": "circle",
      "stroke": { "width": 0, "color": "#000000" },
      "polygon": { "nb_sides": 5 },
      "image": {
        "src": "img/github.svg",
        "width": 100,
        "height": 100
      }
    },
    "opacity": {
      "value": 0.5,
      "random": false
    },
    "size": {
      "value": 10,
      "random": true
    },
    "line_linked": {
      "enable": true,
      "distance": 300,
      "color": "#ffffff",
      "opacity": 0.4,
      "width": 2
    },
    "move": {
      "enable": true,
      "speed": 12,
      "direction": "none",
      "out_mode": "out"
    }
  },
  "interactivity": {
    "detect_on": "canvas",
    "events": {
      "onclick": {
        "enable": true,
        "mode": "push"
      },
      "resize": true
    },
    "modes": {
      "push": {
        "particles_nb": 4
      }
    }
  },
  "retina_detect": true
}
```

---

## ⚙️ Configuration Options

You can control every aspect of the particle behavior. Below are just a few of the available options:

| Key                             | Type / Notes                            | Example        |
|----------------------------------|------------------------------------------|----------------|
| `particles.number.value`        | Number of particles                      | `80`           |
| `particles.color.value`         | HEX, RGB, HSL, Array, or `"random"`      | `"#ffffff"`    |
| `particles.shape.type`          | `"circle"`, `"edge"`, `"image"`, etc.    | `"circle"`     |
| `particles.move.speed`          | Movement speed                           | `6`            |
| `interactivity.events.onclick.mode` | Interaction mode(s)                   | `"push"`       |

👉 Full list of options is available below in this README under the Options section.

---

## 📦 Installation Methods

Choose the method that suits your environment:

### 🔹 NPM
```bash
npm install particles.js
```
[View on NPM](https://www.npmjs.com/package/particles.js)

### 🔹 Bower
```bash
bower install particles.js --save
```

### 🔹 Rails Assets
```ruby
gem 'rails-assets-particles.js'
```

### 🔹 Meteor
```bash
meteor add newswim:particles
```
[View on Atmosphere](https://atmospherejs.com/newswim/particles)

---

## 🌐 CDN Hosting

Load directly from JSDelivr:

```html
https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js
```

Or visit: [JSDelivr CDN](https://www.jsdelivr.com/package/npm/particles.js)

---

## 📘 Full Configuration Options

(Click to expand full option table if rendering markdown)

All available configuration keys and their accepted values are detailed in the original version of this README.

---

## 🤝 Contribution

This project includes contributions from developers and creative minds who help keep the library accessible and powerful.

### 👤 Special Thanks:
**Vlad C. Gherga** 

---

## 🌟 License

MIT – Free to use, modify, and distribute.
