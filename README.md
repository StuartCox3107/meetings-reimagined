
![Imgur](https://i.imgur.com/hMw7Uzp.png)

---

# **meetings re:imagined**

## **Aim of the site**

This is a site designed to showcase a (fictional) training and meeting centre. The site will 
be targeted towards corporate bookers and corporate travel agents, and has a definite
business to business aim.

[Link to live site (opens in same window, click back when done)](https://stuartcox3107.github.io/meetings-reimagined/)

---

## **User Stories**

    "As a corporate administrator looking to book a venue for my manager, I need the site
    to give me everything I need to make a decision without having to return to it, or ask questions"

    "As a corporate travel agent I want to be assured that this solution for my 
    client is a professional, and I want to rest in the knowledge that the venue will be able to deliver"

    "As a manager, I want this venue to showcase the offer they have, and when I look at it 
    - to be re-assured that this venue will provide a productive space where my team will 
    be innovative and creative"

---

## **Site features**

### **Header**
The enquire button needs to be fixed to give an ever present opportunity
to get to the enquiry form.

### **Main picture**
This needs to be big and bold, and really showcase a positive aspect of the product.

### **Overview section**

This should provide an overview of what is offered and provided, transport convenience,
the main features of what is included, as well as where this venue differs from others.

### **Carousel**

This provides a further visual of what the venue looks like in terms of individual rooms, and demonstrate the overall
look and feel of the venue. 


### **Capacity chart**

Present on desktop only, removed for smaller devices shows numbers possible in individual rooms. 
On smaller devices this information will be conveyed in the space description section also.

### **Space description & room information**

This provides detail about what specific rooms there are with an overview and an image of them. 
Also a link to a **CATERING** PDF file opening in a different window, and some information on 
reception services and AV.

### **Contact**

A contact form with name, email, phone number, number attending, date wanted, room desired,
and "What do you want to achieve" fields. 


## **UX & Wireframes**

Given the target market of B2B, it needs to have a corporate & professional look and feel, but at the 
same time keep up with the market trend of being somewhere that looks like a vibrant,
exciting and interesting place. One that meeting delegates would enjoy spending a day at, and one that bookers
feel will meet the needs of those they are booking for. Also, the vast majority of use will
be via desktops, but of course the tablet and mobile layouts need to work.

Potential bookers need to be able to see everything that is included (what 
they get for their money), and need to be able to 
make a decision as to whether this is a suitable venue for their meeting on one visit
to the site. 

There needs to be an ever-present "Enquiry" opportunities on screen, and a way of completing a form to 
express interest and establish contact.

---

### **Wireframe mockups**

Made using Balsamiq

---

### **Desktop**

---

![Desktop wireframe](https://imgur.com/8UJ7ODn.png)


---

### **Tablet**

---

![Tablet wireframe](https://i.imgur.com/dgchKcD.png)

---

### **Mobile**

---

![Mobile wireframe](https://i.imgur.com/uqbALse.png)

---

## Future goals

It would be great in the future for users to be able to make actual bookings through the
site, and also to incorporate a dynamic pricing model.

For a live site taking bookings a "Chat with us" opportunity would be desired.

---
## Technology used

* HTML & CSS
* [Bootstrap](https://getbootstrap.com/) - For frameworks
* [Google Fonts](https://fonts.google.com/) - Baloo Thambi font
* [Font Awesome](https://fontawesome.com/) - Social Media & other logos
* [Gitpod](https://www.gitpod.io/) - IDE used to code
* [GitHub](https://github.com/) - To host the repositories for this project and the live website preview
* [Favicon](https://favicon.io/) - Used to generate the **m** logo
* [Shutterstock](https://www.shutterstock.com/discover/stock-assets?kw=shutterstock&utm_source=google&utm_medium=cpc&utm_campaign=UK-en-Images-Brand&gclid=CjwKCAjwssD0BRBIEiwA-JP5rKqPT3QeLULaZATah3sFDWE2KuV885Xd9SHiIO17Dr0ObKVn1hqY6xoCmG4QAvD_BwE&gclsrc=aw.ds) - Used for image sourcing
* Popper.min.js & Slim.min.js for carousel and modal functionality
* [Google Maps](https://www.google.com/maps) - Used for map link in footer
---
## Testing

* Browsers tested: Chrome, Firefox, Microsoft Edge, Internet Explorer
* Screens tested using Chrome Developer tools: Galaxy F5, 
Pixel 2 & 2 xl, IPhones 5/SE, 6/6 plus, 7/7 plus, 8, 
8 plus, X, Ipad, Ipad pro
* HTML checked with W3c HTML validator, CSS check with W3c CSS validator: Both no errors. HTML checker showing 2 warnings: One advising that
the date picker is not supported in all browser types, addressed by using a polyfill taken from Stack Overflow (warning still present though), assumed issue resolved but unable to test on these browsers as I don't have them. Second warning that the h1
header may be read by screen readers as a top level header left as acceptable.
  


---

## Key issues

* Wireframed plan had the tablet view for the overview section as being 3 columns
side by side. When this section was completed, the reality was that it looked better
with the three on top of each other, as per the mobile view. The final tablet view therefore doesn't 
match the wireframe.

* Original plans had a translucent box in the main picture but I was challenged in the positioning of
this and removed it.

---
## Deployment

To deploy this page to GitHub Pages from its [GitHub repository](https://github.com/StuartCox3107/meetings-reimagined), the following steps were taken: 

1. From the menu items near the top of the page, select **Settings**.
2. Scroll down to the **GitHub Pages** section.
3. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**
4. On selecting Master Branch the page is automatically refreshed, the website is now deployed. 
5. Scroll back down to the **GitHub Pages** section to retrieve the link to the deployed website.
 

### How to run this project locally

To clone this project from GitHub:

1. Under the repository name, click "Clone or download".
2. In the Clone with HTTPs section, copy the clone URL for the repository. 
3. In your local IDE open Git Bash.
4. Change the current working directory to the location where you want the cloned directory to be made.
5. Type ```git clone```, and then paste the URL you copied in Step 3.
```console
git clone  https://stuartcox3107.github.io/meetings-reimagined/
```
6. Press Enter. Your local clone will be created.

Further reading and troubleshooting on cloning a repository from GitHub [here](https://help.github.com/en/articles/cloning-a-repository).

---
## Credits

* Richard Wells_lead for the README.md Deployment section
* Code for image carousel control and navbar toggler taken directly from Bootstrap example code
* Modal for form sending pop-up taken from WS3 Schools
* Images: Warehouse images are owned images, all other images from Shutterstock paid account
* Code line 10 (in index.html): Polyfill taken from Stack Overflow to make sure date picker works on all browser versions
* Mentor Rohit Sharma for his advice on improving the site 