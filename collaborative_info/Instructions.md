# isomip-plus

This is a central repository where we can create and upload figures and the code used to generate them whilst analysing and describing the differences between ice-shelf ocean models. Discussions, figures and scripts are very welcome.

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
- fork this repository (by clicking on the "Fork" button in the right hand corner)
- Click "Create Fork"
- Click on the arrow next to Fork to get to your fork
- Open your terminal and clone this repository on your machine

```
git clone git@github.com:misomip/isomip-plus.git
```
Add your fork as a remote (this will allow you to see this main branch and also your own fork).
```
git remote add <<yourname>> git@github.com:<<your-githubname>>/isomip-plus.git
```
where `<<yourname>>` will be the name of the remote pointing to your fork and `<<your-githubname>>` is your github username

(If you cloned your fork rather than the main misomip repository above, your fork will be the origin, so to add this main repository, type
```
git remote add misomip git@github.com:misomip/isomip-plus.git
```
To get upstream changes from other people that have been merged into the misomip folder, type `git pull misomip`)

  Create a new branch:
  ```
  git branch melt_rate_plot
  git checkout melt_rate_plot
  ```
  where melt_rate_plot is the name of your branch (it can be anything)
  
  make your changes to code, ideally by copying a notebook and then making the figures in the notebook (so that we each work on our own notebooks and avoid merge conflicts), then push it back up to your fork. There are some instructions for setting up a conda environment, and also style pointers in [Figure_guidelines](https://github.com/misomip/isomip-plus/blob/main/Figure_guidelines.md)
  
  ```
  git add XX 
  git commit -m "a message"
  git push <<yourname>>  melt_rate_plot
  ```
  (this pushes your branch, melt_rate_plot, to your fork, `<<yourname>>`.) Here, XX is the file path to the file you changed, or you can use `.` to get all changes. Add a helpful message in "a message"!
  
Final step: On Github when you open your fork of the repository, click "Compare and make pull request" when prompted and follow the instructions. This requests the code changes to the main MISOMIP repository. Then Claire will look at it and approve it.
  
You don't need to start from scratch: Xylar's plotting scripts have been (somewhat) converted to Jupyter Notebook form in [this folder](https://github.com/misomip/isomip-plus/blob/main/notebooks/general-plotting); alternatively there is a different method using xarray in [overturning-streamfunction](https://github.com/misomip/isomip-plus/blob/main/notebooks/overturning-streamfunction/OverturningStreamfunction.ipynb)

In both of these notebooks you can modify the `baserepo` (where this repository is located on your machine) and `basedrive` (where the data is stored on your machine). This should allow you to open the files in a seamless way. 

