# Online-Offline-Progressive-Web-App-Budget-Tracker
PWA that gives users a fast/easy way to track their money, both online and offline.

## Description
My PWA provides users with a resource that they can use, both online and offline, to track their expenses and desposits in their budget. My motivation for this assignment was to showcase my ability to create a PWA and store my data using MongoDB Atlas.

While my PWA doesn't solve a specific problem per se, it provides user with a budgeting resource they can use without having to depend on a stable internet connection. My project stands out because of its fast performance, clean UI, and inherent advantages over a traditional website or app.

### Table to Contents
[Installation](#installation)
[Usage](#usage)
[License](#license)
[Contributing](#contributing)
[Tests](#tests)
[Questions](#questions)

#### Installation
For my PWA, I installed the the "compression", "express", "lite-server", "mongoose", and "morgan" npm's as dependencies.

#### Usage
When a user arrives at my PWA, they are presented with fields where they can enter the name of a transaction and the amount of that transaction. Additionally, they are presented with buttons to add funds or subtract funds. Once the user has entered their transaction information and selected one of these two buttons, then their transaction data is reflected in a graph below along with an itemized record.
![Image 1](public/screenshots/image-1.png)

If the user loses their internet connection, their data is stored in the browser's cache storage. Once they regain internet connection, their data is stored in both IndexedDB.

#### License
GNU GPLv3

#### Contributing
My instructor provided my class and I with the db.js file (due to time constraints), and I relied heavily on chapters 17 and 18 in our cirriculum (especially Chapter 17 NoSQL/Activity 26, and Chapter 18 PWA/Activity 12).

#### Tests
While I didn't create any tests with node.js for this assignment, I did test out my code by debugging it in Heroku.

#### Questions.
If you have any questions for me about my PWA, please reach out to me via GitHub at HHH-603 or send me an email at hholmes726@gmail.com.
