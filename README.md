# Google Drive ID Extractor

This Python package provides a simple utility to extract Google Drive file IDs from different types of Google Drive URLs.

## Usage

```python
from google_drive_id_extractor import extract_google_drive_id

drive_link = "https://drive.google.com/file/d/12345abcde/view?usp=sharing"
file_id = extract_google_drive_id(drive_link)
print(file_id)  # Output: 12345abcde
```
