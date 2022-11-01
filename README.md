# Hosting a markdown formatted resume on GitHub



### *Purpose*

---

We will get to know about the practical steps of how to host and format a resume using Markdown, a Markdown editor, GitHub pages and Jekyll. Also we will hopefully get an idea about key principals in technical communication, as explained in Andrew Etter's book *Modern Technical Writing*.



### *Prerequisites*

---

A properly written and current resume is necessary in order to understand the actual processes for hosting a markdown-formatted resume on GitHub. Then, we'll create a résumé with a markdown format using [Markdown](https://en.wikipedia.org/wiki/Markdown), a lightweight markup language. I've included two excellent Markdown lesson links in the "More Resources" section if you want to learn more about Markdown or if you don't know anything about it yet. You have to have a resume prepared in markdown style at this point.

### *Instructions*

---

1. **Use Lightweight Markup** **Language**

   > One of the most important principles in technical communication nowadays is the use of lightweight markup. There are explanations for this. Contribution, as stated in Etter's book, is one of the fundamental principles of technical writing. People's capacity to contribute is hindered if our content is kept in XML-based languages. There are several specialist editors, but they are very expensive. Lightweight markup is preferable and free in all relevant ways for documentation. There are several minimal markups. We are using [Markdown](https://daringfireball.net/projects/markdown/) to format out resume.

   

2. **Use Distributed Version Control**

      EXPLAIN GIT!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!


   > According to Etter's book, "All sorts of people have extolled the virtues of distributed version control systems (DVCS) like [Git](https://git-scm.com/) / [GitHub](https://github.com) over centralized systems." 

   > Whenever we store our documentation, we should always place a file named README.md in the root of the repository. This file should contain
   >
   > 1. A quick summary of the product being documented
   > 2. Instruction on how to build the documentation locally
   > 3. Instruction on how to contribute
   >
   > For this project, we will use GitHub to host our markdown formatted resume. In order to do so, one  must have an account on GitHub. So, the fist step is to go to [GitHub](https://github.com) and create an account.
   >
   > If you already have an existing GitHub account, you just need to Sign in to our account. Then we should follow the following instructions:
   >
   > 1. Create a new repository
   >
   >    > * Click on the `new` green button on the repository section
   >    > * Give a name to the newly created repository
   >    > * You can add some description if you want
   >    > * Make the repository public 
   >    > * Click on the `create repository` button on the bottom left corner
   >
   > 2. Add files to the repository
   >
   >    > * Go to the newly created resume
   >    > * Click on the `add file` button 
   >    > * Choose `create new file` 
   >    > * Give the file name index.md
   >    > * Click on the `commit new file` button
   >
   > 3. Add another file named "README.md" using the same steps shown on 2.
   >
   > 4. Upload our resume
   >
   >    > * Go to the newly created resume
   >    > * Click on the file named index.md
   >    > * Click on the "edit" button ( in the top right corner, beside the `row/blame` button)
   >    > * Write the markdown formatted resume on the editor
   >    > * Click on the `Commit Changes` button on the bottom left corner
   >
   >    Now, our markdown formatted resume should be visible on GitHub whenever we go to index.md file of the newly created repository.

   

3. **Use static websites**

    >1. Firstly, we need to install ruby or the purpose of hosting the website. For installing ruby follow the given procedure:
    >
    >    > * Open the link for installing ruby which is mentioned in the "more resources" section. 
    >    > * Then click on the Rubyinstaller link given in the Ways of Installing Ruby section..
    >    > * Click on the red download button which is on the top of the webpage.
    >    > * Download any version of rubyinstaller with devkit.
    >    > * Open the downloaded application and choose the option to install all the packages of ruby (Option 3). 
    
    >2. Secondly, we also need to install jekyll. For installing jekyll follow the listed steps:
    >
    >    > * type "gem install bundler jekyll
    >    > * type "jekyll to check whether it got installed or not. If it got installed then the output will show the version of the jekyll that got installed offerwise the output will be an error.

    >3. After dowloading jekyll we need to clone the repository of the github. For cloning the github repository follow the listed step:
    >
    > * Open command prompt and type "git clone https://github.com/[username]/[userame].github.io where usemame is the GitHub's account username and [username].github.io is the name of the repository that is being cloned.

    >4. After creating the clone open the clone directory by using the command "cd [username].github.io".

    >5. Initialize the website by using the command "jekyll new [website name]" and then switch to the new website directory by using command "cd [website name]".

    >6. Install the webrick bundle by using "bundle add webrick" command first and then using "install bundle" command.

    >7. To open the website that you just created type "bundle exec jekyll serve" command. After that go to browser and search "http://localhost:4000".

    >8. Lastly, push the required files using Git desktop or by typing three listed commands in sequence:-
    >
    >   > * git add -all
    >   > * git commit -m "Initial commit"
    >   > * git push-u origin main After that just open the link "https://[your-github-name].github.io" in the web browser where you will find the website.

   
   Here is a gif showing how the resume should look like.....


   ##### More Resources

   * Resources on Markdown:
     * [Markdown Guide](https://www.markdownguide.org/extended-syntax/#strikethrough) is a remarkable place to learn syntaxes.
     * [Markdown Tutorial](https://www.markdowntutorial.com) is the best place to start learning about Markdown by practicing along.

   * A link to Etter's book :[ _Modern Technical Writing_ ](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS/ref=sr_1_1?crid=331C6HXMEK2GK&dchild=1&keywords=modern+technical+writing+by+andrew+etter&qid=1604455886&sprefix=modern+tech%2Caps%2C213&sr=8-1)

   * Resources on JeKyll:
     * A [video series](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB) tutorial on JeKyll

   

   ### Authors and Acknowledgement

   ---

   This README.md was written by Prabal Mendiratta.

   A great level of inspiration was taken from Andrew Etter's book _Modern Technical Writing_.

   I have to thank my group members of COMP3040 class. They helped me to understand the things needed for this writing to be completed.

   ### FAQs

   ---

   Q: Why is Markdown better than a word process?

   > Costly word processors are the best ones. It puts them out of most peoples' price ranges. People consequently neglect to contribute. Markdown, on the other hand, is open source and simple for the majority of people to use. This encourages individuals to participate.

   Q:Why does my resume not showing up?

   > Sometimes, especially after changing themes, it takes some time for our résumé to appear on a static website. If it hasn't shown within five minutes, check again. Once you've waited for the résumé to appear, check to see that you've followed all of the instructions in the Using Static Website section.
