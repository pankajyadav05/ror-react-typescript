<div align="center">
	<a target="_blank" href="https://gitforcetalent.com">
        <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://gitforcetalent.com/_next/image?url=%2Fimages%2Flogo-light.png&w=1920&q=75">
            <source media="(prefers-color-scheme: light)" srcset="https://gitforcetalent.com/_next/image?url=%2Fimages%2Flogo.png&w=1920&q=75">
            <img alt="https://gitforcetalent.com" src="https://gitforcetalent.com/_next/image?url=%2Fimages%2Flogo.png">
        </picture>
	</a>
    <br />
    <br />
</div>

---

---

# Assignment: DogTopia using Ruby on Rails and React

## Part 1: Ruby on Rails

Build a simple web application called "DogTopia" that allows users to create and manage profiles for their dogs. The application should have the following features:

1. **Authentication**: Implement a basic user authentication system using a gem like Devise or creating a simple custom solution. Take the user's full name during signup.

2. **Dog Profiles**: Users should be able to create profiles for their dogs. The profile should include fields like name, breed (breed should be a dropdown use https://dog.ceo/dog-api/documentation), age, and a photo. When creating a new dog profile, use the Dog API (https://dog.ceo/dog-api/breeds-list) to fetch a random image of the selected breed as the profile picture. All external API calling must be done through backend only.

3. **Edit Profiles**: Users should be able to edit the profiles of their dogs, including updating the photo (using the same Dog API).

4. **View Profiles**: Users should be able to view the profiles of other dogs added by other users on the platform.

5. **Database**: Store the user and dog profile data in a PostgreSQL or MySQL database (remote only). You can use a free online database service like NEON (https://neon.tech/) or RAILWAY (https://railway.app/).

6. **Documentation**: Provide a README file explaining how to set up and run the application, including instructions for configuring the database connection.

## Part 2: React TypeScript

Build a front-end application using React and TypeScript that consumes the API provided by the Ruby on Rails application you built in Part 1. The front-end application should have the following features:

1. **User Interface**: Create a simple and responsive user interface that allows users to interact with the "DogTopia" application.

2. **Authentication**: Implement a basic user authentication flow using JSON Web Tokens (JWT) or a similar method.

3. **Dog Profiles**: Provide a user-friendly interface for users to create and edit their dogs' profiles, including selecting the breed and displaying a random image (should be provided by RoR app).

4. **View Profiles**: Display all the dog profiles created by users on the platform on homepage.

5. **Documentation**: Provide a README file explaining how to set up and run the front-end application.

## Bonus Points

- Implement a basic search functionality that allows users to search for dogs by breed or name.

## Submission:

Once you've completed the assignment, please submit your work by providing:

1. Provide the GitHub repository URL as a PRIVATE Git repository (also provide access) to pankaj@gitforcetalent.com and cc prithvi@gitforcetalent.com, arun@gitforcetalent.com.
2. Instructions on how to access and run the application.
3. Provide any additional notes or considerations regarding the implementation.

## Evaluation Criteria:

Check full details about Evaluation criteria here [marks.md](MARKS.md)
