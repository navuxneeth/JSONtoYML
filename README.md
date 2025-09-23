# JSONtoYML

A lightweight, client-side batch converter for JSON to YAML files. This tool is designed to be a simple and efficient way to handle multiple file conversions directly in the browser, providing a significant reduction in token count for applications that rely on YAML.

## Features
* **Batch Conversion:** Convert multiple JSON files to YAML at once.
* **Drag and Drop:** Easily upload files by dragging and dropping them onto the interface.
* **Individual & Batch Downloads:** Download converted files individually or as a single ZIP archive.
* **Client-Side Operation:** All conversions happen in your browser without sending data to a server, ensuring privacy and speed.
* **Live Status Updates:** Get real-time feedback on the conversion status for each file.
* **Theme Switcher:** Toggle between light and dark themes for a customized experience.

## Project Tree
````
.
├── .gitattributes
├── ASCII-Version.html
├── LICENSE
├── README.md
└── index.html
````
## How to Use
1.  **Upload Files:** Click on the upload area or drag and drop your JSON files.
2.  **Convert:** The conversion process begins automatically. The application checks for valid JSON files and converts them to YAML.
3.  **Download:** Once converted, you can download each `.yaml` file individually or click "Download All as ZIP" to get a compressed archive of all successful conversions.

## Technologies Used
* **Frontend:** HTML, CSS
* **Styling:**
    * `index.html`: Tailwind CSS
    * `ASCII-Version.html`: Tailwind CSS with a custom, retro-inspired theme.
* **Core Libraries:**
    * [js-yaml](https://github.com/nodeca/js-yaml): For converting JSON objects to YAML format.
    * [JSZip](https://github.com/Stuk/jszip): For creating the downloadable ZIP archive of all converted files.

## Credits
* **Author:** [Navaneeth Sankar K P](https://github.com/navuxneeth)
* **LinkedIn:** [Navaneeth Sankar K P](https://www.linkedin.com/in/navaneeth-sankar-k-p)

This project was developed by Navaneeth Sankar K P, who is a current User Acquisition team member at Perplexity and has a background as a Design Contractor, UX Researcher, and B2B UX Designer. He is also a student at MIT Institute of Design and the Indian Institute of Technology, Madras, where he is studying User Experience Design and Data Science and Machine Learning.

## License
This project is licensed under the MIT License.
