**Ονοματεπώνυμο**: Έλενα Βέργου

**ΑΜ**: Π2006041


| Εβδομάδα | Παραδοτέο |
| --- | --- |
| 1 | Goals - Φορκ του αποθετηρίου και δημιουργία της σελίδας της αναφοράς με τα προσωπικά στοιχεία σας, της σύνοψης με αυτόν τον πίνακα περιεχομένων, και συγγραφή της εισαγωγής με περιγραφή των αναγκών και των στόχων σας για το αντίστοιχο μάθημα ([link](#goal)) |
| 2 | Button ([link](#button))|
| 3 | Dependencies & Base System ([link](#Dependencies))|
| 4 | CSS Queries ([link](#css))|
| 5 | Text Editor and Plug-ins for Code Highlighting and Autocompletion ([link](#vim))|
| 6 | Collaborative Exercise 1 ([link](#collab))|
| 7 | CSS Mouse Eraser Programming Exercise ([link](#mouseeraser))|
| 8 | Download mp3 ([link](#youtubedl))|
| 9 | Visualization - using d3.js([link](#d3js))|
| 10 | Add a Status Bar to your editor (vim) and Configure a Color-Theme ([link](#vim-bar-colors))|
| 11 | Collaborative Exercise 2 ([link](#collab2))|
| 12 | Τελική αναφορά και αίτημα ενσωμάτωσης για βαθμολόγηση ([link](#final))|

<br/>

***

<br/>

## <a name="goal"></a> Week 1: Goals
I would like to work on front-end technologies, like HTML, JS and CSS, so that I can enhance my coding skills and my ability to create and enhance web content.
Also,  I would to take the opportunity to get more familiar with the Linux command line and various command line utilities that can enhance my experience as a developer and make
the experience of interacting with resources both locally and those hosted online a lot more seamless and effortless. 
On top of that, exploring git functionalities and workflows is a much needed skill in any developer's toolkit, as it's an intergral part of collaborating on coding projects and writing production code.

<br/>

## <a name="button"></a> Week 2: Button
For this programming exercise, I changed the implementation of the button by linking the click user action to opening a new tab that serves a webpage hosting weather forecasts for Corfu. The button look - SCSS properties for color, background color, border, border shadow, etc. and symbols from the Font Awesome CSS library, etc. - and text have been appropriately modified to convay to the user information about the functionality of the button and type of action they can perform by cliking it.


### ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) References
1. Link to my [commit](https://github.com/elenberg-io/site/commit/c4d10f7e134d3bd01f39122dde5b148b73520014#diff-9a05d7548950d29ede008a8c948797a40ec046fb480e65e4267e6fa6a5fe222e)
2. Link to `button.md` in the forked [repo](https://github.com/elenberg-io/site/blob/button%E2%80%93exercise/_remix/button.md) 
3. Link to my source code in [codepen](https://codepen.io/p2006041/pen/qBNNNNM?editors=1111)

### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Live Demo
![link](https://github.com/elenberg-io/assets/blob/main/ButtonExercise.gif)

<br/>

## <a name="Dependencies"></a> Week 3: Dependencies & Base System
For this command line exercise, I completed the *"set-up the main dependencies and demonstrate your base system"* assignment which had the following tasks to complete:
- **change your command prompt with your student ID:** I used `sudo nano` to open with superuser privileges the `.bashrc` file with the nano text editor. The `.bashrc` shell script contains the configurations for the terminal session and is run at the beginning of a new Bash session so we can introduce there a change to a special shell variable, PS1, which is used as the new prompt string. We then call `source` on the `.bashrc` shell script to execute its contents so that the PS1 value change can take effect in our running session. 
- **list your dot files change:** We use the `find` utility that looks for files and directories through the directories hierarchy so that we can locate all dot/hidden files and directories starting from the route directory. By passing in the argument `name` the regex `.[^.]*` we are excluding the special Linux directories `.` and `..`, and then by introducing the argument `-type f` we are only retrieving dot files, not directories.    
- **display your shell configuration file:** we use `less` with the `.bashrc` shell script to show our shell configurations since we are only interested in displaying them and not editing them.
- **display system information (hardware+software):** we use the `neofetch` command line utility that we have installed and in order to display more info regarding the state of our software and hardware we edit the `config.conf` configuration file of `neofetch` that controls what information is displayed when the `neofetch` utility is invoked from the command line. We enable then some extra display options by editing this file with the nano text editor, uncommenting the lines that display this extra information and then after saving we run `neofetch` and have the default plus the extra information displayed.

### ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) References
1. Link to the asciicast in [asciinema](https://asciinema.org/a/367994)


### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Live Demo
[![asciicast](https://asciinema.org/a/367994.svg)](https://asciinema.org/a/367994)

<br/>

## <a name="css"></a> Week 4: CSS Queries
For this programming exercise, I implemented changes changes to the CSS Media Queries exercise, by introducing more `@media` queries dependent on screen width adapting the background colors and the font colors as the screen is squeezed according to 2 different color palettes. The font size and the actual text displayed on the screen is also adapted for the changing screen size, by controlling which html div elements are displayed using their id from the `@media` queries. I've used global CSS variables to hold the color HEX codes which are declared in the `:root` selector and then I'm calling them accordingly from each `@media` rule.

### ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) References
1. Link to my [commit](https://github.com/elenberg-io/site/commit/3166974ad1a2e258a1aba45a12e1ffe0a770a1c1#diff-f4ae7ac56b1b79abd24151c1b033aa250f7e0771751aeeb8e9f90e8e4875af30)
2. Link to the `css-queries.md` in the forked [repo](https://github.com/elenberg-io/site/blob/button%E2%80%93exercise/_remix/css-queries.md)
3. Link to my source code in [codecen](https://codepen.io/p2006041/pen/oNLdwQo).


### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Live Demo
![link](https://github.com/elenberg-io/assets/blob/main/ResizingScreen.gif)

<br/>

## <a name="vim"></a> Week 5: Text Editor and Plug-ins for Code Highlighting and Autocompletion
For this command line exercise, I completed the *"text editor and plug-ins for code highlighting and autocompletion"* assignment.
I used the vim text editor and `vi` to to edit the .vimrc config file for the vim editor. I downloaded `Vundle`, a vim plugin manager that allows users to keep track of and configure the vim plugins right in the `.vimrc` file. I then included in the `.vimrc` file and installed the `youcompleteme` plugin for test autocompletition. I also included in the `.vimrc` file configuration for syntax highlighting.

### ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) References
1. Link to the asciicast in [asciinema](https://asciinema.org/a/371700)

### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Live Demo
[![asciicast](https://asciinema.org/a/371700.svg)](https://asciinema.org/a/371700)

<br/>

## <a name="collab"></a> Week 6: Collaborative Exercise 1
For this collaborative exercise I forked the 2 submodules, `_gallery` and `images`, changed the references of the submodules in my forked repo of `site` to point
to these forked submodule repos, added 2 new entries in `_gallery` and `images`, added the references to the appropriate slides and chronology and updated the `_config.yml` 
file in the forked `site` repo with the url of my *netlify* live site. I added 2 Archetypes, the Datapoint 2200 and the TRS-80, under personal computers and microcomputers respectively.

### ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) References
1. Link to the `_gallery` forked [repo](https://github.com/elenberg-io/_gallery)
2. Link to the `_gallery` forked repo [commits](https://github.com/elenberg-io/_gallery/commits/master)
3. Link to the `images` forked [repo](https://github.com/elenberg-io/images) 
4. Link to the `images` forked repo [commits](https://github.com/elenberg-io/images/commits/master) 
5. Link to the `site` forked [repo](https://github.com/elenberg-io/site)
6. Link to the `site` forked repo [commits](https://github.com/elenberg-io/site/commits/master)
7. Netlify Link with my 2 additions in [Archetypes](https://gracious-yalow-e2bb28.netlify.app/slides/archetypes/)
8. Netlify Link to Timeline of [Personal Computers](https://gracious-yalow-e2bb28.netlify.app/timeline/personal/)
9. Netlify Link to Timeline of [Microcomputers](https://gracious-yalow-e2bb28.netlify.app/timeline/micros/)


### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Live Demo
![link](https://github.com/elenberg-io/assets/blob/main/Collab1.gif)

<br/>

## <a name="mouseeraser"></a> Week 7: CSS Mouse Eraser Programming Exercise
For this programming exercise, I implemented changes changes to the Mouse Eraser exercise, by changing the pictures shown and the size and shape of the eraser.

### ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) References
1. Link to my commit in the forked [repo](https://github.com/elenberg-io/site/commit/adcf74f6ffe442a7c958dc7c2b88740e49cb41c9#diff-e8d1cd09284607023431678e80044d4802124ae6be7edaceec659e58726c7c80)
2. Link to the `mouse-eraser.md` page in the forked [repo](https://github.com/elenberg-io/site/blob/master/_remix/mouse-eraser.md) 
3. Link to my source code in [Codepen](https://codepen.io/p2006041/pen/qBNeWzw).


### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Live Demo
![link](https://github.com/elenberg-io/assets/blob/main/MouseEraser.gif)

<br/>

## <a name="youtubedl"></a> Week 8: Download mp3
For this command line exercise, I completed the *"download mp3"* assignment which had the following tasks to complete: I downloaded a video from youtube from my command line using youtube-dl and then played it using mpv.

### ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) References
1. Link to the asciicast in [asciinema](https://asciinema.org/a/376115)

### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Live Demo
[![asciicast](https://asciinema.org/a/376115.svg)](https://asciinema.org/a/376115)

<br/>

## <a name="d3js"></a> Week 9: Visualization - using d3.js
For this programming exercise, I created a `d3.js` world choropleth chart depicting cumulative COVID-19 total cases as of 2020-11-27 based on WHO data I downloaded and saved in my personal `data` git repo as a [`.csv`](https://github.com/elenberg-io/data/blob/main/WHO_COVID19_20201127.csv). I followed tutorials and links on the [d3.js](https://www.d3-graph-gallery.com/graph/choropleth_basic.html) site on how to create choropleths using the library. The chart allows the users to hover over a country and view via the tooltip that appears the cases. Moreover, it also allows a user to click on a country which then leads to a zoom in the country in the map. The color scale has been selected to move gradually from yellow to red, with deaper red corresponding to higher COVID-19 incidence rates. The chart also has a legend that explains the mapping between the colors and the incidence rate levels.

### ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) References
1. Link to my commit in the forked [repo](https://github.com/elenberg-io/site/commit/4c43b16d06ad0c63d872956be4e043471b604a9a#diff-7b222a67dcbaf16068515e6b1b9add2d77fdbc195841e95bd5ff01dfa82b5b6d)
2. Link to the `visualization.md` page in the forked [repo](https://github.com/elenberg-io/site/blob/master/_remix/visualization.md) 
3. Link to my source code in [codepen](https://codepen.io/p2006041/pen/abmbeoX).

### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Live Demo
![link](https://github.com/elenberg-io/assets/blob/main/COVID19.gif)

<br/>

## <a name="vim-bar-colors"></a> Week 10: Add a Status Bar to your editor (vim) and Configure a Color-Theme 
For this command line exercise, I completed the *"Add a Status Bar to your editor and Configure a Color-Theme"* assignment, where I configured my vim editor through the .vimrc config file to introduce the color theme dracula and to display the powerline status bar in vim. I used the `powerline` package and `dracula` theme which I cloned from git. I used Kazam to record my terminal session as asciinema was not properly recording colors so I couldn't demonstrate the effects of my changes on vim.

### ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) References
1. Link to the dracula theme on [git](https://github.com/dracula/vim)

### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Live Demo
![link](https://github.com/elenberg-io/assets/blob/main/vim-colors-bar.gif)

<br/>

## <a name="collab2"></a> Week 11: Collaborative Exercise 2
For this collaborative exercise I forked the 1 submodule, `extras`, changed the references of the submodules in my forked repo of `site` to point
to this forked submodule repo, added 1 new entry in in `_case_study` and `biography`, and added the appropriate images and thumbnails for the new entries. 
The new entries are related to the previous collaborative deliverable, where I wrote about Datapoint 2200 and the TRS-80. In this deliverable, I decided to focus on the biography of Jack Frassanito, who was integral in the development of Datapoint 2200, and then did a case study on CTC (Computer Terminal Corporation), the company behind
the creation of Datapoint 2200.

### ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) References
1. Link to the `_biography` forked [repo](https://github.com/elenberg-io/site/tree/master/_biography)
2. Link to the `_case_study` forked [repo](https://github.com/elenberg-io/site/tree/master/_case-study) 
5. Link to the `images` forked [submodule](https://github.com/elenberg-io/images/tree/master)
6. Link to the `extras` forked [submodule](https://github.com/elenberg-io/extras)
7. Netlify Link with my addition in [biography](https://gracious-yalow-e2bb28.netlify.app/biography/jack-frassanito/)
8. Netlify Link with my addition in [case studies](https://gracious-yalow-e2bb28.netlify.app/case-study/ctc/)

### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Live Demo
![link](https://github.com/elenberg-io/assets/blob/main/collab2.gif)

<br/>

## <a name="final"></a> Week 12: Τελική αναφορά και αίτημα ενσωμάτωσης για βαθμολόγηση
Making an evaluation of my progress and what I've learnt during this course, I believe that my skills and level of comfort with web technologies like html, css/scss, js and js libraries have increased and I've become a much more proficient user of git and understood some of the nuances in its use for individual projects as well as collaborative ones. Moreover, getting to use several new Linux command line utilities has opened up several new ways to make my workflow faster and more efficient and my interaction
with web and local content becoming more streamlined.
