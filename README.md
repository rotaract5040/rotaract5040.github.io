# Rotaract District 5040 Site

Informational website for Rotaract District 5040.

Built using a custom Jekyll theme (loosely based off of Minima), using Bootstrap 4 for layout and interactive components. Intended to be run via GHPages (but also, if needed, to be portable to another hosting service).

The goal of the project was to get hosting costs a low as possible while still allowing club members of varying levels of tech experience to update the content. The site is low volume, but crucial for member recruitment.

## Updating Content (from Github)

There are a few ways you can edit the site content, the easiest is through the Github web UI.

### 1. Getting Access

Before you can make any updates to the district site, you'll need the proper access to the Github repository (probably where you're reading this right now).

Talk to one of the [organization members](https://github.com/orgs/rotaract5040/people) (or, someone on the district committee) and they'll be able to grant you access!

### 2. Finding Where to Make Your Update

If you're not familiar with Github or coding, this might be challenging at first.

Navigate to the [main project page](https://github.com/rotaract5040/rotaract5040.github.io), and you'll see something like this:

![Screenshot from 2020-10-18 09-53-40](https://user-images.githubusercontent.com/2569306/96375139-12687180-112c-11eb-95ba-7d44df3cda04.png)

Files and folders that hold website content are highlighted in red. Content will *always* be found in Markdown files (they end in `.md`). Don't worry about all the other file types!

To edit the content of a page, just navigate to the `.md` file that holds it's content and click on the file.

Here are some examples:

| Page | Content File |
| --- | --- |
| [About](https://rotaract5040.github.io/about/) | [about.md](https://github.com/rotaract5040/rotaract5040.github.io/blob/master/about.md)
| [Home](https://rotaract5040.github.io/) | [index.md](https://github.com/rotaract5040/rotaract5040.github.io/blob/master/index.md)
| [Burnaby Rotaract](https://rotaract5040.github.io/burnaby-rotaract/) | [_clubs/burnaby.md](https://github.com/rotaract5040/rotaract5040.github.io/blob/master/_clubs/burnaby.md)
| [PACE Trip 20XX]() | [_pace/current_year.md](https://github.com/rotaract5040/rotaract5040.github.io/blob/master/_pace/current_year.md)

### 3. Updating a Page

Once you've found the content file you want to change, you'll probably see something like this:

![Screenshot from 2020-10-18 10-07-48](https://user-images.githubusercontent.com/2569306/96375163-2f04a980-112c-11eb-9503-d8ae179aa63a.png)

Hit the 'Edit' icon (highlighted in red), to start changing the page's content. You'll see something like this:

![Screenshot from 2020-10-18 10-08-44](https://user-images.githubusercontent.com/2569306/96375194-50fe2c00-112c-11eb-939f-f886fa0ae4af.png)

Want special formatting? Headings? Quotes? Images? We use 'Markdown' to do that. Check-out other pages on the site, or this document for examples of what you can do: [Basic writing and formatting syntax](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax)

Once you're happy with your changes, you can 'save' them using the "Commit changes" box at the bottom of the page:
1. Write a short sentence describing your change (you don't *need* to do this, but it's recorded in the websites edit history, and could be useful later!)
1. Make sure the "Commit directly to the `master` branch." option is selected
1. Hit "Commit changes"

In ~5min your changes should show up on the website.

**Please check the website after every change you make!** If something breaks, not a big deal. But we can't fix it if we don't know it's broken.

## Running Locally

```bundle exec jekyll serve```
