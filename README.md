
# Portfolio Project - 100Hires

An Readme Markdown file for my steps installing tools.


## Tools

**IDE(s):** *Cursor*, *VSCode* (what I am using more frequently)


**Websites:** *Cursor*, [*readme.so*](https://readme.so/) (for better structuring - syntaxes are still made by my own). 

**Content**: [Markdown Guide](https://www.markdownguide.org/cheat-sheet/), Git (commit and push). 


## Installation Steps

**Step 1:**  From the request, I start with installing Cursor IDE at [Cursor Website](https://cursor.com/)

![alt text](https://cdn.shopaccino.com/igmguru/images/what-is-cursor-ai-66191743451294.png)

**Step 2:** Installing extensions - There are two extensions including Claude Code and Codex as following: 

*Claude Code*

![alt text](https://miro.medium.com/v2/resize:fit:1400/1*NocnWd9w7IxzEmueRdUDdA.png)

*Codex*

![alt text](https://us1.discourse-cdn.com/openai1/original/4X/f/a/e/faee0d33f59609b05d3c4975ddaf10a29a279b36.png)

**Step 3:** Create new repo on Github

Since I alread had an account on Github, I will make a new repository called [100Hires](https://github.com/chandang206/100Hires). 

I used the command line (cmd) in terminal for initialising the README file as follows:

```bash
echo "# 100Hires" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/chandang206/100Hires.git
git push -u origin main
```
**Result**

```bash
numerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 219 bytes | 219.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/chandang206/100Hires.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
```



## Lessons Learned

Since I have previous experiences in making README file, as well as push to GitHub, it was not too much of a problem, the only issue was it has been a long time since I made a commit and push to GitHub, so some steps were needed for recollecting:
1. Check for instruction on GitHub
2. Using Markdown Guide for some forgotten syntaxes (bold, italic, space, links, images)
3. Review on commit and push process through Git. This also include:
- Create new repository with public setting (this is the easiest one).
- Initialise commit -> git inint -> commit with -m -> branch main -> push to origin main (this takes time as I need to review again the procedure of push and commit change using command line)
## Authors

Actually, I do have a portfolio by coding you can find it [here](https://chandang206.github.io/Portfolio/)

