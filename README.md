# Blog Page - ReactJS

A simple blog page built using the ReactJS framework as part of a learning project. This application allows users to create, read, update, and delete blog posts.

## Features

- **Home Page**: Displays a list of blog posts with a search bar for filtering posts.
- **Navigation Bar**: Provides easy access to Home, Create Post, and About pages.
- **New Post Page**: Allows users to add a new blog post with a title and description.
- **Edit Page**: Enables users to update existing posts.
- **Delete Functionality**: Users can delete posts they no longer need.
- **About Page**: Provides information about the blog page.
- **Missing Page**: Displays a 404 error for invalid routes.

## Project Structure

The blog page consists of the following main components:

1. **Home Page** - Displays all blog posts with a search feature.
2. **New Post Page** - Allows users to create a new blog post.
3. **Edit Page** - Enables editing of existing blog posts.
4. **About Page** - Provides details about the blog project.
5. **Missing Page** - Handles invalid routes with a 404 message.

## Installation and Setup

To run the project locally, follow these steps:

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-folder>
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start the Frontend Server

```bash
npm start
```

### 4. Start the Backend Server (JSON Server)

```bash
npx json-server -p 3500 -w data/db.json
```

## Requirements

- **Node.js** (Ensure you have Node.js installed)
- **ReactJS** (Included with project dependencies)
- **JSON Server** (Used for mock backend)

## Usage

1. Navigate to the homepage to view existing posts.
2. Use the "New Post" page to add a new blog post.
3. Click on a post to edit or delete it.
4. Use the search bar to find specific posts.

## Deploy Website

[ReactJS Blog](https://dashing-haupia-dde149.netlify.app/)
