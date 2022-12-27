# Social Recipes

Social Recipes is a site for sharing 2 (for now) of my favourite recipes to make for social gatherings. The site will be targeted at people organising small friend groups, social nights and/or game nights.


<!-- Add website example in different formfactor -->
![Responsive Mockup](#)

## Features

- __Navigation Bar__

  - Featured on all three pages, the responsive navigation bar includes links to the Starter, Home page and Dessert page and is consistent on each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.
  - The navigation bar will highlight the page you are currently on.

![Nav Bar](#)

- __The landing page image__

  - The landing includes a photograph with a social scene to help the user emotionally connect with the purpose of the visit.


![Landing Page](#)

  - This section contains a brief paragraph on why I created the site.


- __The Footer__

  - The footer section includes copyright information and a smaller version of the nav bar.
  - The footer is valuable to the user as it eases the navigation to other pages after scrolling.

![Footer](#)

- __Starter__

  - This provides a savoury recipe that is very easy to share.

![Starter](#)

- __Dessert__

  - This provides a sweet recipe.

![Dessert](#)

### Features Left to Implement

- __Submit Recipes - Scrapped due to scope__
- This would help the site to grow organically, with some review oversite.

- __Collapsable navigation bar__
- This would help keep the navigation clean as the number of pages increases. Unnecessary at this stage. 

## Testing

I used basic ongoing testing as I was working through the different sections, resizing the browser to make sure everything reacts the way I expected and using Chrome's Developer Tools Toggle device toolbar function. 

Floating footer when not enough content on page. Fixed using flexbox vh on body.

Tested with lighthouse, first test failed on Performance, 68. Replaced images with webp format and moved fontawesome script to below footer.

Validator testing found duplicate id="main" and h3 nested in p. id changed to class and p elements replaced with h3.



### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Femarnus.github.io%2Frecipe1%2Findex.html), after correct first check result.
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Femarnus.github.io%2Frecipe1%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub)

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - Select "Deploy from a branch" in the Source Dropdown
  - Select main in the Dropdown under Branch, after an amount of time the page will have a ribbon at the top that will say "Your site is live at https://NAME.github.io/REPONAME/" and should have a visit site button.

The live link can be found here - https://emarnus.github.io/recipe1/


## Credits

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism.

You can break the credits section up into Content and Media, depending on what you have included in your project.

### Media & Content

- Hero image; Photo by <a href="https://unsplash.com/@kchance8?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Kelsey Chance</a> on <a href="https://unsplash.com/photos/BB4GbHiU1KY?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

- Home nav image taken from: Photo by <a href="https://unsplash.com/ja/@yvonnemorgun?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Lee Myungseong</a> on <a href="https://unsplash.com/photos/y1XXWct5rBo?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
- Home text content taken form https://oakwoodresort.com/14-unbeatable-reasons-to-have-a-grand-gathering-this-year/ and amended.

- Recipes and images were taken from:
Starter: https://www.bbcgoodfood.com/recipes/festive-filled-brioche-centrepiece-baked-camembert
Desert: https://www.bbcgoodfood.com/recipes/black-forest-fridge-cake -->

- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

- Readme template taken from https://github.com/Code-Institute-Solutions/readme-template

<!-- Delete this section when done.

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

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! -->