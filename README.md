### GitHub Finder

**Project Description**:
GitHub Finder is a web-based application that allows users to search for GitHub profiles by entering a username. It fetches and displays key details about the user such as their avatar, name, public repositories, gists, followers, following, location, company, website, email, and the date the user joined GitHub.

If the user does not exist, the application will display a message saying "User Not Found."

**Features**:
- Search for a GitHub user by username.
- Display the following user information (if available):
  - Avatar
  - Name
  - Number of public repositories
  - Number of public gists
  - Number of followers
  - Number of following
  - Location
  - Company
  - Website
  - Email
  - GitHub user since date
- Error handling for users that do not exist on GitHub.

**Technologies Used**:
- **GitHub API**: For retrieving user data: https://api.github.com/users
- **JavaScript**: For handling API requests and DOM manipulation.
- **HTML**: For the basic structure of the webpage.
- **CSS**: For styling the interface (optional, depending on implementation).

**Usage**:
1. Clone or download the repository.
2. Open `index.html` in your browser.
3. Enter a GitHub username in the search box and hit enter.
4. If the user exists, their profile information will be displayed.
5. If the user does not exist, the message "User Not Found" will appear.

**Installation**:
- No special setup is required; simply clone the repo and open the HTML file in a browser.

```bash
git clone https://github.com/coderzaman/github-finder.git
```

**How It Works**:
- The app uses the GitHub API to fetch user details based on the username entered by the user.
- JavaScript is used to process the input, make the API call, and display the results in the HTML DOM.

**Example**:
Search for a user like `octocat` to see their public GitHub details.

**Future Enhancements**:
- Adding more detailed styling to enhance the user experience.
- Caching recent searches to improve performance.
- Adding pagination for repositories and followers.

---

Feel free to contribute to this project by submitting pull requests or suggesting improvements!
