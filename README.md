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

Build a simple web application called "DogTopia" that allows users to create profiles for their dogs. The application should have the following features:

## Part 1: Ruby on Rails (API's)

1. **Dog Profiles**: Users should be able to create profiles for their dogs. The profile should include fields name, breed (breed should be a dropdown use https://dog.ceo/dog-api/documentation), age, and a photo. When creating a new dog profile, use the Dog API (https://dog.ceo/dog-api/breeds-list) to fetch a random image of the selected breed as the profile picture. All external API calling must be done through backend only.

2. **Database**: Store the user and dog profile data in a PostgreSQL / MySQL / MongoDB database. You can use a free online database service like NEON (https://neon.tech/) or RAILWAY (https://railway.app/).

## Part 2: React TypeScript

Build a front-end application using React and TypeScript that consumes the API provided by the Ruby on Rails application you built in Part 1. The front-end application should have the following features:

1. **User Interface**: Create a simple user interface that allows users to interact with the "DogTopia" application.

2. **Dog Profiles**: Provide a user-friendly interface for users to create dogs' profiles, including selecting the breed and displaying a random image (should be provided by RoR app).
