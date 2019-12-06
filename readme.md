*****
Notes
*****

Code is divided into two directories:

1. 'jupyter'

Jupyter Notebook IDE users (.ipynb):

* All code tested (December 6, 2019) using Jupyter Notebook Python IDE

With notebook files that contain matplotlib images, you may have to run the code twice in Jupyter Notebook to see the image displayed.

2. 'python'

Python IDE users (.py extension):

* All code tested (December 6, 2019) using Python IDE


General issues:

We noticed that when loading (numpy.load) banking data, need to include parameter 'allow_pickle=True' when using numpy.load to load target variable 'y' data. Also, need to include the same parameter when loading variable 'bp' (best parameters from tuning). The code you download from the book website should work without any modifications.

If you have any difficulties with numpy.load, you can experiment with the 'allow_pickle' parameter. With all of our testing, we have only had to add 'allow_pickle=True' to the numpy.load() function. We believe that earlier versions of Python were less strict because the code was tested by several people a few months ago with no problems.

