# RapidReply

# 🚀 Rapid Reply – A Tampermonkey Script for Instant Responses

**Rapid Reply** is a customizable Tampermonkey userscript that helps streamline repetitive communication — originally developed for internal use on Amazon's issue tracker (`issues.amazon.com`).  
Built from scratch by [@ossowsko](https://github.com/yourusername) (a.k.a. *your current name*), this tool empowers users to insert pre-defined reply templates, track clipboard activity, and manage text snippets — all from a sleek, floating UI.

---

## 🔧 Features

- ✍️ **Template Manager** – Create, edit, and delete reusable message templates
- 📋 **Copy History** – Automatically track recent copied texts (up to 25)
- 📎 **Clipboard Integration** – Instantly copies selected templates or text
- 🪟 **Floating UI** – Lightweight, draggable interface for quick access
- 🧠 **Local Persistence** – Stores data using Tampermonkey's internal storage (`GM_*` APIs)

---

## 📷 Demo

https://user-images.githubusercontent.com/yourusername/demo.gif  
*→ Replace this with your own screen recording or animated GIF*

---

## 🛠 Installation

1. Install [Tampermonkey](https://www.tampermonkey.net/) on your browser (Chrome, Firefox, Edge, etc.)
2. Open Tampermonkey → **Create a new script**
3. Paste the contents of [`rapid-reply.user.js`](./rapid-reply.user.js)
4. Save the script
5. Visit [https://issues.amazon.com](https://issues.amazon.com)  
6. Use the floating **RapidReply** button to start copying and managing replies!

---

## 🧩 Use Cases

- Customer service agents handling frequent canned replies
- Developers or operations engineers triaging large numbers of tickets
- Internal productivity tools in enterprise platforms

---

## 💡 Tips

- Double-click the RapidReply logo to show/hide the template list
- Right-click the logo to open the context menu (Edit Templates / Copy History / Exit)
- Use the "Edit Templates" panel to quickly modify or add new messages

---

## 👨‍💻 Author

**@arifipek94** (now using [@arifipek](https://github.com/arifipek94))  
Developed during my time working on internal Amazon tooling.  
Feel free to fork, improve, or integrate it into your own workflows.

---

## 📝 License

This project is released under the [GNU General Public License v3.0](LICENSE).

---

> ⚠️ This script is designed for internal tooling (like `issues.amazon.com`) — you may need to modify the `@match` pattern to use it on other platforms.
