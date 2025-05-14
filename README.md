This Python application provides a simple graphical user interface (GUI) for merging multiple PDF files into one. Users can select any number of PDFs from their computer and save the combined file under a new name. The program simplifies PDF merging for users with no coding experience.

Libraries Used:
- tkinter (for GUI interface and file dialogs)
- tkinter.messagebox (for alerts and success messages)
- PyPDF2 (specifically PdfMerger for merging PDF files)

Features:
- GUI-based file selection for choosing multiple PDF files
- "Save As" dialog to specify the name and location of the merged file
- Error handling with user-friendly alerts for missing files or unexpected issues

Note:
- Merged PDF is saved to the location and name specified by the user.
- No third-party PDF viewer is required; the resulting file can be opened with any PDF reader.
