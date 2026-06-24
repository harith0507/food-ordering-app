# 🍕 Food Ordering App

A modern, full-stack food ordering application built with Next.js, MongoDB, and AWS S3. Order your favorite meals with ease and get them delivered to your doorstep.

## ✨ Features

- 🛒 **Browse & Order**: Browse a wide selection of food items and place orders
- 🔐 **User Authentication**: Secure user registration and login
- 💳 **Payment Integration**: Secure payment processing
- 📦 **Order Tracking**: Track your orders in real-time
- 👨‍💼 **Admin Dashboard**: Manage menu items, orders, and inventory
- 🖼️ **Image Management**: Upload and manage food item images via AWS S3
- 📱 **Responsive Design**: Works seamlessly on mobile and desktop devices

## 🚀 Tech Stack

- **Frontend**: [Next.js](https://nextjs.org) - React framework for production
- **Database**: [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) - NoSQL database
- **Storage**: [AWS S3](https://aws.amazon.com/s3/) - Image storage and CDN
- **Styling**: CSS
- **Language**: JavaScript

## 📋 Prerequisites

Before you begin, ensure you have the following:

- Node.js (v14 or higher)
- npm, yarn, pnpm, or bun
- MongoDB Atlas account
- AWS S3 bucket
- Environment variables configured

## 🔧 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/harith0507/food-ordering-app.git
cd food-ordering-app
```

### 2. Create Environment Variables

Create a `.env.local` file in the root directory and add the following:

```env
# MongoDB
MONGODB_URI=your_mongodb_atlas_url

# AWS S3
AWS_ACCESS_KEY_ID=your_aws_access_key
AWS_SECRET_ACCESS_KEY=your_aws_secret_key
AWS_S3_BUCKET_NAME=your_bucket_name
AWS_REGION=your_aws_region

# Application
NEXTAUTH_SECRET=your_secret_key
NEXTAUTH_URL=http://localhost:3000
```

### 3. Install Dependencies

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

### 4. Run the Development Server

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## 📖 How to Use

1. **Sign Up**: Create a new account or log in
2. **Browse Menu**: Explore available food items
3. **Add to Cart**: Select items and customize your order
4. **Checkout**: Review your order and proceed to payment
5. **Track Order**: Monitor your order status in real-time

## 🏗️ Project Structure

```
food-ordering-app/
├── app/                 # Next.js app directory
├── public/              # Static assets
├── components/          # Reusable React components
├── pages/               # API routes
├── styles/              # CSS files
├── .env.local          # Environment variables (not in version control)
└── package.json        # Project dependencies
```

## 🔐 Environment Variables Setup

### MongoDB Atlas Setup
1. Create an account at [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
2. Create a new cluster
3. Add your IP address to the whitelist
4. Create a database user
5. Copy the connection string and add it to `.env.local`

### AWS S3 Setup
1. Create an AWS account at [AWS](https://aws.amazon.com)
2. Create an S3 bucket
3. Generate AWS Access Keys
4. Configure bucket permissions for public read access
5. Add credentials to `.env.local`

## 🚢 Deployment

### Deploy on Vercel

The easiest way to deploy your Next.js app is using the [Vercel Platform](https://vercel.com/):

1. Push your code to GitHub
2. Go to [Vercel](https://vercel.com/new)
3. Import your GitHub repository
4. Add your environment variables
5. Click Deploy

For detailed instructions, check the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying)

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📧 Contact & Support

For support or inquiries, please reach out to [harith0507](https://github.com/harith0507)

## 🎓 About

This project is part of a Final Year Project (FYP) to demonstrate full-stack web development capabilities.

---

**Happy Ordering! 🍔🍕🍜**
