# Header Template using `fastn`

This repository provides a prototype to create customizable business card 
design using the `fastn` language. You can create designs which can be used 
by users to easily create professional business card by filling in their 
information.


## Getting Started

To use this template, follow the steps below:

1. Click on `Use this Template` or go to the following [link](https://github.com/new?template_name=repo_name&template_owner=fastn-community)
2. Enter the required details to create new repository (**Note**: repository name should be in kebab case).
3. Clone this newly created repository to your local machine.
4. Open the `fastn` file named `index.ftd` in a text editor.

## Creating a new Header Design

The `index.ftd` file contains placeholders that you can replace with your own information. Here's what you need to do:

### 1. Replace Package Information

In the section labeled "DOCUMENTATION FOR YOUR HEADER COMPONENTS", locate the 
`docs.home component and check the following placeholders:

**Note:** All these are auto-filled values during repository creation

- `package-name`: Your repository name
- `package-full-name`: Your GitHub repository's full URL
- `license-url`: URL to the license of your choice (e.g., MIT License) (This 
  is currently commented, you can uncomment it if you want to include license.)
- `github`: Your GitHub Repository URL
- `created-by`: The creator name (This is an optional field. You can fill this information)

### 2. Implement Header Components

In the "DEFINE YOUR HEADER COMPONENTS" section, you will find placeholders for implementing the header components of your header.

For the `header` component, you need to use the following 
headers (header details):

**Note:** These headers will be used by the users for filling in their 
information. It's mandatory to use all these headers while creating your 
component.

- `caption site-name`: Your site name (e.g., "John Doe")
- `string site-url`: Your site url
- `string site-logo`: Your site logo
  (Optional for user)


Replace the code present in the line numbers 32 to 39 with actual header 
component implementation/definition.

Also, you need to use sitemap data (section and subsection) to show it in 
header. So, go to `data.ftd` and use either `sitemap` or `full-sitemap` 
variables.

**Note:** It is **recommended** to create a `component/header.ftd`  files for
implementing components respectively.

Also, `assets` for your package is auto-imported, you can use `assets` to 
add image etc. (Checkout `FASTN.ftd` file).

## Fix the README.md content

Replace the preview image with your template image in [`.github/assets/header.png`](.github/assets/header.png)


## Publishing your category design on Github page:

Check out [Publishing Static Site On github 
pages](https://fastn.com/github-pages/) to know more. 

Also add the live site link in **About** section of github repository.


## Some other information:

The sitemap present in `FASTN.ftd` is used to organise your package. 
This uses 

- `index.ftd`: It is the homepage which shows preview of  
  your header


The documentation for this template comes from [`sitemap-header-doc`](fastn-community.github.io/sitemap-header-doc)


*To know more about `fastn`, visit [`fastn` website](https://fastn.com/). Also 
you can join our [discord](https://fastn.com/discord/) channel to connect 
with our team for further guidance.*
