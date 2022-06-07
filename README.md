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

- __Reviews__ 

  - The reviews section covers some feedback provided by previous customers.
  - This gives potential new customers an idea of the services provided by Meala and may offer comfort when booking an appointment.

![Reviews](/assets/images/meala-reviews.PNG)


- __The Footer__ 

  - The footer section includes links to the relevant social media sites for Meala. The links will open to a new tab to allow easy navigation for the user. 
  - The footer also contains the opening hours and location of the salon
  - The footer also contains a form in which the user can contact the salon directly through the site.
  - The footer contains all this information across every page to ensure ease of contact for any potential customers. 

![Footer](/assets/images/meala-footer.PNG)

- __Gallery__

  - The gallery will provide the user with supporting images to see the quality of the clients work. 
  - This section is valuable to the user as they will be able to see finished styles and creations available at Meala and decide for themselves from the images if they'd like to make an appointment. 

![Gallery](/assets/images/meala-gallery.PNG)

- __FAQ Page__

  - This page will allow the user to view multiple queries relating to hair extensions. Which is the most complicated and expensive service offered by Meala.
  - This page is valuable as this product requires a consultation, and having as much information possible before a client decides to make an appointment creates a good user experience.

![FAQ Page](/assets/images/meala-faq.PNG)

### Features Left to Implement

- Another idea for future implementation would be to include an online booking system, in which a person can make the appointment directly through the site, without having to contact the salon prior. 

## Testing 

- I tested the section through the inspect tool on Google for various screen sizes.
- I also opened the website on my phone, ipad and a laptop, all of which were responsive.
- I noticed while testing on my ipad that IOS automatically colors buttons as blue, so I had to go back and declare a background color of white so that it appeared the same across different OS.
- 


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

N/A 

## Deployment

- The site was deployed to GitHub pages. The steps I used to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the pages section, go to source and select 'main' then 'root' then 'save'
  - Refresh the page after a couple mins and the site was live.

The live link can be found here - https://cmeghan.github.io/Meala/index.html

## Credits 

- LoveRunning Project from Code Institute was very helpful and gave me inspiration for placement of certain elements, such as nav bar and landing page. 
- All photographs and media provided by Andrew Thomas Jones (owner of Meala)

### Content 

- The price list and contact information was taken from Hari's hairdressers in London. [Price list](https://harissalon.com/parsons-green/#foobox-6/0/andrew)
- The FAQ's for hair extensions were taken from this website [great lengths hair extensions](https://www.greatlengths.com/en-ie/faq)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- All the photos throughout the website were taken and provided by the client Andrew Thomas Jones.

