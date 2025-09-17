# Mouths&Tongues

| Leader   | Lu Ke    | Student ID | 2019302110065 |
|---|---|---|---|
| Member   | Jiang Yu    | Student ID | 2019302110085 |
| Member   | Zeng Wanru    | Student ID | 2019302110147 |


# 1. Division of Labor

Lu Ke 2019302110065 Page Design, Login Series Page Prototypes, Personal Homepage Series Page Prototypes, Requirements Summary

Zeng Wanru 2019302110147 Recipe Book, Plaza Series Page Prototypes, Project Introduction

Jiang Yu 2019302110085 Feed Template Series Page Prototypes, Steps Page Prototypes, Usability Analysis

# 2. Project Introduction

Mouths&Tongues advocates for everyone to cook at home themselves, fostering a healthy dietary lifestyle. It provides authoritative and practical recipes along with useful dietary knowledge, and offers a platform for chefs and food enthusiasts to record and share. The primary application area of Mouths&Tongues is recipe sharing and communication. Once the product matures, it can evolve into a comprehensive platform combining community and e-commerce. The target users are mainly people who enjoy cooking but are not very skilled, and those with rich cooking experience who are eager to share. The application scenarios for Mouths&Tongues are very broad, whether at home or at a party villa, regardless of the time, be it daily life or holidays, whether wanting to cook yourself or gain satisfaction through food videos – as long as it's related to food and drink, Mouths&Tongues can provide users with the greatest help. The tasks supported by the product focus on six aspects: searching for recipes, creating recipes, viewing feeds, posting feeds, commenting on recipes, and knowledge popularization.

# 3. Requirements Summary

Our project focuses on social interaction and recipes. Therefore, our basic tasks are to ensure users can easily use our software to communicate with other users and to ensure users can understand recipes and complete the cooking process by following them. Thus, our requirements are divided into two modules: social requirements and recipe requirements.
Social Requirements:
As a social platform for food enthusiasts, our software should help users conveniently publish their own food creations and the making process. Simultaneously, we need to push other users' creative content to users so they can browse and select content they like in the plaza. The content feed page needs areas to express other users' appreciation (likes) and facilitate communication (comments) on that post. Considering users might want to save a post for repeated viewing later, we also need to incorporate a collection mechanism. Users can upload images in the comments section to facilitate smoother cooking discussions. We have also added an inbox mechanism in the page, allowing users to more easily view received likes and comments.
Recipe Requirements:
To enable users of the system to recreate dishes they browse, it is essential to have detailed and consistent recipes, making the entire food creation process easier. To achieve this, we not only provide recipe creators with a unified, clear creation template but also offer viewers a clean and aesthetically pleasing browsing interface. Addressing the issue of missing ingredients mentioned in the last presentation, when authors create their recipes, we will remind them to provide alternatives for some non-essential ingredients. Furthermore, on non-detail pages for viewers, only essential ingredients are displayed, making it easier for them to judge whether the ingredients they have on hand can satisfy the requirements for the dish they are viewing.


# 4. Webpage

## 4.1 Home Page

<img width="2322" height="1414" alt="image" src="https://github.com/user-attachments/assets/24f40319-829a-413c-b71b-5a5ac07ee5d0" />

**Overview:** The home page primarily consists of a carousel and three buttons. Scrolling down further reveals the features, advantages, and production team information of our project.
**Specific Functions:** Showcases our project to users, attracting them to use our product. Also provides a login channel for existing users.
**Usage Scenarios & Operations:** As a visitor, you can click "Browse Randomly". Clicking this will generate a random account for the user, allowing them to experience most functions of our product without logging in. However, they cannot like or comment on others' works, publish their own works, or access the personal center. New users can click the "Register" button to go to the registration page. Existing users can click the "Login" button to go to the login interface.
**How it Meets Requirements:** The "Browse Randomly" feature is designed so that users who do not want to register an account casually can enter our software without registering to experience its functions.


## 4.2 Login
<img width="2458" height="1468" alt="image" src="https://github.com/user-attachments/assets/be591c38-7cda-4335-a1b3-045b8bd7f384" />

**Overview:** The login interface mainly consists of two input fields for phone number and verification code. It also includes a "Get Verification Code" button, a "Register" button, an "Email Login" button, and a checkbox to agree to the relevant agreements.
**Specific Functions:** Used for users to log into their accounts.
**Usage Scenarios & Operations:** When a user wants to log in, they enter their phone number, click the "Get Verification Code" button, enter the received verification code in the verification code field, click the button to agree to the relevant agreements, and then click "Login".
**How it Meets Requirements:** If a user realizes they haven't registered an account, they can directly click the "Register" button to jump to the registration page.


