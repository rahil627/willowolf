welceme to
# willowolf (will-o'-wolf)
a digital space for my altruistic desires: my wills, manifested digitally. It’s also a cute spirit animal representing the will. :)

this repo contains the site for www.willowolf.com, which itself contains tiny or temporary homes for my wills/projects; If or when the project needs it's own sub-domain, it'll naturally find it's own home in one.

# *copied from the home-page (likely out-dated)*:
![](docs/assets/images/graveyard-of-fireflies.jpg?raw=true)


# thoughts
my interest in anti-civilization / eco-feminism / anarchy / etc. doesn't need a comunnity. I think it's just my personal intellectual way of understanding what's exactly wrong with civilizaition (industrialized farming, urban development, cars, institutions, governments: everything), not really a practice as permaculture is. It's more of a path that led to permaculture, by rationally justifying permaculture 'n existing primitive traditional cultures.
  - nah, it does deserve a community!! if i took this route, then so can many others!! It might not be as practical or a life-long passion, but it's still extremely important. It *lucidly* tells one what's wrong with civilization, which eventually leads one to stay out.

# borrowed code
https://github.com/garrettallen/fireflies


# notes
style: should be a similar style to rathewolf: hand-drawn (digital or not). more ethereal, as these are my wills: dreamy, faded colors 'n outlines, like a faded drawing.

can keep notes that affect all of the sub-domain sites here

this part of the readme serves as a simple version of GitHub's projects 'n issues. Start with those features off (in the repo's settings), then add features as needed... but i'd prefer a simple single text file for everything.

for sites should be controlled by me (like this one), remember to keep the wiki access restricted! For sites with a public wiki, make it un-restricted. `Settings, under the Features section, un-check 'Restrict editing to collaborators only'`

in the future, if and when GitHub Pages isn't enough, update the DNS of my domains: change (or remove?) the `A records` back to my web host's servers, 'n build 'n deploy from my server (or set-up some similar way to auto-build upon git changes from my web server?).



folder vs sub-domain: a design choice:
i initially thought: sites begin here, as a folder, then, as they grow, they can move their own sub-domain
...but in my case, because i want to use GitHub's project features such as a public wiki, a readme page, etc., it might be better to...
just give it it's own sub-domain from the beginning, because sites built with GitHub Pages require it's own domain or sub-domain (i think...)
otherwise: use git submodule to fetch a copy of the web-site folder from other git repos, and add it as a folder here
  - wellll, since it's so easy to add a sub-domain nowadays, might as well just do that, so that each project is completely seperate. Git submodule feels a bit toooo sloppy.
  - https://stackoverflow.com/questions/36554810/how-to-link-folder-from-a-git-repo-to-another-repo#36554930

to add a sub-domain, just add the 'A' records to the domain's DNS handler, then, update the domain name at GitHub project -> settings -> pages
to use a folder, add a git submodule to this repo for each project's site folder

a pro/con is that the sub-domain will hold a completely different site, and you must re-config Jekyll or whatever it uses, for *every* project.




todo:
the old project names (ega, fga, nga) are used for the folder names
  - this doesnt change anything for the web-site though
  - can't rename files in the web ui, need to use a local git repo and terminal?
change name in all writings  

other:  
https://stackoverflow.com/questions/13051428/how-to-display-images-in-markdown-files-on-github

GitHub Pages:  
https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll#creating-your-site
https://hackernoon.com/use-custom-domain-with-github-pages-2-straightforward-steps-cf561eee244f
https://github.blog/2017-11-29-use-any-theme-with-github-pages/
https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/troubleshooting-jekyll-build-errors-for-github-pages-sites#troubleshooting-build-errors
https://www.namecheap.com/support/knowledgebase/article.aspx/9645/2208/how-do-i-link-my-domain-to-github-pages

domains:  
https://www.namecheap.com/support/knowledgebase/article.aspx/9387/2218/what-is-namecheap-ssl-and-how-do-i-use-it/  
https://www.namecheap.com/support/knowledgebase/article.aspx/794/67/how-do-i-activate-an-ssl-certificate  
https://www.namecheap.com/support/knowledgebase/article.aspx/9637/68/how-can-i-complete-the-domain-control-validation-dcv-for-my-SSL-certificate  
https://www.namecheap.com/support/knowledgebase/article.aspx/9991/38/caa-record-and-why-it-is-needed-ssl-related  
  - add a CAA record with the value as the validator site (comodoco.com, sectigo.com, etc.)
  - this step was un-listed by the docs, probably was supposed to be e-mailed to me by the ssl provider
https://docs.github.com/en/github/working-with-github-pages/troubleshooting-custom-domains-and-github-pages  
  - check this site for the most recent validator being used (currently letsencrypt.org)
  
https://www.namecheap.com/support/knowledgebase/article.aspx/9646/2237/how-to-create-a-cname-record-for-your-domain

the `host` value for DNS records are usually the sub-domain ('www') or these exceptions: '@' for no sub-domain (rathewolf.com); '*' for wild-cards (as in re-direct records)


#### discord notes
when getting the link ("invite"), you have to click on settings / edit so that you can set it to permanent. Otherwise, you'll end up linking temporary links! :/ It seems like permanent links are a character longer than temporary ones... [invites docs](https://support.discord.com/hc/en-us/articles/208866998-Invites-101)


testing git ios app
