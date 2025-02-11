# auswalld_browser
auswalld_browser is a simple web browser built using Python and PyQt5. It provides basic functionality such as navigating back and forward, reloading pages, going to a home page, and entering custom URLs.

## Features
- Back Button: Navigate to the previous page.
- Forward Button: Navigate to the next page.
- Reload Button: Refresh the current page.
- Home Button: Quickly return to the predefined home page.
- URL Bar: Enter URLs directly to visit any website.
- Dynamic URL Updates: The URL bar updates automatically when the browser navigates to a new page.

## Getting Started 
### Prerequisites
Before running the application, ensure that the following are installed on your system:
- Python 3.7+
- PyQt5 library
- PyQtWebEngine module

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Snack73/auswalld_browser.git
    cd auswalld_browser
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use venv\Scripts\activate
    ```

3. Install dependencies:
    ```bash
    pip install PyQt5 PyQtWebEngine
    ```

### Usage 
Run the application using the following command:
```bash
python main.py
```

### Home Page
The default home page is set to Programming Hero. You can change the home page by editing the navigate_home method in main.py.

```python
def navigate_home(self):
    self.browser.setUrl(QUrl('http://programming-hero.com'))
```

## Screenshots
![Screenshot (577)](https://github.com/user-attachments/assets/dad3bc95-5aaf-4ddd-9c17-97a319cb100c)
![Screenshot (576)](https://github.com/user-attachments/assets/2458a9ed-d67c-4196-b393-eead3aac589c)


## Future Enhancements 
- Multi-tab support
- Custom themes
- Bookmark functionality
- Download manager

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
Built with PyQt5.
Inspired by tutorials and community resources on building simple browsers with Python.