### 4.3 Register
<img width="2350" height="1466" alt="image" src="https://github.com/user-attachments/assets/39dec684-0880-43fa-b552-708135c994cf" />

**Overview:** The registration page mainly consists of four input fields for the user to input phone number, verification code, and password (twice).

**Specific Functions:** Helps new users register an account.

**Usage Scenarios & Operations:** When a user wants to register an account, they need to enter their phone number, click the "Get Verification Code" button, then set a password and confirm it. After completing these steps, they click to agree to the relevant agreements. If the verification code is correct, they can click the "Register" button to complete registration.

**How it Meets Requirements:** If a user on the registration page finds they already have an account, they can click the "Login" button to jump to the login interface.


## 4.4 Email Login
<img width="2424" height="1478" alt="image" src="https://github.com/user-attachments/assets/281c1f98-7452-47c1-a05c-25d18d1bed27" />

**Overview:** The page mainly consists of two input fields for entering email and password.
**Specific Functions:** Login via email and password.
**Usage Scenarios & Operations:** When a user wants to log in using their email, they can enter their email and password, click to agree to the relevant agreements, and if the password is correct, click the "Login" button to access their account.
**How it Meets Requirements:** If a user forgets their password, they can click the "Forgot Password" button to retrieve it.


# 4.5 Forgot Password
<img width="2356" height="1422" alt="image" src="https://github.com/user-attachments/assets/e7fc6c29-cccb-4e4d-9711-80f22c80169b" />

**Overview:** The page mainly includes four input fields for phone number, verification code, and new password (twice).

**Specific Functions:** Helps users who forgot their password to set a new one.

**Usage Scenarios & Operations:** When a user forgets their password, they can enter their phone number, click the "Get Verification Code" button to confirm their identity, enter the verification code, and set a new password. If the verification code is correct, they can click the "Confirm" button to update the password.

**How it Meets Requirements:** Confirming the user's identity by sending a verification code to their phone offers relatively high security.


# 4.6 Food Plaza

<img width="2344" height="1448" alt="image" src="https://github.com/user-attachments/assets/38ad84ec-dca1-48f9-9dc0-1a5134dc6be6" />

**Overview:** The Food Plaza is mainly divided into two parts. The upper part of the page is a carousel featuring highly popular promoted recipes. Below the carousel are food cards. This area includes all posts from all users. The system will prioritize推送 (push/promote) content the user might like based on their browsing history.

**Usage Scenarios & Operations:** It's almost time to cook, but Xiao Shuai isn't sure what to make today. He enters the Food Plaza. The rotating popular recipe images at the top give him an idea of what others usually like to eat. Scrolling down, among the neatly arranged, clean, and aesthetically pleasing food cards, one dish catches his interest. Based on the image, main ingredients, and tools required listed on the card, he roughly estimates the difficulty of the dish. Finally, he clicks on the card to enter the detail page for this dish and decides to start making it according to the recipe.

**How it Meets Requirements:** The Food Plaza allows users to intuitively understand current popular recipes and conveniently view all food posts. Smart recommendation algorithms can enhance user interest.


# 4.7 Zone Plaza

<img width="2236" height="1370" alt="image" src="https://github.com/user-attachments/assets/8757ba06-4614-4887-aee0-3fcc9235997a" />

**Overview:** The Zone Plaza categorizes and displays a rich variety of recipes, such as Home Cooking Zone, Creative Dishes Zone, Baking & Snacks Zone, Desserts & Drinks Zone, etc.

**Usage Scenarios & Operations:** On a leisurely afternoon break, Xiao Mei craves a simple afternoon tea. She clicks into the Desserts & Drinks Zone. Scrolling up and down the page, she sees various food cards for small cakes, fruit juices, milk teas, and other desserts and drinks. Finally, she chooses one that she finds both delicious and simple to make and starts preparing it.

**How it Meets Requirements:** The Zone Plaza categorizes the rich variety of recipes, making various posts appear clearer and more organized. This helps users with strong specific intentions to quickly obtain the information they want.


# 4.8 Search
<img width="2216" height="1360" alt="image" src="https://github.com/user-attachments/assets/808c8471-6813-4bf0-9a36-d2b9d8cb4d09" />

**Overview:** The search box at the top of the page provides users with search services for recipes, users, and other content. Features like popular searches, search history, and associative search help users efficiently obtain target information.

**Usage Scenarios & Operations:** Xiao Shuai wants to make steak for Xiao Mei tonight but isn't sure what specific steak to make or how to make it. He opens the search box, enters "steak", and clicks search. The page immediately displays various steak recipes like French Red Wine Thick-Cut Slow-Cooked Steak, Black Pepper Steak with King Oyster Mushrooms, Steak and Potato Skillet...

