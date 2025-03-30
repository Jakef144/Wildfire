# Wildfire Analysis (2008-2024)
# This project analyzes wildfire costs from 2008 to 2024 using data collected from NICF's open resources. The data was extracted from PDF documentation via tools like PyMuPDF and PyPlumber to pull and jsonify tables. Once converted into CSV format, the data underwent further processing.

# An XGBoost regression model was applied to predict missing cost values based on factors such as acre size, previous costs, and cause of the wildfire. Although the model has imputed missing values, further analysis and findings are still pending.

# This checkpoint saves the progress made so far.
