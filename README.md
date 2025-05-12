Open your browser’s Extensions page:

Chrome: chrome://extensions/

Edge: edge://extensions/

Enable Developer mode (toggle in the top right).

Click Load unpacked and select the ModBatchr/ folder.

ModBatchr should now appear in your toolbar!

⚙️ Quick Start
Visit a LoversLab mod page, for example:

Copy
Edit
https://www.loverslab.com/files/file/12345-example-mod/
ModBatchr will auto-refresh to:

Copy
Edit
…/file/12345-example-mod/?do=download

3. Click the **ModBatchr** icon in your toolbar.

4. In the popup, you’ll see a list of all downloadable files:
- Use **Select All**, **Unselect All**, or pick files individually.
- Click **Download Selected** or **Download All**.

5. Files are fetched, zipped, and saved to your chosen folder.

---

## 🔧 Features

- ✅ **Manual file selection**
- 🚀 **ZIP bundling** for multi-file downloads
- 💾 **Custom subfolder paths** (e.g., `MyMods/Bundle1`)
- 🔄 **Auto-refresh** mod pages to access download mode directly
- 🧠 **Persistent preferences** (remembers selections and settings)

---

## ⚙️ Configuration

Inside the popup:

- **Download Folder** – Choose where zipped files are stored.
- **Save Folder** – Saves your custom folder preference.
- **Auto-refresh** – Automatically appends `?do=download` to mod pages.

---

## 📂 How It Works

1. When visiting a mod page, ModBatchr auto-redirects to the download view.
2. It extracts file names and links using DOM scraping.
3. Selected files are fetched in parallel (with fail handling).
4. Files are zipped in-browser using `JSZip`.
5. The ZIP is saved using the browser's native download API.

---

## ❗ Legal Disclaimer

ModBatchr does not host or distribute any third-party files.  
It simply automates manual downloads already accessible via LoversLab.

- Please respect the LoversLab **Privacy Policy** and **Terms of Service**.
- Do not redistribute or commercialize downloaded content.
- This tool is intended for **personal use only**.
- If any file requires registration, verification, or explicit user interaction, you must comply with LoversLab's rules.

---

## 🤝 Contributing

1. Fork this repo.
2. Create a feature branch:
```bash
git checkout -b feature/my-feature
```
3. Make changes and commit them.
4. Push to your fork and open a Pull Request.

---

## 📈 Coming Soon

- 🧾 downloaded files
- 🌐 Firefox support
- 🔔 Notifications when downloads complete (configurable)

---

## 📝 License

This project is open source under the MIT License.
