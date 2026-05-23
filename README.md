# Mail Composer

Mail Composer is a modern, feature-rich web application that provides a seamless, professional email composition experience. Built entirely with Vanilla JavaScript, it offers robust contact management, persistent local storage, interactive rich text editing, and integrated productivity tools like a Dictionary and Global Translator.

## 🚀 Features

### 📧 Email Composition & Management
- **Smart Recipient Fields:** Interactive `To`, `Cc`, and `Bcc` areas that parse chips, automatically resolving custom group names into individual email addresses.
- **Auto-Complete Suggestions:** Quickly search and suggest contacts or groups by nickname, name, or email as you type.
- **Drag-and-Drop Interface:** Intuitively drag contacts from the right sidebar directly into the recipient fields.
- **System Mail Integration:** Click 'Send' to automatically compile your subject, rich text body, and parsed recipients, and seamlessly open your OS's native email client using robust `mailto:` link generation.

### 👥 Advanced Contact Management
- **Dynamic Groups:** Create custom groups, view group members, and dynamically remove specific individuals. Groups can be dropped directly into the 'To' line.
- **Custom Contact Nicknames:** Assign personalized badges/nicknames to easily distinguish between contacts.
- **CSV Import & Export:** Bulk import contacts via a structured CSV file, or selectively export only individual people (excluding groups) into a fresh CSV.

### 💾 Persistent Storage (IndexedDB)
- **Draft Auto-Saving:** The composer continuously saves your draft locally in the background. It won't forcefully overwrite your screen on page reload, keeping your canvas clean.
- **Template Engine:** Save frequently used emails as templates for quick reuse. A built-in modal lets you view, apply, or delete saved templates seamlessly across sessions.

### ✍️ Rich Text Editor
- **Formatting Tools:** Native support for bold, italics, underlining, alignments, bullet points, hyperlinks, and image insertion.
- **Interactive Image Resizer:** Custom-built JavaScript engine allows you to interactively click and drag the edges of inserted images to perfectly resize them while preserving aspect ratios.

### 🛠️ Productivity Tools Tab
- **Integrated Dictionary:** Look up the definition of any English word instantly using the free Dictionary API.
- **Global Translator:** Need to send an email internationally? Use the built-in translator powered by Google Translate, dynamically supporting over 100 ISO languages.

## 🛠️ Technology Stack

- **HTML5 & CSS3:** For a highly polished, responsive interface featuring vibrant color palettes (`#F98866`, `#FFF2D7`), smooth keyframe animations, and glassmorphism elements.
- **Vanilla JavaScript (ES6+):** Zero external dependencies. All logic, from Drag-and-Drop to IndexedDB interfacing, is completely native.
- **FontAwesome v6:** For sharp, scalable vector iconography.

## 📖 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sivasubramoniam-js/mail-composer.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd mail-composer
   ```
3. **Run the application:**
   Simply open `index.html` in your favorite modern web browser. No local server or build step is required!

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit a pull request.

## 📝 License

This project is open-source and available under the MIT License.