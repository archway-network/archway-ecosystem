# Ecosystem Page Contributor Guide

Welcome to the Archway Ecosystem repository! This guide provides detailed instructions on how to contribute to this repository. We are using a specific schema to build Ecosystem page on [archway.io](https://archway.io/ecosystem) and require contributions to follow a standard structure outlined below, we appreciate your effort to help us build out this page.

## How to Contribute

1. **Clone the Repository:**
   Clone this repository to your local machine using `git clone`.

2. **Create a New Branch:**
   Before making any changes, create a new branch with a meaningful name, e.g., `add-your-project-name`.

3. **Make Your Changes:**
   Add or edit the files according to the schema provided. Please refer to sections below for further guidelines.

4. **Commit Your Changes:**
   Make sure to write a concise and informative commit message.

5. **Push to Your Branch:**
   Push the changes to your branch on GitHub.

6. **Open a Pull Request:**
   Navigate to the GitHub page of this repository, switch to your branch, and click "New Pull Request" to open a pull request for the rest of the community to review.

## Schema

The Ecosystem page is built on a standard schema per project, any pull requests must adhere to this schema in order to render properly on the website

Example:

```json
{
  "name": "Example Project",
  "main_category": "DeFi",
  "categories": ["DeFi", "Governance & DAO Tooling"],
  "is_live": true,
  "is_featured": false,
  "is_trending": false,
  "url": "https://www.*****.com",
  "email": "*****@example.com",
  "phone": "**********",
  "location": "London",
  "summary": "This is an example one-line summary of the project",
  "logo": "example.png",
  "cover": "example_cover.png",
  "github": "https://github.com/*****",
  "twitter": "https://twitter.com/*****",
  "discord": "https://discord.com/*****",
  "telegram": "https://t.me/*****"
}
```

**Please ensure** `is_featured` and `is_trending` remain flagged as false, this is managed centrally for the time being.

## Folders Explanation

- `dapps/`: This folder contains all the JSON files for individual projects/entities in the ecosystem page.
- `dapps/assets`: This folder contains all the project images in use on the ecosystem page, this is where you can upload the logo and cover images for your project.

## File Name Requirements

- The JSON file for each project should be named using the project's name, in lower case or lower snake_case, e.g., `apollosafe.json` or `apollo_safe.json`.

## Categories

Please use one of the following predefined categories for the `"categories"` field:
- DeFi
- NFTs
- Infrastructure
- Governance & DAO Tooling
- Dashboards & Analytics
- Games
- Wallets
- Bridges
- Explorers
- Social Media
- Validators
- Relayers
- Tooling

We are open to adding new categories if there are additional groupings that emerge in the ecosystem, for now anything added in this field outside of the predefined list will be ignored.

## Image Requirements

### Logo

- File Format: PNG or JPEG
- Recommended Size: 196x196 pixels
- File Location: Save the logo image in the `dapps/assets` folder.
- File Name: The file name should match the project's name, e.g., `ApolloSafe.png`.

### Cover

- File Format: PNG or JPEG
- Recommended Size: 1200x675 pixels (16:9 aspect ratio)
- File Location: Save the cover image in the `dapps/assets` folder.
- File Name: The file name should match the project's name, e.g., `ApolloSafe_cover.png`.

We strongly recommend running all images through a compression system like [tinypng.com](https://tinypng.com/) to ensure the filesize is efficient and the page load remains performant as it grows.

**Important Note:** Please ensure that you have the rights to use the images that you are uploading and that they do not violate any copyright regulations.

<br>

Thank you for contributing to the Archway Ecosystem page! Your efforts are helping to create a valuable resource for the community.
