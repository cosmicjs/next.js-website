# Next.js Website
![Cosmic React Next](https://cosmicjs.com/uploads/58dafa10-b4f2-11e6-90d2-a7e1741e7b9d-cosmic-react-next.jpg)
### [View Demo](https://cosmicjs.com/apps/nextjs-website/demo)
### Getting Started
```
git clone https://github.com/cosmicjs/next.js-website
cd next.js-website
yarn
```
#### Get your Bucket keys from Cosmic
1. Install the [app demo content in Cosmic](https://www.cosmicjs.com/apps/nextjs-website). Click Select App add and follow the steps to install.
2. Go to Bucket Settings > API Access to get your Bucket slug and read key.
#### Run in development with your Bucket keys
```
COSMIC_BUCKET=your-bucket-slug \
COSMIC_READ_KEY=your-bucket-read-key \
yarn run development
```
#### Run in production
```
COSMIC_BUCKET=your-bucket-slug \
COSMIC_READ_KEY=your-bucket-read-key \
yarn start
```
Open [http://localhost:3000](http://localhost:3000).

### Benefits
#### Next.js
[Next.js](https://github.com/zeit/next.js) is a gift to the React community.  Building React universal applications is not an easy task and the Next.js framework has greatly simplified the process.  Some immediate benefits include:

1. Less boilerplate for managing code reuse between server and client.
2. Get up and going with your development environment instantly with hot-reloading.
3. Simplified paging.

[... see more on their GitHub page](https://github.com/zeit/next.js).

#### Cosmic
Cosmic is a perfect backend to manage your Next.js React Universal application.

1. Query each page easily using the [Cosmic NPM Module](https://github.com/cosmicjs/cosmicjs-node).
2. No CMS boilerplate to configure, fast and easy setup.
3. No updates or security updates required.

[... see more on the Cosmic website](https://cosmicjs.com).
