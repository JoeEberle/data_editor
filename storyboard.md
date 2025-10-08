

# 🧠 Data Editor  

## Loads Data  - Import formats  

1. CSV / TXT
2. Excel (XLS, XLSX)
3. Parquet (PARQUET, PQ)
4. JSON
5. Pickle (pickle,pkl)
5. Feather (feather) 

## 🔎 Filters and selects files

1. Provides filename search/filtering
2. Lets the user choose a file to edit

## 📊 Loads the selected file into a pandas DataFrame for display

1. ✏️ Interactive editing
2. Uses Streamlit’s st.data_editor to let the user view and modify the DataFrame directly in the browser

## 💾 Saving options

1. Overwrite the original file in its same format (if supported)
2. Save As: choose any destination folder, filename, and format

## 📑 Supported export formats

1. CSV
2. Excel (.xlsx)
3. Parquet
4. JSON
5. SQLite (table name user-specified)

##  ✅ Flexible workflow

1. Can rename files and convert between formats
2. Option to overwrite or create new files
