# Rails 4 Application

This is a simple Rails 4 application serving as a foundation for migration to Rails 5. The application includes three main models: User, Post, and Comment.

## Features

1. **Devise Authentication:**
   - User authentication is implemented using Devise, providing secure and customizable user registration and login functionality.

2. **Bootstrap Styling:**
   - The application utilizes Bootstrap for styling. Bootstrap styles are specifically applied in the `app/views/posts/index.html.erb` view to ensure a clean and responsive user interface for the posts index.

3. **JavaScript Character Counter:**
   - A basic JavaScript functionality is implemented to provide a character counter in real-time. This feature is integrated into the Post creation and editing forms, offering users immediate feedback on the character count.

## Models

1. **User:**
   - Represents users of the application and includes authentication features provided by Devise.

2. **Post:**
   - Represents individual posts created by users. Each post may contain text content.

3. **Comment:**
   - Represents comments made on posts. Users can interact by leaving comments on existing posts.

## Usage

1. **Installation:**
   - Clone the repository to your local machine.
   - Run `bundle install` to install the required gems.
   - Set up the database using `rake db:migrate`.

2. **Run the Application:**
   - Execute `rails server` to start the server.
   - Visit `http://localhost:3000` in your web browser.

3. **Explore and Test:**
   - Navigate through the application to explore the existing features.
   - Create new users, posts, and comments.
   - Test the JavaScript character counter on post creation and editing.

## Next Steps

This Rails 4 application is designed to serve as a starting point for migration to Rails 5. As you explore and interact with the current features, consider the enhancements and updates you'll make during the migration process.

Feel free to customize and build upon this foundation to meet the evolving needs of your application.
