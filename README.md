# ISOMIP+ Collaborative Analysis and Writing Project

Ten different modelling groups submitted results to the ISOMIP+ model intercomparison project, using the [Asay-Davis et al. (2016) protocol](https://gmd.copernicus.org/articles/9/2471/2016/). This is a central repository where we can create and upload figures and the code used to generate them whilst analysing and describing the differences between ice-shelf ocean models. Discussions, figures and scripts are very welcome.

### How it works:
- **[To-do_list.md](https://github.com/misomip/isomip-plus/blob/main/To-do_list.md) has a list of things to work on in the hackathon**
- Suggested figures for analysis are in the [Issues](https://github.com/misomip/isomip-plus/issues) section. Feel free to assign yourself a figure, suggest ideas for new ones by creating a new issue, upload figures into the text box, and make comments and suggestions.
- [Figure_outline.md](https://github.com/misomip/isomip-plus/blob/main/Figure_outline.md) contains a summary list of figures; this will be modified as we make progress.
- To contribute code, first fork this repository, then make your changes (e.g. create new folder, edit or upload a jupyter notebook) and finally create a pull request back to the main repository to merge and share your work.

### Virtual Hackathon Schedule:
- US/Europe friendly time zone: Thursday 25 April  (7am-10am US MT/9am-12pm US ET/2pm-5pm UK/3pm-6pm Western Europe)
- Asia/Australia friendly time zone: Wednesday 1 May (9am-12pm Japan/10am-1pm Eastern Australia)/ Tuesday 30 Apr (6pm-9pm US MT/8pm-11pm US ET)

Note: Hackathon zoom link, Overleaf and Model Data distributed privately.

### Getting started:
- download and unzip the model data
- fork this repository 
- clone your fork on your machine
You don't need to start from scratch: Xylar's plotting scripts have been (somewhat) converted to Jupyter Notebook form in [this folder](https://github.com/misomip/isomip-plus/blob/main/notebooks/general-plotting); alternatively there is a different method using xarray in [overturning-streamfunction](https://github.com/misomip/isomip-plus/blob/main/notebooks/overturning-streamfunction/OverturningStreamfunction.ipynb)

In both of these notebooks you can modify the `baserepo` (where this repository is located on your machine) and `basedrive` (where the data is stored on your machine). This should allow you to open the files in a seamless way. 

