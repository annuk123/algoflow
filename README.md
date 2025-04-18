# 🔍 AlgoFlow

**AlgoFlow** is a modern, interactive platform built to **visualize Data Structures and Algorithms (DSA) step by step**, making learning and solving DSA problems easier, clearer, and more intuitive. The core idea behind AlgoFlow is to bridge the gap between writing code and actually understanding how it works under the hood — especially for beginners and intermediate learners preparing for coding interviews.

It features a clean, responsive UI with real-time search, tag-based filtering, and dynamic problem routing, all built using modern technologies like Next.js 14, TypeScript, Tailwind CSS, Framer Motion, and shadcn/ui. Users can explore curated problems by category (e.g., Arrays, Graphs, DP), search problems by keywords, and open detailed pages for each problem.

AlgoFlow is designed not just as a problem list, but as a DSA learning companion — where the focus is on clarity, visual learning, and clean UX, making the complex process of solving algorithms more approachable and even enjoyable.


Crafted with the latest frontend technologies like **Next.js**, **TypeScript**, **Tailwind CSS**, and **Framer Motion**, AlgoFlow delivers a clean, responsive UI with real-time filtering, search, and beautiful animations.

![AlgoFlow Screenshot](/public/image.png)

---

## ✨ Key Features

- 🧠 **Step-by-Step Code Visualization**  
  Understand how DSA problems are solved with animated, interactive walkthroughs.

- 🔎 **Real-time Search & Tag Filtering**  
  Quickly find problems based on keywords and topic categories like `Array`, `Graph`, `DP`, etc.

- 🎨 **Modern UI + Dark Mode Support**  
  Elegant design with dark/light toggle powered by `next-themes`.

- 📱 **Mobile Responsive**  
  Works beautifully on all screen sizes.

- ⚡ **Smooth Animations**  
  Built with Framer Motion for seamless UI transitions and effects.

- 🧩 **Dynamic Routing**  
  Every problem has its own dedicated page for focused learning.

---

## 🛠 Tech Stack

| Technology     | Purpose                          |
|----------------|----------------------------------|
| **Next.js 14** | App routing, server/client logic |
| **TypeScript** | Strong typing, cleaner code      |
| **Tailwind CSS** | Utility-first styling framework |
| **shadcn/ui**  | Polished, accessible UI components |
| **Framer Motion** | Rich animations                |
| **Lucide Icons** | Minimal, scalable icons        |

---

## 📁 Folder Structure

```
.
├── app/
│   ├── page.tsx             # Home: Filter + Problem List
│   ├── problems/[slug]/     # Dynamic problem detail pages
│   └── components/
│       └── navbar/          # Navbar with search + filter
├── data/
│   └── problems.ts          # All problem metadata
├── public/
│   └── preview.png          # Optional UI screenshot
└── README.md
```

---

## 📈 What's Coming Next?

- 🟡 Interactive code visualizations with animations and step transitions
- 🟢 Code editor with explanation tabs
- 🟢 Problem difficulty filters
- 🟢 "Mark as Solved" or "Save for Later"
- 🟢 Backend integration via **Convex** or **Firebase**
- 🟢 User profiles and dashboard

---

## 🚀 Getting Started

### Clone the Repository
```bash
git clone https://github.com/your-username/algoflow.git
cd algoflow
```

### Install Dependencies
```bash
npm install
# or
yarn install
```

### Run the Development Server
```bash
npm run dev
# or
yarn dev
```

Then open [http://localhost:3000](http://localhost:3000) to see AlgoFlow in action.

---

## 🧠 Why AlgoFlow?

There are many DSA resources, but few that **visually explain** the code. AlgoFlow focuses on **bridging that gap** — giving users both problem statements and **interactive visual code flow** so that they not only solve problems but deeply understand *how* they’re solved.

---

## 🤝 Contributing

We welcome all ideas, issues, and pull requests!  
Want to add a new feature, fix a bug, or improve the UI? Fork the repo and get started!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

Built with 💻 & 💙 by **Annu Kumari**  
🔗 [Portfolio](https://bio.link/annukumalu) • 🐦 [Twitter](https://x.com/Annu66126617) • 🐙 [GitHub](https://github.com/annuk123)

---

> Empowering developers to learn DSA with clarity, simplicity, and style.

> **AlgoFlow** — Learn DSA like never before with clear, visual, and interactive problem solving.
