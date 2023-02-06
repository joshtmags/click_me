# Click Me! App

## API Installation
Assuming you already have the repo in your local.
Run the following commands in your terminal.
```
composer install
php artisan key:generate
php artisan optimize:clear
php artisan migrate
php artisan serve
```

Enjoy!

## Laravel Documentation

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## NextJs Installation

This is a [Next.js](https://nextjs.org/) project, a framework of ReactJS, bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

##### First, clone the Click Me! app and create a copy of the `env.local.example` to `env.local`.

```
git clone https://github.com/joshtmags/click-me-ui.git click-me
```

##### Set your backend api endpoint for the Click Me! app.

Example:

```
NEXT_PUBLIC_CLICK_ME_API_URL=http://click-me.test:8888/api/
```

##### Install app dependencies.

```
npm install
```

##### Finally, run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) and Enjoy!

## Learn More about NextJs

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
