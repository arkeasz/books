# Contribution Guide

Thank you for your interest in contributing to this project! This is an **mdBook** that organizes and presents a collection of PDF files for easy access. Follow these guidelines to contribute effectively.

## 🛠️ Prerequisites

Before you start, make sure you have the following:

1. **mdBook** installed:
   ```bash
   cargo install mdbook
   ```
2. Basic familiarity with Markdown and the project structure.

3. Set up a local commit message template:  
   ```bash
   git config commit.template .gitmessage
   ```
---

## 📂 Project Structure

The book is organized as follows:

- **`src/`**: Contains the book's chapters in Markdown format (`.md`).
- **`src/pdfs/`**: Stores the PDF files used in the book.
- **`book.toml`**: The main configuration file for the mdBook.

---

## 🔄 How to Contribute

### 1. Propose Changes or Improvements

1. Check the [open issues](https://github.com/arkeasz/books/issues) to avoid duplications.
2. If no related issue exists, open a **new issue** and describe:
   - The problem or improvement you're addressing.
   - Your proposed solution.

### 2. Add or Update Chapters

1. To add a new chapter:
   - Create a `.md` file in the `src/` folder.
   - Update the `SUMMARY.md` file to include the new chapter in the book navigation.
2. To update an existing chapter:
   - Edit the corresponding `.md` file in the `src/` folder.


### 3. Add New PDFs

1. Upload the PDF files to the `src/pdfs/` folder.
2. Ensure that the chapter links to the PDF correctly:
   ```markdown
   [PDF Name](./pdfs/<area>/file.pdf)
   ```

---

## 🧪 Test Locally

Before submitting your changes, build and test the book locally:

1. Build the book:
   ```bash
   mdbook build
   ```
2. Serve the book locally to preview it:
   ```bash
   mdbook serve
   ```

This will launch the book at `http://localhost:3000`.

---

## 🔄 Submitting a Pull Request

Follow these steps to submit your contributions:

1. **Fork** the repository.
2. Create a new branch for your changes:
   ```bash
   git checkout -b feature/new-feature
   ```
3. Make your changes and commit with a clear message:
   ```bash
   git commit -m "feat: added new chapter on X"
   ```
4. Push your changes to your fork:
   ```bash
   git push origin feature/new-feature
   ```
5. Open a **Pull Request** to the main branch.

---

## 🌟 Best Practices

- Use clear and descriptive file names in lowercase.
- Use relative links for PDFs within the book.
- Check your spelling and formatting before submitting changes.

---

## 💬 Communication

If you have any questions, feel free to open an issue or contact the project maintainers. We're here to help.

---

Thank you for contributing! This project gets better with contributions from people like you.
