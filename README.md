# Pixify

Pixify is an innovative SaaS solution designed to revolutionize image editing using the power of artificial intelligence. This platform offers a comprehensive suite of features to refine, enhance, and manipulate images effortlessly. With Pixify, you can transform ordinary images into extraordinary works of art with just a few clicks.

![thumbnail](public/assets/images/thumbnail.png)

## Table of Contents

- [Usage](#usage)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)

## Usage

Explore the functionalities of Pixify through the following steps:

1. Open Pixify in your web browser (https://pixifyai.vercel.app/)
2. Sign up or log in to your account.
3. Refine images by removing noise and imperfections using "Image Restore" feature
4. Enhance an image's dimensions using AI outpainting through "Generative Fill" feature
5. Identify and eliminate objects from images via "Object Remove" feature
6. Identify and recolor objects from the image using "Object Recolor" feature
7. Remove the background of the image using AI capabilities via "Background Remove" feature
8. View the available credits and the number of image manipulations at your profile
9. Buy additional credits if you run out of those
10. View and access the update/delete page of your recent edits in the homepage

## Technology Stack

Pixify is built using the following technologies:

1. **NextJS:** A React framework that enables server-side rendering and provides a robust development environment.
2. **TypeScript:** A statically typed superset of JavaScript, enhancing code integrity and developer productivity.
3. **MongoDB:** A NoSQL database for storing and managing application data.
4. **shadcn UI:** A comprehensive UI component library for building responsive and visually appealing user interfaces.
5. **Tailwind CSS:** A utility-first CSS framework for styling the application.
6. **Clerk:** Provides secure authentication and user management features, including basic authentication and single sign-on (SSO)
7. **Stripe:** Integrated for seamless payment processing, allowing users to purchase additional credits when needed.
8. **Cloudinary:** Powers image processing functionalities such as image restoration, object removal, object recoloring, and background removal.

## Getting Started

#### Prerequisites

- Node.js installed: https://nodejs.org/en
- MongoDB server running
- Clerk account: https://clerk.com/
- Cloudinary account and its API key and secret: https://cloudinary.com/
- Stripe account and its API key: https://stripe.com/

#### Installation

1. Clone the repository: `git clone https://github.com/aleksanderpulla/pixify.git`
2. Navigate to the project directory: `cd pixify`
3. Install dependencies: `npm install`
4. Contact aleksanderpulla@gmail.com for a template of ".env" file, containing all the referenced environment variables of the application
5. Start the application: `npm run dev` or `yarn dev` or `pnpm dev`
6. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
