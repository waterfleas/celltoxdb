# celltoxdb
Cell line toxicity database

This is a Flask based app to store and retrieve Cell line toxicity data. Built for the Schirmer Lab at EAWAG.


Files and functions
.
- Procfile
-   R
    - [chemical_info.R](#-chemical_info.R)
    - [fitdr.R](#fitdr.R)
    - [xls_properties.R](#-xls_properties.R)
- README.md
-   app
    - assets
        - [dash_v01.css](#-assets/dash_v01.css)
    - models.py
    - plotlydash
        - assets
            - dash_v1.css
        - dashboard.py
        - layout.py
    - static
        - css
            - dropdown.css
            - forms.css
            - main_1.css
        - js
            - dropdown.js
            - trie.js
    - templates
        - 404.html
        - _formatnumbers.html
        - _formhelpers.html
        - _tablehelpers.html
        - browse.html
        - impressum.html
        - main.html
        - plot.html
        - search.html
        - search_results.html
        - show.html
        - upload.html
        - uploaded.html
        - widgets
            - list_download.html
    - translations
        - pt
            - LC_MESSAGES
                - messages.mo
                - messages.po
    - views.py
-   babel
        - babel.cfg
        - messages.pot
- config.py
- custom_validators.py
- fileIO.py
- filter_widgets.py
- forms.py
- init_db.py
- insert_db.py
- populate_db.py
- query_lib.py
- requirements.txt
- search.py
- test.py
- update_db.py
- upload.py
- utils.py


## R
### chemical_info.R
reads data from an Excel file, performs data manipulation and transformation operations on the selected columns, modifies column names, and writes the resulting data frame to a JSON file.

### fitdr.R
processes dose-response data, fits dose-response models, generates plots, calculates estimated values, and saves the results

### xls_properties.R
reads an Excel file, extracts the year from the "Date" column, selects specific columns of interest, reshapes the data, performs some string manipulation, and saves the processed data as a CSV file

### assets/dash_v01.css
css styling for the plotly dashboard



