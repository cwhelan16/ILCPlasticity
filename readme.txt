This drive contains a pdf of the master's thesis as well as two Jupyter notebooks, pertaining to Sections 3 and 4 of the master's thesis.
If run in order (i.e. Section 3 then Section 4), the existing .csv files should be replaced by the ones created by the code in Section 3. (This can be confirmed by checking the timestamp after running Section 3.)
The files are there as a result of running the code on each USB drive once, and as a fail-safe in case unforeseen directory issues cause problems with reading/writng the data.
Each notebook can be run by either copying the .ipynb files to one's C-drive and opening Jupyter notebooks with Python 3 (for example installed with the Anaconda package),
or run directly from the USB drive by opening Anaconda prompt and typing: jupyter notebook "--notebook-dir=[drive location]". For me, the code with drive location included is: "jupyter notebook --notebook-dir=D:/"

