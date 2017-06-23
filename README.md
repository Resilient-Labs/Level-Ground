# Level-Ground

### Theme Structure

#### Includes:
1) Banner - html partial for a row of content that has paragraph content, a button 
and/or a  title
2) Hero Video - html partial for a hero video banner in the background underneath 
content, a title and/or a button
3) Card - html partial for
4) Sidebar - html partial for the sidebar included on the news page and/or news posts
5) Head - html partial for the meta data and links to css, js and/or external dependencies
6) Header - html partial for the header that appears on every page
7) Footer - html partial for the footer that appears on every page

#### Layouts:
1) Classes - layout for the classes page
2) Home - layout for the home page
3) News Page - layout that loops through all of the news posts in the _news collection 
then displays that content in chronological order with a sidebar included in the layout
4) News Post - layout for a single news post that is the template for all news posts in
 the _news collection
 
#### Data:
1) Sponsors -

#### Pages:
1) Classes - markdown file that uses the classes layout
2) Index - markdown file that uses the home layout
3) News - markdown file that uses the news-page layout
 
#### Looking to fork, Emilio?
1) Set baseurl in your _config.yml to match the production URL without the host (e.g. 
/example, not http://jekyll.github.io/example).
2) Run jekyll serve and go to http://localhost:4000/your_baseurl/, replacing your_baseurl
 with whatever you set baseurl to in your _config.yml, and not forgetting the trailing slash.
3) Make sure everything works. Feel free to prepend your urls with site.baseurl.
4) Push up to your host and see that everything works there, too!

#### Setting up Forestry?
1) Fork this repositories gh-pages branch
2) Be sure that Github Pages is all set in the Settings for your forked repository
3) After forking, edit the config.yml file and change the url to your github pages url
4) Visit Forestry.io and connect with your github account
5) After logging in, go to the dashboard and add a site by clicking 'Add Site'
6) A modal should pop up with to options, click Import Existing site
7) Set jekyll as the generator
8) Sync a github repository and provide permissions to Forestry
9) Select the repository and set the branch to gh-pages 
10) Set a name for the newly generated site and set the url to be the concatenated 
string of the url and baseurl that is set in the config.yml file

#### Todo:
Responsive Footer
Success Stories
Gym
MindBody integration with Ali
Include loop of Sponsor logos (make reference in data)
put real videos and final images in
Clean up any css