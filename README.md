## Free Online Text File Splitter

A web-based application that allows users to split text files (e.g., .txt, .csv, .log) into a specified number of smaller files. The application operates entirely client-side, ensuring privacy and security.

**Features:**

* **Client-side processing:** All operations occur within the user's browser, safeguarding data privacy.
* **HTML5-based:** Leverages modern web technologies for a robust and efficient experience.
* **Intuitive interface:** Easy-to-use design for seamless file splitting.
* **Multiple file formats:** Supports .txt, .csv, and .log files.
* **Customizable splitting:** Choose to split by lines or characters.

**How it works:**

1. **Upload file:** Select a text file to split.
2. **Specify splits:** Determine the desired number of smaller files.
3. **Choose splitting method:** Select whether to split by lines or characters.
4. **Download:** Download the split files as a ZIP archive.

**Technical details:**

* **HTML structure:** Provides the basic layout and form elements.
* **CSS styles:** Creates an attractive and responsive design.
* **JavaScript functionality:**
  * Reads files using the FileReader API.
  * Splits content based on user preferences.
  * Downloads files using Blob and URL.createObjectURL.
  * Provides progress indication for large files.
* **JSZip library:** Used to create a ZIP file containing the split files.

**Note:**

While this application is designed to be functional, additional testing and optimization may be necessary for production-level use.

**Installation:**

1. Clone this repository.
2. Open the `index.html` file in a web browser.

**Contributions:**

Contributions are welcome! Please feel free to fork the repository and submit pull requests.
