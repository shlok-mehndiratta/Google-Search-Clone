# Google Search Clone (Frontend Project)

This is a **frontend-only clone** of Google's core search interfaces. It replicates the look and basic behavior of:
- **Google Search**
- **Google Image Search**
- **Google Advanced Search**

Built using **HTML and CSS only**, with no JavaScript or backend code.

---

## 📁 Project Structure

.
├── index.html # Main Google Search page
├── images.html # Google Image Search clone
├── advanced.html # Google Advanced Search clone
├── style.css # Styles for index and images pages
├── adv_style.css # Styles for advanced search page
├── static/
│ └── google_logo_image.png # Google logo used in all pages

yaml
Copy
Edit

---

## 🔍 Features

### ✅ Google Search (`index.html`)
- Centered search input styled like the Google homepage
- "Google Search" and "I'm Feeling Lucky" buttons
- Font Awesome icon inside the search bar

### ✅ Google Image Search (`images.html`)
- Search input specifically styled for image queries
- Includes `tbm=isch` to redirect to Google Images

### ✅ Google Advanced Search (`advanced.html`)
- Input fields for:
  - All these words → `as_q`
  - Exact phrase → `as_epq`
  - Any of these words → `as_oq`
  - None of these words → `as_eq`
- Aligned inputs for consistent UX
- Helpful hints beside each field

---

## 🚀 How to Run

1. **Clone the repository**

```bash
git clone https://github.com/your-username/google-search-clone.git
cd google-search-clone
```

2. **Open any HTML file in your browser**

- `index.html` – Standard Google Search
- `images.html` – Google Image Search
- `advanced.html` – Google Advanced Search

You can open them by double-clicking the file or dragging it into your browser.

3. **Use the search fields**

- Type your query and hit Enter or click the buttons.
- The form will redirect you to the actual Google search results for demonstration.

🧠 Concepts Practiced
HTML semantics and form behavior

CSS Flexbox layout for alignment

Input and label styling consistency

Responsive design for smaller screens

Accessibility using <label> and for

📜 License
This project is intended for educational purposes only.
This is not affiliated with Google in any way.

🙌 Contributing
Want to improve the design or add more features?
Fork the repo and submit a pull request!