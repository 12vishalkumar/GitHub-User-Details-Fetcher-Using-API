# GitHub User Details Fetcher

<p align="justify">This project fetches and displays user details from GitHub using the GitHub API. It allows you to search for a GitHub user by their username and displays information such as their avatar, name, username, date of joining, repositories, followers, following, location, Twitter handle, website, and company.</p>

## Features

- Fetches user details from GitHub using the GitHub API.
- Displays user information such as avatar, name, username, date of joining, repositories, followers, following, location, Twitter handle, website, and company.
- Allows searching for different users by their GitHub username.

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/github-user-details-fetcher.git
    ```

2. Navigate to the project directory:

    ```sh
    cd github-user-details-fetcher
    ```

3. Open the project in your preferred code editor.

## Usage

1. Open `index.html` in your web browser.
2. Enter a GitHub username in the input field and click the "Search" button.
3. The user details will be fetched and displayed on the page.

## File Structure

- #### **github-user-details-fetcher/**
- │
- ├── index.html
- ├── style.css
- └── script.js


- `index.html`: The main HTML file that contains the structure of the web page.
- `style.css`: The CSS file for styling the web page.
- `script.js`: The JavaScript file for fetching and displaying user details from GitHub.

## Customization

### HTML

Modify the `index.html` file to change the structure or content of the web page.

### CSS

Edit the `style.css` file to customize the styles, such as colors, font sizes, and layout.

### JavaScript

Update the `script.js` file to change the behavior of the user details fetching and displaying logic.

#### Key JavaScript Functions

- `getUserDetails`: Fetches user details from the GitHub API and updates the DOM with the fetched data.
- `formatDate`: Formats the date of joining in a human-readable format.
- `submitHandler`: Handles the search form submission and calls `getUserDetails` with the entered username.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Output Screen

- GitHub Account Profile
![GitHub](./Pictures/githubPrifile.png)