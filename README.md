# DUXA2

This assignment transforms the wireframes into interactive websites built with HTML and CSS

# Design:

The purpose of the Couzens Bakery and Coffee Lounge website would be to allow customers to view information about them from a centralized place. Instead of relying on multiple websites such as google, TripAdvisor and Facebook, a website can provide what needs to be found. Furthermore, a dedicated website allows for the most up to date information instead of having to use third-party websites which may not have updated. This benefits both the customers and staff.

#### First Time Visitor: James:

James was a first-time visitor who wanted to be able to access the website through his phone where he could check the menu and prices before visiting the shop. The problem was he had to gather information from multiple websites which may not have includeed relevant, updated information. So having a website he can access to check the menu and the item prices would be a benefit for him.

#### Returning Visitor: Sophie:

Sophie was a returning visitor who wanted to be able to interface the application with the TAB key and be able to view special items and if items contain any allergies, as she is allergic to nuts. So, listing the allergies on the menu as well as allowing for better navigation with the TAB key would be good for her.

#### Accessibility-Dependant Regular: Margret:

Margret was a regular visitor but wanted to be able to preorder items and request special services beforehand instead of asking every time in person. Having a form or a place for contacting on the website would be beneficial for her.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/34b8672f-d84e-4226-b0a2-e01c61d2bbc6" />

_Home wireframe_

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7d2b8393-ed19-4063-929b-ba215c801f47" />

_Menu wireframe_

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0e80c69e-f6f9-45e5-bc0f-ce0c294314f9" />

_Contact Us wireframe_

# Development:

## Finished Website

<img width="1903" height="1079" alt="image" src="https://github.com/user-attachments/assets/5ffa9ae7-7b28-423e-9989-246c4287cd65" />

_Home Page_

<img width="1902" height="1079" alt="image" src="https://github.com/user-attachments/assets/af2ef4ab-0be4-41eb-ad08-b4d60cd873b8" />

_Menu Page_

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/2fd53245-72b8-4830-83a8-5e131dee7d82" />

_Contact Us Page_

Link to the page (hosted on GitHub Pages): https://mo-chowd.github.io/DUXA2

## Development Process:

The three above screenshots show the finished website. Like the wireframes, there is a home page, menu page and contact us page. The home page introduces the customer to the store, providing a title, "about us" and information on what they sell. The menu page contains the items on the menu as well as specials. The Contact Us page provides helpful information such as phone numbers and opening times. All of these pages are styled to look somewhat clean and readable.

### Tools used:

Before starting to program, I decided to use an application that would improve my coding experience. In this case, I used Visual Studio Code (VSC). With VSC, I was able to use powerful and useful features like split-screen and multiple cursors.

Instead of using regular CSS, which usually requires a separate document and can be difficult to read, I used a framework called Tailwind CSS which allows me to add CSS code directly into the HTML code. I also found Tailwind to be easy to understand. Furthermore, "Tailwind CSS is the fastest framework available. As a result, styling elements directly make it simple to develop attractive layouts" (Incentius, 2022). These reasons made me lean towards using Tailwind CSS over other frameworks.

I also used Google Chrome to test my website while developing it. Every time I save my documents and refresh the page on Chrome, I was able to see what changes occoured. Google Chrome is also extremely powerful for more complex JavaScript code, but it was also perfectly suitable for my use case.

### Key Design and Coding Decisions:

When developing the website, I initially planned to add more functionality. I was planning on implementing an ordering system on the menu which would allow the users to add items they want. I also planned on adding a functional submitting system for reporting issues. However, due to time restraints, I decided to cut down on these features. I just keeping a menu for viewing items with prices and a simple but more broad submitting form which could also be used for submitting requests but is just for show. In general, I tried to keep the design of the wireframes simplistic so it could be easily implemented into the website without facing major issues.

When programming, the use of Tailwind CSS allowed me to directly code css into my html files, which is a positive for me because I would easily be able to identify an element (HTML) and the design for it (CSS) simultaneously. I can then change and adjust the design and the element without changing between files, simplifying the development process.

### Challenges and solutions:

One issue I faced was creating a grid of boxes in both the home and menu pages. The problem was that I did not know how to adjust the boxes, so they are centred and I don’t have to manually adjust them properly. I found that using "flex" in CSS automatically adjusts the size of the boxes and even compresses when the window is smaller than the maximum size of the grid.

# Testing:

## Manual Testing:

The first user story I tested was James, who was a first-time visitor. The main thing that he wanted was a centralised place to view the menu and item prices, instead of having to rely on third-party websites. He also wanted to be able to access the website through his phone.

