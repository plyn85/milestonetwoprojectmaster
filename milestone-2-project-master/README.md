# Patrick Lynch Footballs Transfers Data Website

Milestone 2
One Project: Interactive  Frontend Development - Code Institute

My project is a data visualization website. The goal of the website is the reveal to the the user the extend to which the money spent on 
transfers has risen sharply since the turn of the century. This will be mainly done using data visualization charts which will be presented tp the user in the simplest way possible.

## Demo
A live demo can be found [https://plyn85.github.io/milestone-2-project/](https://plyn85.github.io/milestone-2-project/)

![Desktop Demo](https://res.cloudinary.com/plyn85/image/upload/v1574097773/milestone-2/Screenshot_23_jnvmqe.png "Desktop Demo")

# UX

The goal of the website Is to give the user a breakdown and 
easily readable visual representation of the last 19 
seasons of football transfer data. 2 row charts were used along 
with a pie chart, line graph and scatter plot to display the data. 
All charts used the same color scheme which was generated using the [http://tristen.ca/hcl-picker/](http://tristen.ca/hcl-picker/) website. A background color of black was 
used with white text In order to make the website visually pleasing to the eye.  Oswald was used for headings a Barlow semi condensed was used for smaller text. These texts where taken from google fonts.

### Client stories

1. As a new visitor to this website, I would like to be able to easily understand the data that Is being displayed.
2. As a new visitor to this website, I want to be able to Interact with the different charts understanding the purpose and how the Interact with each other.

3. As a returning visitor, I would like to be able to see any change to the data occured, such as updated transfer data from transfers that have occurred since I first visited the website.
4. As a returning visitor, I would wish to see any teams or leagues that changed position In the top ten spending charts If the data has been updated. 

### Wireframe mockups:
  <table>
   <tr>
    <td>Above 768px <img src="https://res.cloudinary.com/plyn85/image/upload/v1574093270/milestone-2/IMG_20191018_190657_r8uk7q.jpg" alt="wireframe mockup" style="width: 250px;"/> </td>
    <td>Above 768px <img src="https://res.cloudinary.com/plyn85/image/upload/v1574093274/milestone-2/IMG_20191018_190704_h33gin.jpg" alt="wireframe mockup" style="width: 250px;"/> </td>
     <td>Above 768px <img src="https://res.cloudinary.com/plyn85/image/upload/v1574095657/milestone-2/IMG_20191118_164149_uaarlj.jpg" style="width: 250px;"/> </td>
    </tr>
</table>
<table>
   <tr>
    <td>Above 768px <img src="https://res.cloudinary.com/plyn85/image/upload/v1574095644/milestone-2/IMG_20191118_164238_hnfyv6.jpg" alt="wireframe mockup" style="width: 250px;"/> </td>
    <td>Below 768px <img src="https://res.cloudinary.com/plyn85/image/upload/v1574095622/milestone-2/IMG_20191118_164332_htxxuh.jpg" alt="wireframe mockup" style="width: 250px;"/> </td>
     <td>Below 768px <img src="https://res.cloudinary.com/plyn85/image/upload/v1574095610/milestone-2/IMG_20191118_164410_e0mv2z.jpg" alt="wireframe mockup" style="width: 250px;"/> </td>
    </tr>
</table>

# Features

## Navbar

The navbar is contained at the top of the page and  and overlaps the callout Image.The navbar will remain In a a fixed position at the top of the page no matter what section of the of the page the user Is on. It has a football stats main header a football icon and three buttons that are  links to the other parts  of the page. The stats  button brings you to the section containing all the charts that display the data that is the main focus of the website. The transfer history section button brings you to the transfer history section which gives some background on football transfers. There Is also a home button where the user will be brought to back to the callout section no matter which other section of the page they are In.  The navbar changes to a drop down menu at 767px so it can be viewed more easily on smaller devices. Adjustments were made to the navbar using media queries for mobile landscape mode. 


## Callout 

The callout section has a background Image covering the entire view height of the screen. The callout text Is there to Introduce the user to the website and  gives them an Idea of the purpose of the website and what It contains. There is then a large data button which will bring the user to the main section of the page which contains all the graphs that display the data. Adjustments were made to the navbar using media queries for mobile landscape mode. I felt this was Important as the sight Is best suited to being viewed by the user In landscape mode on mobile the width of a mobile devices means charts are really small when displayed In portroit mode.  
 



## Data Section 

The data section is the main section on the page. It contains all the graphs and charts that display the data which Is the main point of the website. The aim is for the user to be able to easily understand the data. Explanations are provided beside each chart detailing the data displayed and how all charts Interact with each other. Two reset buttons are provided In this section both buttons will allow the user to reset all data displayed on the charts at any time. 

#### Pie chart 
The pie chart displays the percent of the of the players from each position who were transferred. If the user hovers over any of the slices of the pie chart that percent will be shown. If If the user clicks on any of the slices only  the players signed from that position will be displayed on the scatterplot below. Furthermore If the user was to then click on premier league row of the row chart only the premier league players signed for that position would be signed. To narrow it down even further the user could click on a row of the teams row chart which would narrow it down to just players signed in a certain position for that club.    

#### Scatterplot 
The scatter plot displays all 4700 transfers from the data set across the 19 seasons. If hovered over the user will see the season the players transfer took place, his name, the club he was transferred from plus the name of the club he was transferred  too and the amount of money that was spent on that transfer. The scatterplots dots are the same colors  as the players positions in the pie chart making it easy for the user to understand. The chart will change dynamical decreasing the number of dots displayed depending on what combination of charts the user clicks on. The chart can be returned to its original setting with every transfer displayed at any time by clicking on either reset button.   

#### Linechart
The line chart displays the total spend across all the seasons it gives the user a visual representation of the Increases and decreases spending over the course of the 19 seasons.If one of the dots Is hovered over the user Its will display the total spend for the particular season. 
This charts line will change dynamically. Depending on which combination of the other charts the user has clicked the lines height will change giving a visual representation of, for example the amount of money manchester united have spent on center forwards In the last 19 seasons.

#### RowCharts 
 The row charts come last on the page. The first row chart displays the ten highest spending leagues and the second chart  the highest spending clubs. Both row charts are dynamic and Interact with all other charts. For example If you click the la liga row of the row chart, the top spending teams chart will then display the top ten spending clubs from la liga rather than the top ten clubs over all. The scatter plot would then  only display la liga transfers and the line graph height will be a representation of the money spent in la liga over the 19 seasons.


## Transfer history section 

The transfer history section is reached by clicking the the transfer history button in the navbar. Its purpose was to give some background to transfers and  how the spending has Increased over time. This was done by adding 4 Images of some landmark transfers  In the history of football with some explanation text alongside. Lastly a video was added from youtube with a short documentary on how money could be ruining the sport.   

## Footer

A simple footer was added with a copyright an a link to my github account

## Features to Implement In the future

1. In the future I would Like to add more charts to website to further Investigate the data using the dc library.
2. At one point during the project when I felt I was well ahead of the schedule I conserved adding a card flipping matching game section to the project In which a user would turn over cards wit Images of famous footballers who were Involved In big transfers and try and match them. In the end I decided against it. This is something I would like to add In the future.





## Technologies
___
-  Vs code - I used vs code as my editor for building this website.
-  HTML 
-  CSS
- JavaScript  
  - Javascript was used extensively throughout the website. Plain javascript was used on all buttons on the website to hide/show different sections  and to reset the data using the reset data button.
  - Jquery was Imported and used for bootstrap navbar dropdown functionality. 
  - For the creation and manipulation of the data-visualization elements, the following Libraries where used
    - D3. js version 5(Although version 3 is thaught  on the course I wanted to use the most up to date Library 
 )
    - DC.js
    - Crossfilter.js 
     
-  Bootstrap - to make the website responsive and used for layout.
-  FontAwesome - to provide icons for the website.
- Google fonts - used to supply the fonts for this website.
- Cloudinary - All images where deployed using the cloudinary caching server.
- Git and Github Git used for version control. GitHub used as a remote repository and the hosting of this site.

## Testing 
I used WSC CSS Validation and HTML Markup Validation to validate the code, JSHint was used to check the javascript for errors. 

JavaScript testing can be found [here](milestone-2-project-master\README.md)

The responsiveness and correct displaying of all elements has been tested on a number of devices, browsers, and resolutions. Chrome, Firefox, Opera, Safari, Edge, and IE all display without issue.

Chrome dev tools were used to simulate multiple devices and widths, and no issues were encountered.

The following physical devices where  tested with no issues found.

 - Lenovo ideapad 320s
 - Apple iphone 8
 - Apple ipad 3 
 - Samsung galaxy A3
 - Huawei p20 lite  
 ### Client testing stories
 1. As a new visitor to this website, I would like to be able to easily understand the data that Is being displayed.
    - When I click on the data or stats button is brings me to a section with graphs displaying the data. As I scroll down the page I find the data easy to understand. The text beside each graph clearly explains what each graph purpose and how all the graphs Interact.

2. As a new visitor to this website, I want to be able to Interact with the different charts understanding the purpose and how the Interact with each other.
   - I first hover over center forwards in the pie chart i see that 25% of the players signed In the last 19 seasons play In that position. I click on center forward. I see on the scatterplot that the dots now  only display center forwards. This clear because it matches the color of the slice of the pie which I had clicked before. I hover over some of them and see that their name, clubs they were transferred between, the season they were transferred In, and the amount they were transferred for are all displayed. I now see a line graph which displays the total amount spent on center forwards by season. I hover over the 2018/19 season an see 1 billion was spent on center forwards.I next view the row chart and see the premier league and Serie A are still one and two. In a surprise addition I see the english championship is now In the top ten I realise the data displayed on these row charts will change depending on what has being clicked on the other charts. Finally I get to another row chart displaying teams I hover over the team I support manchester united and see that they spent 240 million pound on strikers. I click on Manchester United as I scroll back up the page I see all data has changed to just strikers purchased By Manchester United. I hit the reset button and reset all the data.  



   ## Manual testing of all elements on website

   ## Deployment 
The site is hosted on GithHub Pages at [https://github.com/plyn85/milestone-2-project](https://github.com/plyn85/milestone-2-project) and is built from the master branch. The Master
branch was created in the repository by:

  1. On GitHub, navigate to your GitHub Pages site's repository.
  2. Under your repository name, click  Settings.
  3. Use the Select source drop-down menu to select master as your GitHub Pages publishing source.
  4. Click Save

Should you wish to clone this:

   1. On GitHub, navigate to the main page of the repository.
   2. Under the repository name, click Clone or download.
   3. In the Clone with HTTPs section, click the copy icon to copy the clone URL for the repository.
   4. Open terminal.
   5. Change the current working directory to the location where you want the cloned directory to be made.
   6. Type git clone, and then paste [https://plyn85.github.io/milestone-2-project/](https://plyn85.github.io/First-Milestone-Project/)
   7. Press Enter. Your local clone will be created.

## Credits

### Content
 - All of the content In the data page was written by myself. The content in the transfer history section was mainly take from [Wikipedia](https://en.wikipedia.org/wiki/Main_Page)
 - The source dataset was obtained from [kaggle](https://www.kaggle.com/) user [Vardan](https://www.kaggle.com/vardan95ghazaryan) and can be found [here](https://www.kaggle.com/vardan95ghazaryan/top-250-football-transfers-from-2000-to-2018)   

### Media
All Images where obtained from [google Images](https://www.google.com/imghp?hl=en)
The video used Is from [youtube](https://www.youtube.com/)
### Acknowledgements
 - Rahul Patil my Code Institute mentor, for his invaluable advice and guidance.
- The [dc.js documentaion](https://dc-js.github.io/dc.js/docs/html/index.html) which I couldn't have done with out

 - The [Shanghai SSE Composite Index](http://bl.ocks.org/jun9/5632043) I found myself returning too reagulary for a better understanding of Dc js. 

 #### Disclaimer

   The content of this Website is for educational purposes only.

