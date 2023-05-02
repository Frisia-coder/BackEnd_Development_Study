SuperPy Requirements
Well-structured and documented code:
 Clear and effective variable and function names
 Use of comments where the code does not speak for itself
 Clear and effective separation of code into separate functions and possibly files
Use of modules:
 csv
 argparse
 datetime
Additionally used modules:
 calendar (https://docs.python.org/3/library/calendar.html)
 os.path (https://docs.python.org/3/library/os.path.html)
 python-barcode (https://pypi.org/project/python-barcode/)
pip install python-barcode
pip install "python-barcode[images]"
 rich (https://rich.readthedocs.io/en/stable/introduction.html) [only for clean debug output]
pip install rich
 sys (https://docs.python.org/3/library/sys.html)
 tabulate (https://pypi.org/project/tabulate/)
pip install tabulate
 unittest (https://docs.python.org/3/library/unittest.html)
 xlsxwriter (https://xlsxwriter.readthedocs.io/)
pip install XlsxWriter
Requirements
 Use of external text files (CSV) to read and write data
 A well-structured and user friendly command-line interface
 Clear descriptions of each argument in the --help section
 A text file containing a usage guide aimed with peers as the target audience
 The usage guide should include plenty of examples
 A short, 300-word report that highlights three technically notable elements
The application must support:
 Setting and advancing the date that the application perceives as ‘today’
 Recording the buying and selling of products on certain dates
 Reporting revenue and profit over specified time periods
 Exporting selections of data to CSV files
 Two other additional non-trivial features of your choice
Additional non-trivial features
 1: Export report as a JSON or Excel file
 2: Generate a unique EAN-13 barcode for a new product and store products in a separate database
 3: Store new barcodes in a barcodes directory