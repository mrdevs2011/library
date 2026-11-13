# MR Developer Utility Library

A lightweight, zero-dependency, high-performance developer toolkit and client utilities created by [@mrdevs2011](https://github.com/mrdevs2011).

---

## ⚡ Modules

### 1. `MRRealtime` (`js/realtime.js`)
Zero-dependency, seamless DOM poller designed for chats, notifications, feeds, and live dashboards without page flicker or losing user input focus.

#### Usage via CDN (Fastest):
```html
<script src="https://cdn.jsdelivr.net/gh/mrdevs2011/library@main/js/realtime.js"></script>
```

#### Method A: Pure HTML (Zero Script Required!)
Just add `data-mr-realtime="1500"` to your container:
```html
<div class="messages-container" data-mr-realtime="1500">
    <!-- Django / Backend messages loop -->
</div>
```

#### Method B: JavaScript API
```javascript
MRRealtime.start('.messages-container', 1500);
```

---

## 📦 License
MIT License © 2026 mrdevs2011 (Muhammadrasul)
