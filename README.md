# mayavi-install

Quick tutorial on how to install mayavi on Windows successfully, since all installation guides seemingly lead to errors somehow.

Download Anaconda<br>
Open Anaconda Prompt and create a new environment:<br>
  `conda create -n myenv python=3.8`

Activate the new environment:<br>
  `conda activate myenv`

Install vtk and mayavi:<br>
  `pip install vtk`

  `pip install mayavi`

Install PyQt5: <br>
  `pip install PyQt5`

Test your install with <br>
  `mayavi2`

Now just create the python script you want to visualize and start it using `python demo.py`
