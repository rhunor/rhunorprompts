# Rhunor Prompt - Next.js Full Stack App

Rhunor Prompt is a powerful full stack web application built with Next.js, designed to provide users with the ability to share and copy prompts for use in AI applications. The app integrates Google Auth for secure sign-in and sign-up processes, and utilizes MongoDB Atlas as the cloud database server to manage prompt data. Rhunor Prompt supports all CRUD (Create, Read, Update, Delete) operations, enabling users to interact with prompts seamlessly.

![Rhunor Prompt Screenshot](https://raw.githubusercontent.com/rhunor/promptipia/main/images/Screenshot%202023-08-06%20at%2010.00.01%20PM.png?token=GHSAT0AAAAAACEJ6MSHWVHCGQBWNDJ4VFJYZGQBKIA)

## Features

- **AI Prompt Sharing**: Users can easily share prompts with the AI community and copy prompts to use in their own AI applications.

- **Google Auth Integration**: Secure user authentication and registration are provided through Google Auth, ensuring users' data and prompts are protected.

- **MongoDB Atlas Database**: The app leverages MongoDB Atlas as the cloud-based database server to store and manage prompt data efficiently.

- **CRUD Operations**: Rhunor Prompt supports all CRUD operations, allowing users to create, read, update, and delete prompts with ease.

## Technologies Used

- **Next.js**: A powerful React framework for building server-rendered applications.

- **Google Auth**: Integration with Google's authentication services for user sign-in and sign-up.

- **MongoDB Atlas**: A cloud-based database service for managing prompt data.

- **Node.js**: A runtime environment for running JavaScript on the server-side.

- **Express.js**: A minimalist web application framework for Node.js to handle server-side logic.

- **CSS**: Custom styling to create an attractive and user-friendly interface.

- **Git**: Version control for collaborative development and code management.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/rhunor/rhunor-prompt.git
   ```

2. Install dependencies:
   ```
   cd rhunor-prompt
   npm install
   ```

3. Set up your MongoDB Atlas database and obtain the connection URI.

4. Create a `.env` file in the root of the project and add the following environment variables:
   ```
   MONGODB_URI=<your_mongodb_uri>
   GOOGLE_CLIENT_ID=<your_google_client_id>
   ```

5. Run the development server:
   ```
   npm run dev
   ```

6. Open your web browser and navigate to `http://localhost:3000` to access Rhunor Prompt.

## Contributing

Contributions to Rhunor Prompt are welcome! If you find any issues or have ideas for improvements, feel free to open a new issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

