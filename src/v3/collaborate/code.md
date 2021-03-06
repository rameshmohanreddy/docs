---
title: Code
platform: web
type: collaborate
sidebarSorting: 3
categories: 
- Collaborate
order: 4
---

Collaborators can view the **HTML**, **CSS**, and **React** code of the elements of the prototype and can download* the entire project as a code package containing all HTML, CSS, and assets in a zip file.

> **Downloading Code requires a Pro plan**

![Code Mode](https://s3.amazonaws.com/animaapp/docs/web-app/Anima%204%20-%20Code%20mode.png)


1.  Open the prototype screen you want to view the code for
2.  Select **Code mode** at the top bar of the Omni view
3.  **Select any element**  in the prototype  and the code will appear in the Elements panel. Use the Path bar on the code panel to navigate to the parent of the selected element
4.  Use the drop-down menu to switch between **HTML and React code**
5.  _Optional_ – Click the red **Download Code** button to export the entire project as [a code package](https://docs.animaapp.com/v3/collaborate/code.html#The-Code-Package) (Requires Pro plan).


## **Advanced Features**

**Code mode** has a few more great features for developers to stay in control:

- **Overrides –** Select any element and add override its HTML tags and CSS properties. The changes are applied immediately, just like on Chrome Inspect Tool

- The difference between Anima Overrides and Chrome Inspect Tool is that overrides done in Anima are saved, and Chrome overrides disappear after refreshing the page.

![Code Override demo](https://s3.amazonaws.com/animaapp/docs/web-app/Anima%204%20-%20Code%20-%20Override%20opt.gif)


- **Assets –** Right side-bar contains all assets of the selected screen
  
![Download Assets](https://s3.amazonaws.com/animaapp/docs/web-app/Anima%204%20-%20%20Code%20-%20Assets.png)

- **Mark as Component** forces Anima to generate a React component for the selected element. If an element is marked as a component, then it will not be a div, an img, or any other HTML tag. Instead, it will become a custom React component. This is only relevant while viewing React code, not HTML.


**The Code Panel** 
![Code Panel](https://s3.amazonaws.com/animaapp/docs/web-app/Anima%204%20-%20Code%20panel%20options.png)

1. **Path Bar** allows you to navigate from the child component towards its parent and view the code of the entire component.

2. **Compare** feature allows you to match a snapshot of the original design that was synced from either Sketch, Figma or Adobe XD with the Anima’s results.

![Compare Code Generation with Design](https://s3.amazonaws.com/animaapp/docs/web-app/Anima%204%20-%20Code%20-%20Compare%20slider.gif)

3. **HTML/React** menu changes the code view from HTML to React view.

4. **React Code Preferences** allow you to choose the React syntax Functions or Classes.

5. **CodePen** button opens the selected element in CodePen.


## The Code Package
![Downoad code package](https://s3.amazonaws.com/animaapp/docs/web-app/Anima%204%20-%20Export%20code.png)

- Click "**Download HTML**" in the top right corner to download the entire Anima project as a **Code Package** . 
- The code package is a zip file that contains all the HTML files, CSS files, and assets of the entire Anima project.


![Code Package](https://s3.amazonaws.com/animaapp/docs/web-app/Anima%204%20-%20Code%20package.png)

-  [Download](https://s3.amazonaws.com/animaapp/tutorials/Anima%203.0%20Code%20Package%20Sample.zip) the sample Code Package and run it locally to preview it perfectly in your browser.

![HTML Files locally](https://downloads.intercomcdn.com/i/o/95946171/ac800bee0f0f17046bb6e40e/1%2AYDIyhtQnkGiqtkBQQCYjpA.png)

- If you open the files in a text editor you’ll see a well structured HTML and CSS.
– If the design is using Anima Breakpoints, Anima will export all connected screen sizes (i.e.: Desktop, Tablet, Mobile) as one HTML and CSS file.

![CSS Structure](https://downloads.intercomcdn.com/i/o/95946174/5f1c4df3908408ac2d1196a1/1%2AgqcF2yZX74Rtk5pkn1YTbw.png)

![CSS Structure](https://downloads.intercomcdn.com/i/o/95946175/a309cb5874ab6d7a51cb08dd/1%2A8ww5nOrz-WFWquqwgQW2xQ.png)

## Export FAQ

In order to keep your website **pixel-perfect**, easily made **responsive**, load **crazy fast**, yet **clean** & **readable **— We made some choices for you about the code style. Here are some questions we get about code packs.

**Why Absolute Positioning?**

Developers tend to use CSS _relative_ position, while Anima composes CSS with _absolute_ position by default. The upside here is getting high fidelity, bringing your design as close as possible to **pixel-perfect** in browser. You’re not likely to see a line break where you didn’t expect it (_relative_ position downside).

**Why did my Forms break?**

When you’re hosting your website with us, we also give you a tiny backend server to support your forms. It allows users to send to that server, and we store it for you.

This server-side code cannot be simply exported and included in the code package, as it needs to run on a server rather than on the browser (which is called client-side code).

Therefore, when exporting code with forms, you’ll have to implement your own server to capture form submissions, and store your data.
