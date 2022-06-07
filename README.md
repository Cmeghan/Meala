MEALA 
======



FEATURES 
-----
- Navigation 
The Navigation bar is featured at the top left of the page. With the brand/website name in the top left corner, which when clicked takes the user back to the homepage. 
The 3 pages within the website are located on the top right of the page on each page to easily navigate throughout the website. 
The client's brand is simple and uses a lot of natural tones so I chose a simple font with brown/tan colors which contrast eachother for ease of visibility, while complimenting the client's brand. 

<!--- Space for picture of nav bar --->

- Header 
The header shows images of the client's workspace, which suits the overall theme of the website in color. 
The header immediately showcases the location of the business and the name of the brand, overlapping the background image. 
The fonts are consistent and subtle throughout. 

<!--- Space for picture of header --->

- About 
The about section provides information regarding the client's experience and history.
The about section also provides brief information regarding mobile services, location, brands, etc. 
Below the about section is an image bar showing images from the client which match the branding across their social media. 

<!--- Space for picture of about --->

- Price List 
The price list section shows a list of all the services available and their corresponding prices.
The fonts are consistent in tone and the information is clearly visible for customers on the front page.

<!--- Space for picture of price list --->

- Client Reviews
The client reviews section contains some brief reviews clients have submitted on social media.
Above the reviews is another image bar with on-brand images from the client with the statement "Get the Meala experience" 

<!--- Space for picture of reviews --->

- Footer 
The Footer across all 3 pages contains multiple ways to contact the business.
It contains the address of the business and the phone number.
It contains a contact form for users to contact the business directly through the website. 
It contains the opening hours of the business.
It contains links to the business' multiple social media platforms. 
All this information was placed in the footer across the website so that users always have easy access to contacting the business without needing to look for this information themselves.

<!--- Space for picture of footer --->
<!--- Space for picture of footer --->


<!--- Space for picture of footer --->

- BUGS

Struggled to push through data to Github as I made a change on Github while Gitpod coding was still open. Kept receiving error “tip of your current branch is behind its remote counterpart”

When I tried to fix error by using "git pull" I kept receiving error "fatal: Not possible to fast-forward, aborting." 

I googled the error and found a suggestion here "https://stackoverflow.com/questions/13106179/fatal-not-possible-to-fast-forward-aborting" 

Terminal bug error resolution:
"gitpod /workspace/Meala (main) $ git pull --rebase
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
error: could not apply 6bdacea... updated readme
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply 6bdacea... updated readme
gitpod /workspace/Meala (main|REBASE 3/3) $ git add/rm <conflicted_files>
bash: syntax error near unexpected token `newline'
gitpod /workspace/Meala (main|REBASE 3/3) $ git rebase --continue
README.md: needs merge
You must edit all merge conflicts and then
mark them as resolved using git add
gitpod /workspace/Meala (main|REBASE 3/3) $ git pull
error: Pulling is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.
gitpod /workspace/Meala (main|REBASE 3/3) $ git add .
gitpod /workspace/Meala (main|REBASE 3/3) $ git commit -m "test"
[detached HEAD b3164a7] test
 1 file changed, 1 insertion(+)
gitpod /workspace/Meala (main|REBASE 3/3) $ git push
fatal: You are not currently on a branch.
To push the history leading to the current (detached HEAD)
state now, use

    git push origin HEAD:<name-of-remote-branch>

gitpod /workspace/Meala (main|REBASE 3/3) $ git push origin HEAD:main
Enumerating objects: 24, done.
Counting objects: 100% (24/24), done.
Delta compression using up to 16 threads
Compressing objects: 100% (14/14), done.
Writing objects: 100% (16/16), 1.61 KiB | 1.61 MiB/s, done.
Total 16 (delta 8), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (8/8), completed with 5 local objects.
To https://github.com/Cmeghan/Meala.git
   c7cc93b..b3164a7  HEAD -> main
gitpod /workspace/Meala (main|REBASE 3/3) $ "

# Meala

The Meala website was set up as a landing page for a local hair-styling business named 'Meala', looking to entice potential new customers, and aid existing customers in making bookings, and gathering information. 

![Responsive Design](/assets/images/Responsive.PNG)


## Features 

The website has been set up with all the information a customer should need prior to making a booking or consultation, this includes pricing, contact information, information about the services rendered, along with information regarding the stylist themselves.

About: Important for customers to know the qualifications and history of the brand/client.
Price List: Potential customers can review price list before contacting directly for ease of experience.
Reviews: Gives customers a chance to see what previous customers have had to say about the business.
Contact Form: Easy access for potential customers to reach out directly to the business.
Gallery: Images of the clients own work to entice potential customers.  
FAQ: Information regarding the clients hair extension service as this information would be valuable for customers prior to making a booking.

### Existing Features

- __Navigation Bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, Gallery and FAQ page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](/assets/images/meala-nav.PNG)

- __The landing page image__

  - The landing includes a photograph with text overlay to allow the user to see the location of the salon.
  - This section introduces the user to Meala with an 'on-brand' image of the client's salon.

![Landing Page](/assets/images/meala-landing.PNG)

- __About Section__

  - The About section gives the user insight into the stylist and owner of the business, while also providing information about which brands are used, and a brief overview of services rendered. 

![About](/assets/images/meala-about.PNG)

- __Image Bar__

  - After speaking to the client, they advised that besides the gallery, they also wanted the user to see their work on the homepage, so that potential clients can see the clients work immediately after opening the website. 

![Image Bar](/assets/images/meala-imagebar.PNG)

- __Price List__

  - I've included a price list for all services rendered by the client.
  - I have included this on the front page as typically this information is of paramount importance to customers, and being upfront about pricing creates a good user experience. 

![Price List](/assets/images/meala-price.PNG)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for Meala. The links will open to a new tab to allow easy navigation for the user. 
  - The footer also contains the opening hours and location of the salon
  - The footer also contains a form in which the user can contact the salon directly through the site.
  - The footer contains all this information across every page to ensure ease of contact for any potential customers. 

![Footer](/assets/images/meala-footer.PNG)

- __Gallery__

  - The gallery will provide the user with supporting images to see what the meet ups look like. 
  - This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together. 

![Gallery](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png)

- __The Sign Up Page__

  - This page will allow the user to get signed up to Love Running to start their running journey with the community. The user will be able specify if they would like to take part in road, trail or both types of running. The user will be asked to submit their full name and email address. 

![Sign Up](https://github.com/lucyrush/readme-template/blob/master/media/love_running_signup.png)

For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- Another feature idea

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 