**How it Meets Requirements:** Before searching, text in the input box guides users to search for recipes, users, etc. During search, popular searches, search history, and associative search options are displayed to help users select what they actually want to search for, improving search usability and convenience. After searching, results are displayed in a double-row layout for user viewing.


## 4.9 Recipe Feed

<img width="2282" height="1398" alt="image" src="https://github.com/user-attachments/assets/50f115c1-9347-4d0d-bcec-3d0d8729d949" />

<img width="2320" height="1422" alt="image" src="https://github.com/user-attachments/assets/5060d259-98d5-4436-bb29-83afa6ccacad" />

<img width="2360" height="1446" alt="image" src="https://github.com/user-attachments/assets/ff9b72d5-49df-469e-a767-860c7b3ae77e" />

**Overview:** The Recipe Feed page is generated based on the template filled out by the food content publisher. It includes all ingredients used for the dish and various notes. A comments section is also established below the recipe for users to discuss the dish.
**Specific Functions:** This is a display page containing the recipe's cover image, author, main ingredients, specific ingredients and their substitutes, required tools, and other related content. If the user's available ingredients and tools meet the requirements for making the dish, the user can click "Start Cooking" to proceed to the detailed steps. If the user likes the dish, they can收藏 (bookmark) and like it. Likes and bookmarks increase the dish's popularity. A comments section at the bottom allows for exchanging tips during the cooking process and recommending related dishes.
**Usage Scenarios & Operations:** Users can jump to this page from food cards on other pages to browse the specific requirements for making the dish. After reviewing the recipe, users can assess whether they meet the preparation conditions. If unsure, they can check the comments section for others' experiences making the dish. After deciding to proceed, they click "Start Cooking" to enter the detailed steps page. If the dish meets their expectations after cooking, they can like it. If they browse but don't have time to cook it immediately, they can bookmark it to find later in their collection.
**How it Meets Requirements:** For the recipe display page, our main goal is to reduce the user's browsing cost, allowing them to determine if they can make the dish by viewing minimal information. Therefore, our interface is as简洁 (concise) as possible, using醒目 (eye-catching) subheadings to guide user browsing. Substitute options increase the fault tolerance of the dish for its intended audience.


## 4.10 Steps
<img width="2386" height="1462" alt="image" src="https://github.com/user-attachments/assets/e120bac0-dd81-4fd0-b5f6-72830060212a" />
**Overview:** The detailed steps page for making a dish, primarily displaying step information and the operation interface.
**Specific Functions:** The progress bar on the left side of the recipe consists of multiple step nodes, showing the specific steps. The main body of the page is a paper-like display interface showing one specific step, including text descriptions and image displays, etc. The same step might have multiple pages; we provide options to switch between pages using keys.
**Usage Scenarios & Operations:** After clicking the "Start Cooking" button on the recipe, the user arrives at this interface. They can adjust the specific step by clicking nodes on the progress bar. Different pages within the same step can be switched using keyboard or mouse operations. If the operation difficulty seems too high, they can return via the back button in the upper right corner.
**How it Meets Requirements:** For the steps interface, we need our steps to be clear and straightforward, with diverse and accurate step-switching methods. Therefore, we adopted a progress bar plus page turner approach, using sequential nodes to display the logical step order, thus breaking down the cooking steps into nodes for user convenience.


# 4.11 Recipe Book
<img width="2196" height="1350" alt="image" src="https://github.com/user-attachments/assets/8b17b84c-6076-4789-a312-ce330fad90d7" />

**Overview:** The Recipe Book mainly consists of two parts. The upper part is a categorization option where users can subdivide and view recipes according to categories like dish type, cuisine, occasion,功效 (benefit/effect), target group, etc. Below the categorization options are food cards that meet the user's category requirements. If the user hasn't selected a category, all recipes are displayed.

**Usage Scenarios & Operations:** Tonight is Chinese New Year's Eve reunion dinner, and Xiao Mei starts preparing the feast early. She opens the Recipe Book, first clicks the "Big Fish & Meat" category tag and follows recipes to make several hearty dishes. Then, she selects "Home Cooking" to start preparing. Finally, thinking that Xiao Shuai and Grandpa will definitely have some drinks, she clicks open the "Appetizers" tag...

**How it Meets Requirements:** The Recipe Book provides practical and authoritative recipes. The categorization function divides the messy and vast recipe information into clear and orderly sections. Detailed and everyday category tags help provide users with clear ideas.


# 4.12 Personal Center
<img width="2244" height="1380" alt="image" src="https://github.com/user-attachments/assets/1e683b6f-4318-423c-a5f9-835ac73308be" />

