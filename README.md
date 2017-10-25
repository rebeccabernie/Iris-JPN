# Problem Sheet 3 - Jupyter, Numpy, Pyplot

> Module: Emerging Technologies / 4th Year  
> Lecturer: Dr Ian McLoughlin  
> [Original Problem Sheet](https://github.com/emerging-technologies/emerging-technologies.github.io/blob/master/problems/jupyter.md)  
  
These problems relate to [Jupyter](http://jupyter.org/), [Numpy](http://www.numpy.org/) and [Pyplot](https://matplotlib.org/api/pyplot_api.html), and use the [Iris data set](https://archive.ics.uci.edu/ml/datasets/iris).  

### Using Jupyter
The [IrisData.ipynb](https://github.com/rebeccabernie/Iris-Jupyter/blob/master/IrisData.ipynb) file is a Jupyter notebook containing all the problems and solutions for this problem sheet. To run the notebook, you must first install Jupyter - if you have [Anaconda](https://www.anaconda.com/download/) and a modern browser like [Firefox](https://www.mozilla.org/en-US/firefox/new/) or [Chrome](https://www.google.com/chrome/browser/desktop/index.html) already installed on your machine, you won't need to do any setup. If not, follow the instruction guide [here](https://jupyter.readthedocs.io/en/latest/install.html#id4).  

While the notebook *displays* properly on GitHub, it's not interactive. To run the notebook properly, you'll need to:
1. Open a text editor like Notepad or Notepad++.  
2. Copy and paste the [raw data](https://raw.githubusercontent.com/rebeccabernie/Iris-Jupyter/master/IrisData.ipynb) into the text editor.  
3. Save the file with `.ipynb` extension - for example, `IrisData.ipynb`. The extension is important, as the notebook won't run without it.  
4. Open a command line in the same location you've saved this file and type `jupyter notebook`.  
5. A browser window containing the notebook home will open. Clicking on the `.ipynb` file you created will open the notebook in another tab.  
6. In this new tab, click on `Kernel` and select `Restart & Run All`, which will restart the kernel and run all cells in the notebook. You can now edit the notebook as you need.