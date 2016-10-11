<h1>training</h1>
Please don't post solutions. Helpful examples of how to code exploitation related tasks can be found in the examples repo.
<h2>git instructions</h2>

<h3>initial setup</h3>
<ol>
    <li><a href="http://rogerdudler.github.io/git-guide/">Here's</a> a good Git tutorial. Use the commands rather than other ways of interacting with Github to build proficiency.</li> 
    <li>Install git if you don't have it</br>
        &nbsp&nbsp<code>sudo apt-get install git</code>
    </li>
    <li>make a new directory wherever you want. Here we'll make one named 'training.'</br>
        &nbsp&nbsp<code>mkdir training</code>
    </li>
    <li>go into the directory and clone this repo to download a working local copy</li>
        &nbsp&nbsp<code>cd training</code></br>
        &nbsp&nbsp<code>git clone https://github.com/0x0Titan/Training</code>
    </li>
</ol>
<h3>pull updated content from remote repo</h3>
<code>git pull origin</code>
<h3>contributing</h3>
<ol>
    <li>
        make desired changes in your local training/ directory
    </li>
    <li>
        after you are done for the day, update and save your commit by</br>
        &nbsp&nbsp<code>git add --all</code></br>
        &nbsp&nbsp<code>git commit -m "<your commit message>"</code></br>
        &nbsp&nbsp(you can put whatever message describing your commit between "&nbsp")
    </li>
    <li>
        Push your commit to the remote repo</br>
        &nbsp&nbsp<code>git push origin</code></br>
    </li>
    <li>
        You may get an error message if someone else made changes to the remote repository since your last pull.</br>
        &nbsp&nbsp<code>git pull origin</code></br>&nbsp&nbsp
        This will make your local folder up-to-date with web repository and you should be able to push.
    </li>
</ol>