**Overview:** The page mainly consists of the information bar on the left and the works area on the right.

**Specific Functions:** This page is primarily used to store recipe works published by the user, recipe works collected from others, and recipe works saved as drafts that have not been published.

**Usage Scenarios & Operations:** When a user wants to view a specific work they published, they can click on the "My Publications" section and quickly find the desired work based on the work title and cover image below each food card.

**How it Meets Requirements:** When a user wants to complete a previously unfinished work, they can enter the draft manuscript on this page for editing and publishing. The page can simultaneously display up to six recipe cards, facilitating quick查找 (searching/finding) of the desired recipe.



# 4.13 Inbox

<img width="2284" height="1404" alt="image" src="https://github.com/user-attachments/assets/c92466ab-e246-49bf-a181-0bd6a402ed47" />


**Overview:** The page mainly consists of the navigation bar on the left and the message display box on the right.

**Specific Functions:** Users can click on the navigation bar on the left to choose whether to view likes or comments. They can also use the "All", "Unread", and "Read" buttons above the display box on the right to filter which type of information to show.

**Usage Scenarios & Operations:** When a user wants to view unread comments about themselves, they first click "Comments" in the left navigation bar, then click "Unread" above the display box on the right. All unread comments will then be displayed in the box.

**How it Meets Requirements:** To facilitate user management of messages, we added four buttons in the upper right corner. These can be used to mark unread messages as read, delete messages, mark all list messages as read, and delete all messages.


## 4.14 Settings

<img width="2180" height="1334" alt="image" src="https://github.com/user-attachments/assets/c8518eb6-5f43-426c-b143-c04f9b567273" />
**Overview:** The page mainly consists of text input boxes, image upload boxes, and buttons.
**Specific Functions:** The Settings page is primarily used to modify the user's displayed relevant information and allows for binding an email and changing the password.
**Usage Scenarios & Operations:** When a user wants to change their avatar and nickname, they can go directly to the Settings page, enter the new nickname in the text input box after "Nickname", upload the desired avatar, click "Confirm Update", and the new avatar and nickname are set.
**How it Meets Requirements:** Considering that besides setting avatars, nicknames, and personal signatures, users might also need to change passwords, a "Reset Password" button was added to the Settings page.


## 4.15 Contact Us
<img width="2284" height="1386" alt="image" src="https://github.com/user-attachments/assets/ebc6efc3-1079-4e52-ac9d-6898b5069c15" />

**Overview:** This page is mainly composed of text boxes.
**Specific Functions:** States the relevant contact information of the production team, providing users with a channel to communicate with the production team.
**Usage Scenarios & Operations:** When users encounter related problems with the webpage and need to provide feedback to the production team, they can click "Contact Us", find the relevant contact methods on the page, and communicate with us by sending emails.
**How it Meets Requirements:** Considering that different users may have different purposes for contacting the production team, to respond faster to feedback from different users, feedback is divided into three categories, handled by three different email addresses.


## 4.16 Post Recipe Template
<img width="2278" height="1390" alt="image" src="https://github.com/user-attachments/assets/94d65f6a-8279-49e8-bcf7-409cada2b531" />
<img width="2266" height="1392" alt="image" src="https://github.com/user-attachments/assets/5b271b57-66e6-4bdd-b937-bfac2121f2a8" />

**Overview:** A template for posting recipes, used for users to create their own recipes.
**Specific Functions:** Users gradually add their own content following the template's prompts, including dish name, cover image, ingredients, and other information.
**Usage Scenarios & Operations:** The user enters this interface when clicking "Create Your Own Dish". They gradually add the dish name, upload their cover image or video introduction, list main ingredients, specific ingredients, tools, and warm tips. Afterwards, they add all steps and upload step-by-step images for each step. Finally, they click "Publish Recipe" to release it. Unfinished recipes can be saved as drafts for continued editing next time.
**How it Meets Requirements:** In our planning, the recipe creation template should be as simple as possible, allowing authors to focus on dish creation. Therefore, our template only requires users to fill in relevant information; specific layout will be uniformly arranged.

# 5. Usability Analysis

In our prototype design, we have simplified the operational流程 (process/workflow), making the entire system's usage process simple and clear. Users can understand the function of buttons through icons and text, improving learnability. Moreover, our design stems from our initial requirements analysis, so it can meet users' usage needs and operate normally in our预设 (predefined) scenarios. To address the needs of different user groups, we unified the interface, ensuring the requirements of various人群 (groups of people) can be met. Regarding error handling, we provided contact information. If users encounter unexpected errors during page use, they can contact us for resolution. Overall, this prototype design is an aesthetically pleasing design that meets our design requirements.
