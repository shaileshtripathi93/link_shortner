# Link Shortener with Analytics

## Project Overview
This is a Node.js-based URL shortener similar to Bitly, with click analytics and secure user authentication. The frontend is rendered using **EJS** templates.

## Features
- **Shorten URLs**: Convert long URLs into shortened versions.
- **Click Analytics**: Track the number of clicks, referrer, and timestamps.
- **User Authentication**: Secure authentication using JWT.
- **Dashboard**: View analytics for each shortened URL, rendered using EJS.

## Technologies Used
- **Backend**:
  - Node.js: Core server-side logic.
  - Express.js: Web framework.
  - MongoDB: Database for storing URLs, click data, and user details.
  - Mongoose: ORM for MongoDB.
  - JWT: Authentication.
  - bcrypt: Password encryption.

- **Frontend**:
  - EJS (Embedded JavaScript Templates): For server-side rendering of HTML pages.

## Setup Instructions

### Prerequisites
- **Node.js** (version 14 or above)
- **npm** (Node Package Manager)
- **MongoDB** (running locally or using a cloud service like MongoDB Atlas)

### Installation

1. **Clone the Repository**
   ```bash
   git clone <https://github.com/shaileshtripathi93/link_shortner>
   cd link-shortener
