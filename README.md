
# 🖼️ Base Frame Tester

A minimal **Farcaster Frame** scaffold to experiment with metadata, buttons, and interaction flow before integrating into a full Base app.

---

## 📘 What is this?

This repo allows testing of:
- Open Graph + `fc:frame` metadata  
- Button interactions (`fc:frame:button`)  
- JSON-based frame descriptors (`frame.json`)

---

## 🚀 How to use

1. Host `frames/frame.html` on any static service (e.g., Vercel / Cloudflare Pages).  
2. Replace `fc:frame:post_url` with your own endpoint.  
3. Share that URL in a Farcaster cast — Warpcast will render it as an interactive frame.  
4. Adjust buttons and metadata in `frame.json`.

Example:
```html
<meta property="fc:frame:button:1" content="Ping" />
<meta property="fc:frame:button:2" content="Visit Repo" />
```

---

## 📂 Folder Structure

```
base-frame-tester/
├── frames/
│   ├── example.html
│   ├── button.html
│   └── frame.html
├── public/assets/
│   └── placeholder.txt
├── frame.json
├── LICENSE
├── README.md
└── TODO.md
```

---

## 🔗 Related Repositories
- [Talent Protocol Roadmap](https://github.com/Igorehadem/talent-protocol-roadmap)
- [Farcaster Bot Starter](https://github.com/Igorehadem/farcaster-bot-starter)

---

## 🧭 Roadmap
- [ ] Add BaseToken frame example  
- [ ] Simulate cast trigger  
- [ ] Integrate with Farcaster bot autopost
