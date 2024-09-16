# greenwood-library-website

"greenwood-library-website" The website aims to be more engaging to its visitors. It currently incluses basic sections: Home, About_US, Events and Contact_US. Our team has decided to add Book_Reviews section and also update the Events secetion.

Additional description about the project and its features.

## Built With

- Major languages (HTML)

- Technologies used (Bash)

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

- A text editor(preferably Visual Studio Code)

### Install

- [Git](https://git-scm.com/downloads)
- [Node](https://nodejs.org/en/download/)

#### Clone this repository

```bash
For non-linux users, you can use:
git clone https://github.com/kelomo2502/greenwood-library-website.git

For Linux users, you can use:
git clone git@github.com:kelomo2502/greenwood-library-website.git
cd greenwood-library
```

### How to implement the project

- Create a repo on github and name it "greenwood-library-website"
  ![creating repo](./images/1.create_repo_on_github.png)
- Initialize A README.md file
  ![initializing README.md](./images/2.Initialize_README.png)
- Create home.html
  ![Create home.html ](./images/3.home.html.png)
- Create About_us.html
  ![About_us.html ](./images//4.About_us.html.png)
- Create Events.html
  ![Events.html ](./images/5.events.html.png)
- Create Contact_us.html
- ![Contact_us.html ](./images/6.contact_us.html.png)
- Add random contents to each of the fles
  ![Add contents to files ](./images/7.sample_random_contents.png)
- Add to staging area by using ```git add .``` command
  ![Add to staging area](./images/8.Adding_%20all%20_%20the_%20files_%20to_%20git_%20staging_%20area.png)
- Commit the files using ``` git commit -m "my first commit message" ```
  ![Commit the files](./images/9.Commiting%20the%20files%20to%20git.png)
- Push the files to the remote repository using ```git push origin main``` command
  ![Pushing the file to remote main branch](./images/10.Pushing_the_files_directly_to_main_branch.png)
- Create a branch for Morgan using the command ```git checkout-b add-book-reviews``` command. This command creates and switches to the created branch simultaneously
  ![Create a branch for Morgan ](./images/11.Creating_add_book_reviews_branch.png)
- Add a new file book_reciews.html using ```touch book_reviews.html``` command
  ![Add book review](./images/12.Add_book_reviews_html.png)
- Add the book_reviews files to git staging are using ```git add book_reviews.html```
  ![Add book reviews file to stagging area ](./images/13.Adding_book_reviews_html_to_stagina_area.png)
- Commit book_reviews_html to github history using ```git commit -m "Add book_reviews.html file"``` command
  ![Commit book reviews ](./images/14.Commiting_to_add_book_reviews_branch.png)
- Push from add_book_reviews to remote repo
  ![Push from add-book-reviews to remote repo](./images/15.Pushing_to_book_reviews_branch.png)
- Raise a pull request from add_book_reviews branch to the main branch
  ![Raise a pull request from add-reviews branch to main](./images/16.Raise_pull_request_for_book_reviews.png)
- Merge the pull request to the main branch
- ![merge pull request to main branch](./images/17.Merge_the_book_review_brach_to_main.png)
- Update the events.html file, however, pull the latest changes from the main branch by first checking out into main branch first using ```git checkout main``` and then run```git pull``` command
  ![Update events.html file](./images/18.Updating_the_events_html_file.png)
- Create the update-events branch and checkout into it using ```git checkout -b update-events```
  ![Create and checkout update-events branch ](./images/18.Updating_the_events_html_file.png)
- Add random contents to the events.html file
  ![Add random contents to events.html ](./images/18.Updating_the_events_html_file.png)
- Add the new update to git staging area using ```git add events.html```
  ![Add new updates to stagging area ](./images/20.git_pull_before_update.png)
  ![Commit new changes ](./images/21.Creating_the_update_events_branch.png)
- Commit the changes by running ```git commit -m "Add new events to events.html"```
  ![Commit new changes ](./images/24.Commit_changes_to_events_html.png)
- Push the commits to the update-events branch by running ```git push origin update-events```
  ![push changes to update-events branch ](./images/26.Push_into_update_events_branch.png)
- Create a pull request from the update-events branch to main branch and resolve all conflicts before merging
  ![Create pull request  ](./images/27.PR_from_update_events_branch.png)

#### Run project

```bash
 open live-server in your vscode and click on Go Live
```

## Authors

👤 **Gbenga Oyewunmi**

- GitHub:(<https://github.com/kelomo2502/greenwood-library-website.git>)
- Twitter: @kelomojs

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [Github Issues](https://github.com/kelomo2502/greenwood-library-website/issues/3)

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](https://opensource.org/licenses/MIT) licensed.