| James' Suggestions | Testing suggestions in website |
| :--- | :--- |
| Website accessible on phone | While box implementation was designed to work for phone, resizing the grid might require JavaScript. Still technically viewable on phone |
| Centralized menu and item prices | Implemented a full menu of items with images, prices and extra details in a grid format. Simple and easy to read |

The second user story I tested was Sophie, who was a returning visitor. She wanted to be able to navigate using the TAB key and to also see allergies that certain items may contain. She also wanted to see the specials.

| Sophies' Suggestions | Testing suggestions in website |
| :--- | :--- |
| Website can be navigated with TAB key | The only interactive part on this website is the navigation bar, form for issues/requests and social media links. But all those elements are interactable with the TAB key |
| Allergies on menu | Managed to mention the allergies that certain products may contain however it is very basic as it is only listed beneath the grid |
| Specials | While there are specials listed, this is just the general listing and not specific. However, that can be simply changed by updating the content for that box |

The third user story I tested was Margret, who was an accessibility-dependent returning-visitor. A feature she wanted was to be able to request special services before visiting the store instead of having to ask every time in person.

| Margrets' Suggestions | Testing suggestions in website |
| :--- | :--- |
| Website contains form for requests | A form was created on "Contact Us" page which can be used to report issues or request something. Contains a short, worded reason and a section for extra details |

### Issues with the website

The first issue I have ran into is the formatting on the boxes on the menu. For some reason, even though I managed to fill in the image area of the box with the relevant images, the menu for some reason puts the images over the image box instead of filling the box nicely. All information inside the boxes is still visible, but the design is not what I intended.

The second issue was the formatting on some of the areas such as the social media and phone number sections, where I was unable to get the emails and phone numbers to align correctly, resulting in a slightly odd and unorganised look. Another issue is the text mentioning the allergies beneath the grid of menu items in the menu page, where I was unable to apply a gap to separate them.

## Automated Testing:

I used Google Lighthouse to test my website:

### Home Page on desktop

<img width="951" height="864" alt="image" src="https://github.com/user-attachments/assets/e5d96b2f-9029-4247-97f6-83993597bd67" />
<img width="940" height="783" alt="image" src="https://github.com/user-attachments/assets/0c170e81-f0d2-4ea8-907f-b1ca6b840ff6" />

### Home Page on mobile

<img width="949" height="862" alt="image" src="https://github.com/user-attachments/assets/1d69b74f-9441-4ebe-bf06-69355bb9b11e" />
<img width="957" height="763" alt="image" src="https://github.com/user-attachments/assets/6a6000f8-832b-4a43-a11d-599252a45606" />

### Menu Page on desktop

<img width="945" height="862" alt="image" src="https://github.com/user-attachments/assets/7bb96041-4be9-48c5-940d-b568bc534e71" />
<img width="952" height="790" alt="image" src="https://github.com/user-attachments/assets/7d28d7fc-6d21-41eb-895f-3fbf6d9a36a0" />

### Menu Page on mobile

<img width="946" height="870" alt="image" src="https://github.com/user-attachments/assets/d11677d8-c29d-4eb6-800c-a5e5dd0777c0" />
<img width="957" height="817" alt="image" src="https://github.com/user-attachments/assets/44fc6b87-89cf-4dee-b0d1-2468541455ca" />

### Contact Us Page on desktop

<img width="948" height="870" alt="image" src="https://github.com/user-attachments/assets/a57e2c12-59e1-4f70-a7ec-5885e0f56b5c" />
<img width="959" height="624" alt="image" src="https://github.com/user-attachments/assets/e67d740c-0e97-4b43-858b-8bcaf44b3ccd" />

### Contact Us Page on mobile

<img width="946" height="864" alt="image" src="https://github.com/user-attachments/assets/fca30983-19d4-4a6f-8f20-83e559c3069f" />
<img width="959" height="732" alt="image" src="https://github.com/user-attachments/assets/78de127b-2391-4745-b89f-564a1876586e" />

### Google Lighthouse links for report

https://pagespeed.web.dev/analysis/https-mo-chowd-github-io-DUXA2-index-html/eh83hea2iy?form_factor=desktop
https://pagespeed.web.dev/analysis/https-mo-chowd-github-io-DUXA2-menu-html/1xl8c4q66d?form_factor=desktop
https://pagespeed.web.dev/analysis/https-mo-chowd-github-io-DUXA2-contact-html/hbaa1c6v38?form_factor=mobile

# References:

https://www.incentius.com/blog-posts/pros-and-cons-of-using-tailwind-css/#:~:text=When%20it%20comes%20to%20styling,from%20scratch%20when%20creating%20designs.
