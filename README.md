# Tweeter Clone

This is a simple clone of the popular social media platform Twitter. It allows users to post tweets, follow other users, and view a feed of tweets from followed users.

## Features

- User authentication (sign up, log in, log out)
- Post tweets
- Follow and unfollow users
- View a feed of tweets from followed users
- Like and comment on tweets

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/tweeter-clone.git
    cd tweeter-clone
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Set up environment variables:
    Create a `.env` file in the root directory and add the following:
    ```
    DATABASE_URL=...
    DIRECT_URL=...
    NEXTAUTH_SECRET=...
    NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=...
    ```

4. Run database migrations:
    ```bash
    npx prisma migrate dev
    ```

5. Start the development server:
    ```bash
    npm run dev
    ```

## Usage

- Visit `http://localhost:3000` in your browser to access the application.
- Sign up for a new account or log in with an existing account.
- Start posting tweets and follow other users to see their tweets in your feed.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Twitter](https://twitter.com) for the inspiration
- [Node.js](https://nodejs.org) and [Express](https://expressjs.com) for the backend framework
- [React](https://reactjs.org) for the frontend framework
- [Prisma](https://www.prisma.io) for the ORM
