[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/IMjfWEJv)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11792676&assignment_repo_type=AssignmentRepo)
Week Two Lab Instructions ~ Plants Web Site

1. Clone the starter files from GitHub Classroom to your computer
2. Observer the preferred organization

   <img width="274" alt="Screenshot 2023-09-02 at 10 12 58 PM" src="https://github.com/SSC-WebDevelopment/wdd221-week2-lab/assets/15079402/4d32a1cc-7947-469a-9b99-53884f55fe5e">

3. After you have cloned the files, launch the plants.html and observe the code
   - Nothing should be too foreign at this point
   - The list items contain an onclick event that basically captures the plantImg id located inside the `<figure>` section of the code

```
<!--this is the area that will display a plant image once the plant link is clicked by the user, the getElementById method is calling this id attribute-->
      <article>
         <figure>
            <img src="#" width="640" height="400" alt="" title="" id="plantImg"/>
            <figcaption>
               <script>
                  /*
                     Information on available plants
                     including link to USDA website
                  */
                  document.write("<p>Plant choices for <a href='http://planthardiness.ars.usda.gov'>hardiness zones</a> 5a-6b</p>");// hardiness zones for Chicago and surrounding area
               </script>
            </figcaption>
         </figure>
      </article>
```

- The JavaScript replaces the image src with the appropriate images once the visitor clicks the link
- Observe the document.write line within the script section
- Finally, observe the link to the external JavaScript code, just like CSS, it is highly advised that your scripts reside in a separate file within a separate folder

4. Create a new file and save it as plants.js, make sure it resides inside the js folder/directory
5. Code the JavaScript as follows (it’s not necessary to key all of the comments, however, coders document name, date, and purpose):

```
/*
	JavaScript ~ WDD221
	Week 1 ~ Guided Activity ~ Working with Events and Elements
	Web Site for a fictional company ~ Tinley Xeriscapes
	Plants web page
	Author:    ehancock
	Date:      2023
	Filenames: plants.html, tinley.css, tinleyhand.css
*/

//define variables containing img src values
let blanket = "images/blanket.jpg";
let bluestem = "images/bluestem.jpg";
let rugosa = "images/rugosa.jpg";
```

6. Save changes, test in a browser of choice. Make sure it functions as desired, click the plant name link and an image displays in the designated area.
<img width="961" alt="Screenshot 2023-09-02 at 10 31 15 PM" src="https://github.com/SSC-WebDevelopment/wdd221-week2-lab/assets/15079402/38ee5ed0-add7-4d18-bc07-20241b72660a">

7. Validate files and push to GitHub
8. Submit to GitHub Classroom
9. Adjust your landing page to include this new assignment
10. Submit the link to the assignment on your landing page to Blackboard
