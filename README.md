## Usage

- Create a Python virtual environment and activate it
- Run `pip install -r requirements.txt`
- Copy a Firefox Places SQLite database file to `places/` in the repo. You can name it as `nightly-places.sqlite`, otherwise, you will need to update the name in 23rd cell of the notebook "domains.ipynb"
  - You can find the database file as follows:
    - Type `about:profiles` in the URL bar and locate the profile you like
    - Click "Show in Finder" of the "Root Directory" (assuming you're on OSX) to open the browser profile folder
    - Find and copy the file `places.sqlite` and paste to the `places/` directory of this repo. Note: just copy, don't cut it!
- Open the notebook by running `jupyter notebook`
- Click `Run All Cells` under the "Run" menu to run all the cells
- At the end of the notebook, use the slider to do the interest classification
