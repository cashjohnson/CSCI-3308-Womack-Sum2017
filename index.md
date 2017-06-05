asdf

| Discussion Forum | Course Website | Lectures | Repository |
|:---:|:---:|:----:| :----:|
| [Piazza](https://piazza.com/colorado/summer2017/csci3308/home) | [Moodle](https://moodle.cs.colorado.edu/course/view.php?id=163) | [Youtube](https://www.youtube.com/user/chrisdwomack) | [Github](https://github.com/chris-womack/CSCI-3308-Womack-Sum2017/) |

### Virtual Machine

To get started you will need to download the **Virtual Machine** (or VM) from the [CU Foundation](https://foundation.cs.colorado.edu/vm/) website. The website will explain how to download and install the VM. The site also covers some of the issues that may pop up while trying to install, so check this first before asking for help.

You'll want the Summer 2017 Edition for this class.

If you have trouble installing the VM then get help [here](mailto:ethan.hanner@Colorado.EDU).

### Class Forum

I will be teaching multiple courses this summer and have not been provided with additional help (TAs). So in order to ensure you receive the help you need, we will be using [Piazza](https://piazza.com/colorado/summer2017/csci3308/home) for discussion/questions regarding problem sets and programming assignments.

Sign up using the following link: [Piazza Forum - CSCI 3308](https://piazza.com/colorado/summer2017/csci3308)

### Course Website

Please enroll ASAP in the [Moodle course web page]((https://moodle.cs.colorado.edu/course/view.php?id=163)). All of your class material will be available through Moodle, and all exams will be administered here as well. The enrollment key is: **agile**

### Github

As moodle can be a little tedious to use for downloading all class material, I will be maintaining a repo for this class with the following content:

- Labs
- Lecture Slides
- Demo Code from Class

### Fork Repository

There are several ways to get the course content. The easiest way, though less versitile if changes are made to the repo, is to download the content through the download links to the left. The second method is to use git and fork the repo to your account, then clone the repo to your local machine. You can follow the steps below to fork/sync the repo:

- Ensure you have a Github account. If you don't you can sign up [here](https://github.com/join).
   - Also checkout the [Student Developer Pack](https://education.github.com/pack) if you don't already have it. Some really good stuff here including private repos
   
- Use the "View on Github" link to the left to view the [repo page](https://github.com/chris-womack/CSCI-3308-Womack-Sum2017) and select fork in the top right hand corner.

- Now we need to clone the repo to your local machine. First open a terminal in the VM

- Type the following to see if git is installed

   ```Shell
   $ git
   ```

- If the return looks like this:

   ```Shell
   bash: command not found: git
   ```
   - Then run:
   ```Shell
   $ sudo apt-get install git-all
   ```

- Clone the repo in your home area (*Note:* Change \<GITHUB_USERNAME\> to **your** Github username)

   ```Shell
   $ git clone https://github.com/<GITHUB_USERNAME>/CSCI-3308-Womack-Sum2017.git
   ````
*Note:* You will likely need to input your username and password for Github unless you have setup your ssh keys.

### Sync Repository

These steps will sync your local repo with the current version of *this* repo. Run in local repo directory

```Shell
# First add the upstream
git remote add upstream https://github.com/chris-womack/CSCI-3753-Womack-Sum2017

cd 

# Second fetch
$ git fetch upstream

# Third switch branches
$ git checkout gh-pages

# Now merge with local master
$ git merge upstream/gh-pages

# Finally push to origin master (remote)
$ git push origin gh-pages
```

<br>
### Course Calendar

<iframe src="https://calendar.google.com/calendar/embed?showTitle=0&amp;showNav=0&amp;showDate=0&amp;showPrint=0&amp;showTabs=0&amp;showCalendars=0&amp;showTz=0&amp;height=600&amp;wkst=1&amp;bgcolor=%23FFFFFF&amp;src=31p3a3ekqu49520g028l5m5tvo%40group.calendar.google.com&amp;color=%232952A3&amp;src=1433ho9msln3okpsjpmcdgo5bc%40group.calendar.google.com&amp;color=%23333333&amp;src=b51dogf11hmlth8evuon0l1so4%40group.calendar.google.com&amp;color=%231B887A&amp;src=p8nd7l2nohrrtpu5s16h0js7q8%40group.calendar.google.com&amp;color=%235229A3&amp;src=vdutitopq5faosmmhnsc26oc34%40group.calendar.google.com&amp;color=%2329527A&amp;src=lrgkd57gd16f6j77tesvljcue4%40group.calendar.google.com&amp;color=%23333333&amp;src=teasdhdav1suh71ulk7ekalid8%40group.calendar.google.com&amp;color=%23182C57&amp;ctz=America%2FDenver" style="border-width:0" width="100%" height="600" frameborder="0" scrolling="no"></iframe>

<br>

### Course Agenda

<iframe src="https://calendar.google.com/calendar/embed?showTitle=0&amp;showNav=0&amp;showDate=0&amp;showPrint=0&amp;showTabs=0&amp;showCalendars=0&amp;showTz=0&amp;mode=AGENDA&amp;height=600&amp;wkst=1&amp;bgcolor=%23FFFFFF&amp;src=31p3a3ekqu49520g028l5m5tvo%40group.calendar.google.com&amp;color=%232952A3&amp;src=1433ho9msln3okpsjpmcdgo5bc%40group.calendar.google.com&amp;color=%23333333&amp;src=b51dogf11hmlth8evuon0l1so4%40group.calendar.google.com&amp;color=%231B887A&amp;src=p8nd7l2nohrrtpu5s16h0js7q8%40group.calendar.google.com&amp;color=%235229A3&amp;src=vdutitopq5faosmmhnsc26oc34%40group.calendar.google.com&amp;color=%2329527A&amp;src=lrgkd57gd16f6j77tesvljcue4%40group.calendar.google.com&amp;color=%23333333&amp;src=teasdhdav1suh71ulk7ekalid8%40group.calendar.google.com&amp;color=%23182C57&amp;ctz=America%2FDenver" style="border-width:0" width="100%" height="600" frameborder="0" scrolling="no"></iframe>
