# Documentation
In this file i am going to document the process of this project.

## Part A
I created a folder called TOWA and within that folder I created this Angular project with simple commands:

If Angular isn't installed, run this command on the cmd:
```js
npm install -g @angular/cli
```

To create an Angular project run the following command:
```js
ng new towa-app
```

## Part B
After setting up the project, the goal of Part B was to create the header, main & footer.

I created the header, main and footer as new components:
```js
ng generate component header/footer/main
```

### header
In the header I created 2 div-tags called leftSideItem & rightSideItem.
In the leftSideItem I added the Angular logo from the internet and in the rightSideItem I added 3 navigation items.

### main
For this part, the main should remain empty. I still created a skeleton just for myslef (to have a better outlook), which I changed later on.

### footer
In the footer I created 3 column-div-tags. On the left is the logo, the navigation items are in the middle and on the right side is just the contact information with my name, number and address.

## Part C
I already created the grid-layout in the parts before, but in this part i added the dummy data to the main section. I just need to change the dummy data to some real or scientific personas. I will most probably use professional football players.

### cards
Every card has an image, title, description/short text and a button which forwards the user to an external URL.

### responsiveness
To see if the website is responsive, inspect the page and click on "toggle device toolbar" to see how the design looks on a phone for example.