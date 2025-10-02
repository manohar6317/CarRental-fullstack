# Demo Repository

⚠️ **Note:**  
This repository is for **demo purposes only**.  
No actual commits or code changes are maintained here.  

The actual development work (commits, code changes, and history) is maintained in a **private repository**.



# Car Rental Fullstack Application

A fullstack car rental platform where users can browse, book, and manage cars, and owners can list and manage their vehicles.

Click Live to view website [Live](https://car-rental-tau-livid.vercel.app/)


## Features

- User authentication (register/login)
- Browse and search available cars
- Book cars for specific dates and locations
- View and manage user bookings
- Owner dashboard to list, update, and remove cars
- Owner booking management and revenue tracking
- Image upload and optimization via ImageKit
- Responsive React frontend with Tailwind CSS

## Tech Stack

- **Frontend:** React, Vite, Tailwind CSS
- **Backend:** Node.js, Express, MongoDB (Mongoose)
- **Image Hosting:** ImageKit
- **Authentication:** JWT
- **Deployment:** Vercel

## Project Structure

```
client/   # React frontend
server/   # Node.js/Express backend
```

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- MongoDB Atlas account (or local MongoDB)
- ImageKit account

### Environment Variables

#### Server (`server/.env`)

```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
```

#### Client (`client/.env`)

```
VITE_CURRENCY=$
VITE_BASE_URL=http://localhost:3000
```

### Installation

#### 1. Clone the repository

```sh
git clone https://github.com/yourusername/car-rental-fullstack.git
cd car-rental-fullstack
```

#### 2. Install dependencies

```sh
cd server
npm install

cd ../client
npm install
```

#### 3. Start the development servers

- **Backend:**

  ```sh
  cd server
  npm run server
  ```

- **Frontend:**

  ```sh
  cd client
  npm run dev
  ```

#### 4. Open in browser

Visit [http://localhost:5173](http://localhost:5173) (or the port shown in your terminal).

## Deployment

- Both client and server are configured for Vercel deployment.
- See [client/vercel.json](client/vercel.json) and [server/vercel.json](server/vercel.json) for routing and build settings.

## License

[MIT](LICENSE)

---

**Author:** Manohar Daripalli
