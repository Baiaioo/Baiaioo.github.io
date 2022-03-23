# **How to Host a Resume on GitHub**  

## **Purpose:**  
This README will go over the steps on how to host a resume on GitHub. The steps will include the necessary programs needed for hosting, and will make reference to the key priniples from Andrew Etter's book Modern Technical Writing: An Introduction to Software Documentation.  

## **Prerequisites:** 
* An Account on GitHub.
    * create one if necissary.
* A basic understanding of GitHub and its functionality.
    * push, pull and commit features.
* An understaning of writing in Markdown.
    * Can use Github flavoured or another ide ex) Visual Studio Code.  
## **Instructions:**
### <ins>**Setup**</ins>
Etter enciurages that there should be a location host our static site from. GitHub is an excelent location to host, it allows for easy modification both online and offline, and has version control. it is very popular and easy to use. there is a lot of external documentation to ease the user into comfort.  
1. Log into your GitHub account that want to Host your resume on.
2. Create a new Repository and name it : UserName.GitHub.io.  
3. Set the repository to public.  
 
At this point you have you have the repository that that will host the static resume for your resume.  
### <ins>**Resume**</ins>
Etter states that the lightweight markup languages like Markdown have manny advantages. The most notible advantage is Markdowns ability to be easily converted XML, which is necessary to generate static websites. This is what we will do to convert your resume to our static website.  

4.  On GitHub in your repository, create a file called index.md.
    * It is important to save it as a .md file, this is for Markdown files.
    * you can edit this file on GitHub or clone it to one of your favorite editors (Visual Studio Code).  
5.  Write your Resume in the index.md file using Markdown.
6.  when you are done save and add the index.md file to your repository.
    * Adding comments to know what you did or added and then hit commit.
    * If written locally coppy ypur test over and commit the file.  

After step 6 we should successfully have our resume on our website. In the internet search bar type in userName.GitHub.io and it should pop up.  

### <ins>**Adding Style**</ins>
Etter is a fan of static webesites because they are secure and will be up as long as GitHub is up and running.  

The following steps will help to give your site some flair and style.  

7. Create a new file and name it _config.yml. 
8. Next you can copy and paste the following code from the link into your _config.yml.
    * Any of the selected styles. click into their _config.yml and get the code.
    * [styles](https://pages.github.com/themes/).

9.  Commit the changes.
10. Check your site and see the style.
11. below is a gif of how to find your site.
![a demo of site](https://imgur.com/a/1xkSo0S)


## **Additional Resources:**
1. [Markdown Tutorial](https://www.markdowntutorial.com/)
2. [Etter's Book: Modern Technical Writing](https://www.amazon.ca/gp/product/B01A2QL9SS/ref=ppx_yo_dt_b_d_asin_title_o00?ie=UTF8&psc=1)  
    * For purchase and Download.  
3. [GitHub pages supported themes](https://pages.github.com/themes/)
    * To get the code needed, go tho the README on the selected styles GitHub page.  
4. [Jekyll download](https://jekyllrb.com/docs/installation/)

## **Authors and Acknowledgments:**
* group members from class that provided feedback for the README and Resume:  
  * Alex Kitt  
  * Daniel Makarchuk  
  * James Watts  
  * Nitya Seth    
* [Template creator used in Resume:](https://github.com/pages-themes/architect) Ben Balter - Architect.  
## **FAQs:**
1. **Why is Markdown better than Word processor?**
    * Markdowns easy to learn simplified syntax, provides a much easier and more streamlined process than Mcrosoft Word, and only takes an average of an hour to learn.  
    * Markdown removes the clunkiness of the task bar, numerous mouse clicks and helps keep fingers on keyboards, making the documentation process quicker and more efficient.
2. **Why is my Them not showing up?**
    * GitHub does not automatically update with the most current changes. Updates can take up to 20 minutes to be applied after they have been comitted. If GitHub is overloaded the update may take up to and longer than an hour.
