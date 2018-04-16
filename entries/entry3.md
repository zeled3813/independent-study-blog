<h1>Entry 3: Installing Dependencies</h1>
<hr>
<p>The main focus for this week is to succeed in installing the `Gosu` gem and practice the syntax and concepts of `Gosu` with Ruby.</p>

<h2>Debugging the Ruby Gem and its dependencies</h2>
<hr>
<h3>Installing `Linuxbrew` to add Gosu's Dependencies</h3>
<p>Since I have been unsuccessful in installing `Gosu` due to several `Gosu` dependencies that are required in order to install `Gosu`, I have done researches online to find a solution to this problem. One of the solutions that I found was to update and add these dependencies using `Linuxbrew`, a package manager for Linux, which allows one to add packages by installing `Linuxbrew` to the home directory.</p>
<img src="../images/linuxbre.png"/>

<h3>Installing the Suggested Dependencies</h3>
<p>`brew install sdl2 libogg libvorbis` is the command line syntax that one has suggested to use in order to add the dependencies for `Gosu`. I have successfully installed these dependencies - including sd12, libogg, libvorbis - by using `Linuxbrew`, but unfortunately this did not solve the issue with the constant failure in building gem native extension for the `Gosu` gem. Thus, I had to find another way to solve the issue.</p>
<img src="../images/brew.png"/>

<h3>Additional Packages are Needed</h3>
<p>Going through the result, I found people who have had the same issue and answers for the problem. One of which was to use `sudo apt-get install build-essential libsdl2-dev libsdl2-ttf-dev libpango1.0-dev \
                     libgl1-mesa-dev libopenal-dev libsndfile-dev libmpg123-dev \
                     libgmp-dev` to install all of the packages included. This would install the packages listed but not all of the packages were installed either because they were missing from the package file or due to other issues.</p>

<h3>Packages Loss and Unmet Packages</h3>
<p>I was unsuccessful in adding the packages, so I had to google for a solution for this issue. I found that I could simply use `sudo apt-get update` to update the package file and add the missing packages to the file. This time I succeed in installing a couple more files but not all. I encountered a new problem: unmet dependencies for a few packages and broken packages.</p>
<img src="../images/broken-packages.jpg"/>

<h2>Takeaways</h2>
<li>Throughout the week, I have been looking for a way to install `Gosu` gem and its dependencieis. From constantly failing to install the `Gosu` gem, I learned that one problem could potentially lead to another, but that is okay. Because one answer could potentially lead to another answer. And the changing in error means that the previous error has been resolved. </li>

<h2>Next Step</h2>
<li>While I need to solve the issue with the `Gosu` gem, I also have to continue learning about concepts of `Gosu`, and think about what I want to create using `Gosu`. Although it might be difficult to know what to make at this point since I haven't tried actually coding with `Gosu`, but I believe things will workout.</li>
