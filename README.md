# NEXT JS STUDY DOCS

- [NEXT JS STUDY DOCS](#next-js-study-docs)
	- [Setup ✅](#setup-)
		- [DevFlow Project Setup ✅](#devflow-project-setup-)
		- [Eslint Prettier Setup ✅](#eslint-prettier-setup-)
			- [Install Prettier](#install-prettier)
			- [Setting things up for VSCode ✅](#setting-things-up-for-vscode-)
		- [Git-Github Setup ✅](#git-github-setup-)
		- [Tailwind CSS Setup ✅](#tailwind-css-setup-)
		- [Code Architecture ✅](#code-architecture-)
	- [Next\_js Routing  ✅](#next_js-routing--)
		- [What is Next.js Routing ✅](#what-is-nextjs-routing-)
			- [dynamic routes ✅](#dynamic-routes-)
			- [enclosed routes ✅](#enclosed-routes-)
		- [Creating Routes for DevFlow ✅](#creating-routes-for-devflow-)
	- [Next.js Architecture ✅](#nextjs-architecture-)
		- [01\_Client vs. Server Paradigm  ✅](#01_client-vs-server-paradigm--)
			- [benefits of SSR(Server Side Rendering) ✅](#benefits-of-ssrserver-side-rendering-)
		- [Different Rendering Strategies ✅](#different-rendering-strategies-)
	- [Authentication ✅](#authentication-)
		- [The Modern Auth Service ✅](#the-modern-auth-service-)
		- [Setup Auth for DevFlow ✅](#setup-auth-for-devflow-)
	- [Layouts ✅](#layouts-)
		- [Creating Layouts using Next-Font and Metadata in DevFlow ✅](#creating-layouts-using-next-font-and-metadata-in-devflow-)
	- [Theme 🔲](#theme-)
		- [Creating a Global Theme Context for DevFlow 🔲](#creating-a-global-theme-context-for-devflow-)
	- [Navbar 🔲](#navbar-)
		- [Container and User Account ✅](#container-and-user-account-)
		- [Shadcn Installation](#shadcn-installation)
		- [Theme Switcher and Mobile Navigation](#theme-switcher-and-mobile-navigation)
		- [theme switcher ✅](#theme-switcher-)
		- [MobileNavigation](#mobilenavigation)
	- [Sidebar 🔲](#sidebar-)
		- [11\_Sidebar 🔲](#11_sidebar-)
	- [Home Page 🔲](#home-page-)
		- [01\_Home Route 🔲](#01_home-route-)
		- [02\_Active Lesson 3 — Create a LocalSearchbar 🔲](#02_active-lesson-3--create-a-localsearchbar-)
		- [03\_LocalSearchbar Component 🔲](#03_localsearchbar-component-)
		- [04\_Active Lesson 4 — Create a Filter 🔲](#04_active-lesson-4--create-a-filter-)
		- [05\_Home Filters 🔲](#05_home-filters-)
		- [07\_Create Question Card 🔲](#07_create-question-card-)
	- [Ask a Question Page 🔲](#ask-a-question-page-)
		- [](#)
		- [](#-1)
		- [](#-2)
		- [](#-3)
		- [](#-4)
		- [](#-5)
	- [Develop Backend](#develop-backend)
	- [Create a Question](#create-a-question)
	- [Fetching Questions on the Home Page](#fetching-questions-on-the-home-page)
	- [The Webhooks](#the-webhooks)
	- [Community Page](#community-page)
	- [Tags Page](#tags-page)
	- [Question Details](#question-details)
	- [Voting](#voting)
	- [Collections Page](#collections-page)
	- [Views](#views)
	- [Tag Details Page](#tag-details-page)
	- [Profile Page](#profile-page)
	- [Edit\_Delete User Actions](#edit_delete-user-actions)
	- [Show Top Results](#show-top-results)
	- [The Local Search Functionality](#the-local-search-functionality)
	- [The Filters](#the-filters)
	- [The Pagination](#the-pagination)
	- [Global Search](#global-search)
	- [Reputation](#reputation)
	- [Badge System](#badge-system)
	- [Generate AI Answer](#generate-ai-answer)
	- [Loadings \_ Toasts](#loadings-_-toasts)
	- [Meta Data](#meta-data)
	- [Bug Fixing and Recommendation](#bug-fixing-and-recommendation)
	- [Next.js 13.5+](#nextjs-135)
	- [Deployment](#deployment)
		- [](#-6)
		- [](#-7)
		- [](#-8)
		- [](#-9)
		- [](#-10)
		- [](#-11)
		- [](#-12)


## Setup ✅

### DevFlow Project Setup ✅

next js installation page https://nextjs.org/docs/getting-started/installation

let's create a new project with the following command:

```bash
npx create-next-app@latest
```

![Alt text](image.png)

our app default folder structure

![Alt text](image-1.png)

let's run the app

```bash
npm run dev
```

### Eslint Prettier Setup ✅

![Alt text](image-2.png)


let's install eslint standard

```bash
npm install eslint-config-standard
```
![![Alt text](image-4.png)](image-3.png)

let's update the eslint config file

```json
{
	"extends": ["next/core-web-vitals", "standard"]
}

```
![Alt text](image-5.png)

let's run the lint

```bash
npm run lint
```
result

![Alt text](image-6.png)

Adding an ESLint Configuration for TailwindCSS

let's install eslint plugin tailwind

```bash
npm install eslint-plugin-tailwindcss
```

Having our class names organized logically in Tailwind makes the code easier to read and review. We can install another ESLint config that takes care of that to do this automatically.

Prettier VS ESLint potential conflicts

ESLint sometimes likes to enter into conflict with Prettier. 🥊

To avoid these situations, you should run:

```bash
npm install eslint-config-prettier
```
#### Install Prettier

Don’t forget to install prettier before proceeding; otherwise, things will not work, and you won’t know why. 🤷

```bash
npm install prettier
```
#### Setting things up for VSCode ✅

Now that everything is set up command-line-wise, it’s time to integrate ESLint and Prettier with VSCode. For that, we will need to modify the `**settings.json**` file or create a config specific to our project that you can share with others if you’d like. We’ll go with the latter.

In your Next.js project at the root, create a `**.vscode`** folder and within it a `**settings.json**` file with the following code:

```json
{
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.addMissingImports": true
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}
```

final result
```json
{
	"extends": [
		"next/core-web-vitals",
		"standard",
		"plugin:tailwindcss/recommended",
		"prettier"
	]
}

```
### Git-Github Setup ✅
create a new repo on github


### Tailwind CSS Setup ✅
style guide for the app
colors
![Alt text](image-7.png)
typography
![Alt text](image-8.png)

let's add the design system to our application
```ts
import type { Config } from 'tailwindcss';

const config: Config = {
	content: [
		'./pages/**/*.{js,ts,jsx,tsx,mdx}',
		'./components/**/*.{js,ts,jsx,tsx,mdx}',
		'./app/**/*.{js,ts,jsx,tsx,mdx}'
	],
	theme: {
		extend: {
			colors: {
				primary: {
					500: '#FF7000',
					100: '#FFF1E6'
				},
				dark: {
					100: '#00000',
					200: '#0F1117',
					300: '#151821',
					400: '#212734',
					500: '#3F4354'
				},
				light: {
					900: '#FFFFFF',
					800: '#F4F6F8',
					850: '#FDFDFD',
					700: '#DCE3F1',
					500: '#7B8EC8',
					400: '#858EAD'
				},
				'accent-blue': '#1DA1F2'
			},
			fontFamily: {
				inter: ['var(--font-inter)'],
				spaceGrotesk: ['var(--font-spaceGrotesk)']
			},
			boxShadow: {
				'light-100':
					'0px 12px 20px 0px rgba(184, 184, 184, 0.03), 0px 6px 12px 0px',
				'light-200': '10px 10px 20px 0px rgba(218, 213, 213, 0.10)',
				'light-300': '-10px 10px 20px 0px rgba(218, 213, 213, 0.10)',
				'dark-100': '0px 2px 10px 0px rgba(46, 52, 56, 0.10)',
				'dark-200': '2px 0px 20px 0px rgba(39, 36, 36, 0.04)'
			},
			backgroundImage: {
				'auth-dark': "url('/assets/images/auth-dark.png')",
				'auth-light': "url('/assets/images/auth-light.png')"
			},
			screens: {
				xs: '420px'
			},
			keyframes: {
				'accordion-down': {
					from: { height: '0' },
					to: { height: 'var(--radix-accordion-content-height)' }
				},
				'accordion-up': {
					from: { height: 'var(--radix-accordion-content-height)' },
					to: { height: '0' }
				}
			},
			animation: {
				'accordion-down': 'accordion-down 0.2s ease-out',
				'accordion-up': 'accordion-up 0.2s ease-out'
			}
		}
	},
	plugins: [require('tailwindcss-animate'), require('@tailwindcss/typography')]
};
export default config;

```

and create a folder called styles and file inside a theme.css

```css
@tailwind base;
@tailwind components;
@tailwind utilities;

@layer utilities {
	.background-light850_dark100 {
		@apply bg-light-850 dark:bg-dark-100;
	}
	.background-light900_dark200 {
		@apply bg-light-900 dark:bg-dark-200;
	}
	.background-light900_dark300 {
		@apply bg-light-900 dark:bg-dark-300;
	}
	.background-light800_darkgradient {
		@apply bg-light-800 dark:dark-gradient;
	}
	.background-light800_dark400 {
		@apply bg-light-800 dark:bg-dark-400 !important;
	}
	.background-light700_dark400 {
		@apply bg-light-700 dark:bg-dark-400;
	}
	.background-light700_dark300 {
		@apply bg-light-700 dark:bg-dark-300;
	}
	.background-light800_dark400 {
		@apply bg-light-800 dark:bg-dark-400;
	}
	.background-light800_dark300 {
		@apply bg-light-800 dark:bg-dark-300 !important;
	}
	.text-dark100_light900 {
		@apply text-dark-100 dark:text-light-900 !important;
	}
	.text-dark200_light900 {
		@apply text-dark-200 dark:text-light-900;
	}
	.text-dark200_light800 {
		@apply text-dark-200 dark:text-light-800 !important;
	}
	.text-dark300_light700 {
		@apply text-dark-300 dark:text-light-700;
	}
	.text-dark400_light700 {
		@apply text-dark-400 dark:text-light-700;
	}
	.text-dark500_light700 {
		@apply text-dark-500 dark:text-light-700 !important;
	}
	.text-dark500_light500 {
		@apply text-dark-500 dark:text-light-500;
	}
	.text-dark300_light900 {
		@apply text-dark-300 dark:text-light-900 !important;
	}
	.text-dark400_light800 {
		@apply text-dark-400 dark:text-light-800;
	}
	.text-light400_light500 {
		@apply text-light-400 dark:text-light-500 !important;
	}
	.text-dark400_light500 {
		@apply text-dark-400 dark:text-light-500;
	}
	.text-dark400_light900 {
		@apply text-dark-400 dark:text-light-900 !important;
	}
	.text-light400_light500 {
		@apply text-light-400 dark:text-light-500 !important;
	}
	.light-border {
		@apply border-light-800 dark:border-dark-300;
	}
	.light-border-2 {
		@apply border-light-700 dark:border-dark-400 !important;
	}
	.h1-bold {
		@apply text-[30px] font-bold leading-[42px] tracking-tighter;
	}
	.h2-bold {
		@apply text-[24px] font-bold leading-[31.2px];
	}
	.h2-semibold {
		@apply text-[24px] font-semibold leading-[31.2px];
	}
	.h3-bold {
		@apply text-[20px] font-bold leading-[26px];
	}
	.h3-semibold {
		@apply text-[20px] font-semibold leading-[24.8px];
	}
	.base-medium {
		@apply text-[18px] font-medium leading-[25.2px];
	}
	.base-semibold {
		@apply text-[18px] font-semibold leading-[25.2px];
	}
	.base-bold {
		@apply text-[18px] font-bold leading-[140%];
	}
	.paragraph-regular {
		@apply text-[16px] font-normal leading-[22.4px];
	}
	.paragraph-medium {
		@apply text-[16px] font-medium leading-[22.4px];
	}
	.paragraph-semibold {
		@apply text-[16px] font-semibold leading-[20.8px];
	}
	.body-regular {
		@apply text-[14px] font-normal leading-[19.6px];
	}
	.body-medium {
		@apply text-[14px] font-medium leading-[18.2px];
	}
	.body-semibold {
		@apply text-[14px] font-semibold leading-[18.2px];
	}
	.small-regular {
		@apply text-[12px] font-normal leading-[15.6px];
	}
	.small-medium {
		@apply text-[12px] font-medium leading-[15.6px];
	}
	.small-semibold {
		@apply text-[12px] font-semibold leading-[15.6px];
	}
	.subtle-medium {
		@apply text-[10px] font-medium leading-[13px] !important;
	}
	.subtle-regular {
		@apply text-[10px] font-normal leading-[13px];
	}
	.placeholder {
		@apply placeholder:text-light-400 dark:placeholder:text-light-;
	}
	.invert-colors {
		@apply invert dark:invert-0;
	}
	.shadow-light100_dark100 {
		@apply shadow-light-100 dark:shadow-dark-100;
	}
	.shadow-light100_darknone {
		@apply shadow-light-100 dark:shadow-none;
	}
	.primary-gradient {
		background: linear-gradient(129deg, #ff7000 0%, #e2995f 100%);
	}
	.dark-gradient {
		background: linear-gradient(
			232deg,
			rgba(23, 28, 35, 0.41) 0%,
			rgba(19, 22, 28, 0.7) 100%
		);
	}
}
```
and change the globals.css
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
@import url('../styles/theme.css');
body {
	font-family: 'Inter', sans-serif;
}
@layer utilities {
	.flex-center {
		@apply flex justify-center items-center;
	}
	.flex-between {
		@apply flex justify-between items-center;
	}
	.flex-start {
		@apply flex justify-start items-center;
	}
	.card-wrapper {
		@apply bg-light-900 dark:dark-gradient shadow-light-100 dar;
	}
	.btn {
		@apply bg-light-800 dark:bg-dark-300 !important;
	}
	.btn-secondary {
		@apply bg-light-800 dark:bg-dark-400 !important;
	}
	.btn-tertiary {
		@apply bg-light-700 dark:bg-dark-300 !important;
	}
	.markdown {
		@apply max-w-full prose dark:prose-p:text-light-700 dark:pros;
	}
	.primary-gradient {
		background: linear-gradient(129deg, #ff7000 0%, #e2995f 100%);
	}
	.dark-gradient {
		background: linear-gradient(
			232deg,
			rgba(23, 28, 35, 0.41) 0%,
			rgba(19, 22, 28, 0.7) 100%
		);
	}
	.tab {
		@apply min-h-full dark:bg-dark-400 bg-light-800 text-light-5;
	}
	.no-focus {
		@apply focus-visible:ring-0 focus-visible:ring-transparent focus;
	}
}

.active-theme {
	filter: invert(53%) sepia(98%) saturate(3332%) hue-rotate(0deg)
		brightness(104%) contrast(106%) !important;
}
.light-gradient {
	background: linear-gradient(
		132deg,
		rgba(247, 249, 255, 0.5) 0%,
		rgba(229, 237, 255, 0.25) 100%
	);
}
.primary-text-gradient {
	background: linear-gradient(129deg, #ff7000 0%, #e2995f 100%);
	background-clip: text;
	-webkit-background-clip: text;
	-webkit-text-fill-color: transparent;
}
.custom-scrollbar::-webkit-scrollbar {
	width: 3px;
	height: 3px;
	border-radius: 2px;
}
.custom-scrollbar::-webkit-scrollbar-track {
	background: #ffffff;
}
.custom-scrollbar::-webkit-scrollbar-thumb {
	background: #888;
	border-radius: 50px;
}
.custom-scrollbar::-webkit-scrollbar-thumb:hover {
	background: #555;
}
/* Markdown Start */
.markdown a {
	color: #1da1f2;
}
.markdown a,
code {
	/* These are technically the same, but use both */
	overflow-wrap: break-word;
	word-wrap: break-word;
	-ms-word-break: break-all;
	/* This is the dangerous one in WebKit, as it breaks things whereve
word-break: break-all;
/* Instead use this non-standard one: */
	word-break: break-word;
	/* Adds a hyphen where the word breaks, if supported (No Blink) */
	-ms-hyphens: auto;
	-moz-hyphens: auto;
	-webkit-hyphens: auto;
	hyphens: auto;
	padding: 2px;
	color: #ff7000 !important;
}
.markdown pre {
	display: grid;
	width: 100%;
}
.markdown pre code {
	width: 100%;
	display: block;
	overflow-x: auto;
	color: inherit !important;
}
/* Markdown End */

/* Clerk */
.cl-internal-b3fm6y {
	background: linear-gradient(129deg, #ff7000 0%, #e2995f 100%);
}
.hash-span {
	margin-top: -140px;
	padding-bottom: 140px;
	display: block;
}
/* Hide scrollbar for Chrome, Safari and Opera */
.no-scrollbar::-webkit-scrollbar {
	display: none;
}
/* Hide scrollbar for IE, Edge and Firefox */
.no-scrollbar {
	-ms-overflow-style: none; /* IE and Edge */
	scrollbar-width: none; /* Firefox */
}

```


and install the following packages

![Alt text](image-9.png)

bash command
```bash
npm i -D tailwindcss-animate @tailwindcss/typography
```

cleanup the main page

```tsx
export default function Home() {
	return (
		<main>
			<h1 className="h1-bold ">NEXT JS !# here we come</h1>
		</main>
	);
}

```

output 

![Alt text](image-10.png)


### Code Architecture ✅


![Alt text](image-11.png)

## Next_js Routing  ✅
### What is Next.js Routing ✅
![Alt text](image-12.png)
![Alt text](image-13.png)
![Alt text](image-14.png)
![Alt text](image-15.png)
let's build a simple app with next js

![Alt text](image-16.png)
let's build a simple navbar component

![Alt text](image-17.png)

and call it inside the layout

![Alt text](image-18.png)

let's create the about page

![Alt text](image-19.png)

let's create the contact page

![Alt text](image-20.png)

nested route

![Alt text](image-21.png)

add this to app page

![Alt text](image-22.png)

![Alt text](image-23.png)

#### dynamic routes ✅
 
![Alt text](image-24.png)

![Alt text](image-25.png)

![Alt text](image-26.png)

#### enclosed routes ✅

![Alt text](image-27.png)

![Alt text](image-28.png)

question 

![Alt text](image-29.png) 

![Alt text](image-30.png)

![Alt text](image-31.png)

![Alt text](image-32.png)


### Creating Routes for DevFlow ✅

let's create the routes for our app

![Alt text](image-34.png)

in the (auth) folder let's create a layout component

```tsx
import { FC, ReactNode } from 'react';

type TLayoutProps = {
	children: ReactNode;
};
const Layout: FC<TLayoutProps> = ({ children }) => {
	return (
		<main className="flex min-h-screen w-full items-center justify-center">
			{children}
		</main>
	);
};

export default Layout;

```
and delete the root `page.tsx` from root

this is the default root now

![Alt text](image-35.png)

```tsx
const Home = () => {
	return <div>Home</div>;
};

export default Home;

```
## Next.js Architecture ✅
### 01_Client vs. Server Paradigm  ✅
![Alt text](image-36.png)

![Alt text](image-37.png)

both of them are react components

but the difference is where they are rendered
client side components are rendered on the client
![Alt text](image-38.png)
client
![Alt text](image-39.png)

server side components are rendered on the server
![Alt text](image-40.png)

by rendering on the server we can get the following benefits

rendering on the server is faster
reduce the initial load time
better SEO
reduce the initial bundle size

![Alt text](image-41.png)

![Alt text](image-42.png)

![Alt text](image-43.png)

#### benefits of SSR(Server Side Rendering) ✅

![Alt text](image-44.png)
because we are returning the html from the server

![Alt text](image-45.png)

because we are sending html instead of js like in react SEO is better

![Alt text](image-46.png)

![Alt text](image-47.png)

when to decide to use SSR
- when you need better SEO
- when you need better performance
- when you need better initial load time
- when you need better initial bundle size
- when you need better user experience
- when you need better accessibility
- when you need better security 
  
![Alt text](image-48.png)

![Alt text](image-49.png)

![Alt text](image-50.png)

if a component need user data we can't render it on the server

![Alt text](image-51.png)

examples

![Alt text](image-52.png)

we use 

![Alt text](image-53.png)

![Alt text](image-54.png)

![Alt text](image-55.png)

![Alt text](image-56.png)

![Alt text](image-57.png)

![Alt text](image-58.png)

app router consider all components as server side components

![Alt text](image-59.png)
![Alt text](image-60.png)

to define a component as client side component we use

![Alt text](image-61.png)


example code 

![Alt text](image-64.png)

ExampleServer.tsx
```tsx
const ExampleServer = () => {
    console.log("I am a server side component")
    return (
        <div>
        <h1>Example Server</h1>
        </div>
    );
}

export default ExampleServer;
```

ExampleClient.tsx
```tsx

"use client";
const ExampleClient = () => {
    console.log("I am a clinet side component")
    return (
        <div>
        <h1>Example Client</h1>
        </div>
    )
}

export default ExampleClient;
```
on the server

![Alt text](image-65.png)

on the client

![Alt text](image-66.png)

why are we seeing the client side component on the server



![Alt text](image-62.png)

![Alt text](image-63.png)

also nextjs pre-render the page on the server to make it faster

![Alt text](image-67.png)
default 

![Alt text](image-68.png)

next will try to rerender components on the server

![Alt text](image-69.png)

![Alt text](image-70.png)

do not include server components inside the client components
- it will become a client component


quiz 
add the use client to the app component

![Alt text](image-74.png)

![Alt text](image-71.png)

![Alt text](image-72.png)

![Alt text](image-73.png)

### Different Rendering Strategies ✅

![Alt text](image-75.png)

![Alt text](image-76.png)

![Alt text](image-77.png) 

we can render our code on two environments

- server
- client

![Alt text](image-78.png)

![Alt text](image-79.png)

![Alt text](image-80.png)

![Alt text](image-81.png)

build time

![Alt text](image-82.png)

run time

![Alt text](image-83.png)

![Alt text](image-84.png)

![Alt text](image-85.png)

![Alt text](image-86.png)

![Alt text](image-87.png)

![Alt text](image-88.png)

![Alt text](image-89.png)

![Alt text](image-90.png)

![Alt text](image-91.png)

![Alt text](image-92.png)

![Alt text](image-93.png)

![Alt text](image-94.png)

quiz
![Alt text](image-95.png)
![Alt text](image-96.png)
![Alt text](image-97.png)
![Alt text](image-98.png)
![Alt text](image-99.png)
![Alt text](image-100.png)

## Authentication ✅

### The Modern Auth Service ✅
we will use clerk.dev for authentication https://clerk.com/
![Alt text](image-103.png)
### Setup Auth for DevFlow ✅
we will use clerk.dev for authentication
![Alt text](image-101.png)
![Alt text](image-102.png)

copy the keys to the `env.local` file

now go to https://clerk.com/docs/quickstarts/nextjs

let's install clerk

```bash
npm install @clerk/nextjs
```
![Alt text](image-104.png)

![Alt text](image-105.png)

let's create a middleware file in the root folder
and make the home page public
```ts
import { authMiddleware } from '@clerk/nextjs';

// This example protects all routes including api/trpc routes
// Please edit this to allow other routes to be public as needed.
// See https://clerk.com/docs/references/nextjs/auth-middleware for more information about configuring your Middleware
export default authMiddleware({
	publicRoutes: ['/']
});

export const config = {
	matcher: ['/((?!.+\\.[\\w]+$|_next).*)', '/', '/(api|trpc)(.*)']
};
```

and update the layout page

```tsx
import { ClerkProvider } from '@clerk/nextjs';
import { ReactNode } from 'react';

export const metadata = {
	title: 'Next.js 13 with Clerk'
};

export default function RootLayout({ children }: { children: ReactNode }) {
	return (
		<ClerkProvider>
			<html lang="en">
				<body>{children}</body>
			</html>
		</ClerkProvider>
	);
}
```

follow the steps in the docs and create sign-in and sign-up pages

![Alt text](image-106.png)

pages/sign-in.tsx
```tsx
import { SignIn } from '@clerk/nextjs';

export default function Page() {
	return <SignIn />;
}
```

pages/sign-up.tsx
```tsx
import { SignUp } from '@clerk/nextjs';

export default function Page() {
	return <SignUp />;
}

```

## Layouts ✅
### Creating Layouts using Next-Font and Metadata in DevFlow ✅

let's add the public folder to the app

![Alt text](image-107.png)

![Alt text](image-108.png)

change the layout page

```tsx
import { ClerkProvider } from '@clerk/nextjs';
import { ReactNode } from 'react';
import './globals.css';
// eslint-disable-next-line camelcase
import {Inter,Space_Grotesk} from 'next/font/google';

import type {Metadata} from "next";
const inter = Inter({
	subsets: ['latin'],
	weight:['100','200','300','400','500','600','700','800','900'],
	variable:'--font-inter',
});
const spaceGrotesk = Space_Grotesk({
	subsets: ['latin'],
	weight:['300','400','500','600','700'],
	variable:'--font-spaceGrotesk',
});


export const metadata:Metadata = {
	title: 'StackFlow',
	description:'StackFlow is a Q&A site for professional and enthusiast programmers. ' +
		'It is built and run by you as part of the Stack Exchange network of Q&A sites. ' +
		'With your help, we are working together to build a library of detailed answers to every question about programming.',
	icons:{
		icon: '/assets/images/site-logo.svg',
	}
};

export default function RootLayout({ children }: { children: ReactNode }) {
	return (
		<ClerkProvider appearance={{
			elements:{
				formButtonPrimary:'primary-gradient',
				footerActionLink:'primary-text-gradient hover:text-primary-500',
			}

		}}>
			<html lang="en">
				<body className={`${inter.variable} ${spaceGrotesk.variable}`}>
			 <h1 className="h1-bold">this is a  piece of text</h1>

				{children}
				</body>
			</html>
		</ClerkProvider>
	);
}
```

will customize the clerk appearance

![Alt text](image-109.png)


## Theme 🔲
### Creating a Global Theme Context for DevFlow 🔲

Using React Context for State Management with Next.js https://vercel.com/guides/react-context-state-management-nextjs

let's create a context/ThemeProvider.tsx

```tsx
"use client";

import {
  useContext,
  createContext,
  useState,
  ReactNode,
  FC,
  useEffect,
} from "react";

type TTheme = "dark" | "light" | undefined;

type TThemeContext = {
  theme: "dark" | "light" | undefined;
  setTheme: (theme: TTheme) => void;
};

const ThemeContext = createContext<TThemeContext | undefined>(undefined);

type TThemeProvider = {
  children: ReactNode;
};
export const ThemeProvider: FC<TThemeProvider> = ({ children }) => {
  const [theme, setTheme] = useState<"dark" | "light" | undefined>(undefined);

  const handleThemeChange = (theme: TTheme) => {
    if (theme === "dark") {
      setTheme("light");
      document.documentElement.classList.add("dark");
    } else {
      setTheme("dark");
      document.documentElement.classList.add("light");
    }
  };

  useEffect(() => {
    handleThemeChange(theme);
  }, [theme]);

  return (
    <ThemeContext.Provider
      value={{
        theme,
        setTheme,
      }}
    >
      {children}
    </ThemeContext.Provider>
  );
};

export const useTheme = () => {
  const context = useContext(ThemeContext);
  if (context === undefined) {
    throw new Error("useTheme must be used within a ThemeProvider");
  }
  return context;
};
```

let's add the theme provider to the layout

```tsx
export default function RootLayout({ children }: { children: ReactNode }) {
  return (
    <html lang="en">
      <body className={`${inter.variable} ${spaceGrotesk.variable}`}>
        <ClerkProvider
          appearance={{
            elements: {
              formButtonPrimary: "primary-gradient",
              footerActionLink: "primary-text-gradient hover:text-primary-500",
            },
          }}
        >
          <ThemeProvider>{children}</ThemeProvider>
        </ClerkProvider>
      </body>
    </html>
  );
}
```
## Navbar 🔲

### Container and User Account ✅
let's create a NavBar component

```tsx
import { FC } from "react";
import Link from "next/link";
import Image from "next/image";
import { SignedIn, UserButton } from "@clerk/nextjs";

type TNavBar = {};
const NavBar: FC<TNavBar> = () => {
  return (
    <nav
      className={
        "flex-between background-light900_dark200 fixed z-50 flex w-full gap-5  p-6 shadow-light-300 dark:shadow-none sm:px-12"
      }
    >
      <Link href={"/"} className={"flex items-center gap-1"}>
        <Image
          src={"/assets/images/site-logo.svg"}
          width={23}
          height={23}
          alt={"StackFlow"}
        />
        <p
          className={
            "h2-bold min-sm:hidden font-spaceGrotesk text-dark-100 dark:text-light-900"
          }
        >
          Stack <span className={"text-primary-500"}>Flow</span>
        </p>
      </Link>
      {/*  GLOBAL SEARCH COMPONENT */}
      <div className={"flex-between gap-5"}>
        Theme
        <SignedIn>
          <UserButton
            appearance={{
              elements: {
                avatarBox: "h-10 w-10",
              },
              variables: {
                colorPrimary: "#ff7000",
              },
            }}
            afterSignOutUrl="/"
          />
        </SignedIn>
        Mobile Navigation
      </div>
    </nav>
  );
};

export default NavBar;
```

let's remove the user button from the some page

```tsx
export default function Home() {
  return <div></div>;
}
```

create a  root layout 
```tsx
import { FC, ReactNode } from "react";
import NavBar from "@/components/shared/navbar/NavBar";

type TLayout = {
  children: ReactNode;
};

const Layout: FC<TLayout> = ({ children }) => {
  return (
    <main className={"background-light850_dark100 relative"}>
      <NavBar />
      <div className="flex">
        LEFT SIDE BAR
        <section
          className={
            "flex min-h-screen flex-1 flex-col px-6 pb-6 pt-36 max-md:pb-14 sm:px-14"
          }
        >
          <div className={"mx-auto w-full max-w-5xl"}>{children}</div>
        </section>
        Right Side Bar
      </div>
      Toaster
    </main>
  );
};

export default Layout;

```
![Alt text](image-110.png)

### Shadcn Installation

shadcn https://ui.shadcn.com/

![Alt text](image-111.png)

go to documentation

https://ui.shadcn.com/docs/installation/next

select next js and run the install command

```bash
npx shadcn-ui@latest init
```
answer the questions

![Alt text](image-113.png)

it will create a tailwind conifg js file and overrride the globals.css file 
delete the tailwind config file and undo the globals.css file

it will create a `lib/utils.ts` file
```ts
import { type ClassValue, clsx } from "clsx"
import { twMerge } from "tailwind-merge"
 
export function cn(...inputs: ClassValue[]) {
  return twMerge(clsx(inputs))
}

```

components.json file

```json
{
  "$schema": "https://ui.shadcn.com/schema.json",
  "style": "default",
  "rsc": true,
  "tsx": true,
  "tailwind": {
    "config": "tailwind.config.js",
    "css": "app/globals.css",
    "baseColor": "slate",
    "cssVariables": true
  },
  "aliases": {
    "components": "@/components",
    "utils": "@/lib/utils"
  }
}
```
### Theme Switcher and Mobile Navigation

let's add the button to the project

```bash
npx shadcn-ui@latest add button
```

let's add a menu bar to 

```bash
npx shadcn-ui@latest add menubar
```

### theme switcher ✅

let's create a constants component for storing constants

```tsx
import { SidebarLink } from "@/types/types";

export const THEMES = [
  {
    value: "light",
    label: "Light",
    icon: "/assets/icons/sun.svg",
  },
  {
    value: "dark",
    label: "Dark",
    icon: "/assets/icons/moon.svg",
  },
  {
    value: "system",
    label: "System",
    icon: "/assets/icons/computer.svg",
  },
];

export const sidebarLinks: SidebarLink[] = [
  {
    imgURL: "/assets/icons/home.svg",
    route: "/",
    label: "Home",
  },
  {
    imgURL: "/assets/icons/users.svg",
    route: "/community",
    label: "Community",
  },
  {
    imgURL: "/assets/icons/star.svg",
    route: "/collection",
    label: "Collections",
  },
  {
    imgURL: "/assets/icons/suitcase.svg",
    route: "/jobs",
    label: "Find Jobs",
  },
  {
    imgURL: "/assets/icons/tag.svg",
    route: "/tags",
    label: "Tags",
  },
  {
    imgURL: "/assets/icons/user.svg",
    route: "/profile",
    label: "Profile",
  },
  {
    imgURL: "/assets/icons/question.svg",
    route: "/ask-question",
    label: "Ask a question",
  },
];

export const BADGE_CRITERIA = {
  QUESTION_COUNT: {
    BRONZE: 10,
    SILVER: 50,
    GOLD: 100,
  },
  ANSWER_COUNT: {
    BRONZE: 10,
    SILVER: 50,
    GOLD: 100,
  },
  QUESTION_UPVOTES: {
    BRONZE: 10,
    SILVER: 50,
    GOLD: 100,
  },
  ANSWER_UPVOTES: {
    BRONZE: 10,
    SILVER: 50,
    GOLD: 100,
  },
  TOTAL_VIEWS: {
    BRONZE: 1000,
    SILVER: 10000,
    GOLD: 100000,
  },
};
```
let's create a types folder and create a types.d.ts file

```ts
import { BADGE_CRITERIA } from "@/constants";
export interface SidebarLink {
  imgURL: string;
  route: string;
  label: string;
}
export interface Job {
  id?: string;
  employer_name?: string;
  employer_logo?: string | undefined;
  employer_website?: string;
  job_employment_type?: string;
  job_title?: string;
  job_description?: string;
  job_apply_link?: string;
  job_city?: string;
  job_state?: string;
  job_country?: string;
}
export interface Country {
  name: {
    common: string;
  };
}
export interface ParamsProps {
  params: { id: string };
}
export interface SearchParamsProps {
  searchParams: { [key: string]: string | undefined };
}
export interface URLProps {
  params: { id: string };
  searchParams: { [key: string]: string | undefined };
}
export interface BadgeCounts {
  GOLD: number;
  SILVER: number;
  BRONZE: number;
}
export type BadgeCriteriaType = keyof typeof BADGE_CRITERIA;
```

final code for the ThemeProvider.tsx

```tsx
"use client";

import {
  useContext,
  createContext,
  useState,
  ReactNode,
  FC,
  useEffect,
} from "react";

export type TTheme = "dark" | "light" | undefined;

type TThemeContext = {
  theme: TTheme;
  setTheme: (theme: TTheme) => void;
};

const ThemeContext = createContext<TThemeContext | undefined>(undefined);

type TThemeProvider = {
  children: ReactNode;
};
export const ThemeProvider: FC<TThemeProvider> = ({ children }) => {
  const [theme, setTheme] = useState<"dark" | "light" | undefined>(undefined);

  const handleThemeChange = () => {
    if (
      localStorage.theme === "dark" ||
      (!("theme" in localStorage) &&
        window.matchMedia("(prefers-color-scheme: dark)").matches)
    ) {
      document.documentElement.classList.add("dark");
      setTheme("dark");
    } else {
      document.documentElement.classList.remove("dark");
      setTheme("light");
    }
  };

  useEffect(() => {
    handleThemeChange();
  }, [theme]);

  return (
    <ThemeContext.Provider
      value={{
        theme,
        setTheme,
      }}
    >
      {children}
    </ThemeContext.Provider>
  );
};

export const useTheme = () => {
  const context = useContext(ThemeContext);
  if (context === undefined) {
    throw new Error("useTheme must be used within a ThemeProvider");
  }
  return context;
};

```
small change in the tailwind
```ts
import type { Config } from "tailwindcss";

const config: Config = {
  darkMode: "class",
  content: [
    "./pages/**/*.{js,ts,jsx,tsx,mdx}",
    "./components/**/*.{js,ts,jsx,tsx,mdx}",
    "./app/**/*.{js,ts,jsx,tsx,mdx}",
  ],
  theme: {
    extend: {
      colors: {
        primary: {
          500: "#FF7000",
          100: "#FFF1E6",
        },
        dark: {
          100: "#000000",
          200: "#0F1117",
          300: "#151821",
          400: "#212734",
          500: "#3F4354",
        },
        light: {
          900: "#FFFFFF",
          800: "#F4F6F8",
          850: "#FDFDFD",
          700: "#DCE3F1",
          500: "#7B8EC8",
          400: "#858EAD",
        },
        "accent-blue": "#1DA1F2",
      },
      fontFamily: {
        inter: ["var(--font-inter)"],
        spaceGrotesk: ["var(--font-spaceGrotesk)"],
      },
      boxShadow: {
        "light-100":
          "0px 12px 20px 0px rgba(184, 184, 184, 0.03), 0px 6px 12px 0px",
        "light-200": "10px 10px 20px 0px rgba(218, 213, 213, 0.10)",
        "light-300": "-10px 10px 20px 0px rgba(218, 213, 213, 0.10)",
        "dark-100": "0px 2px 10px 0px rgba(46, 52, 56, 0.10)",
        "dark-200": "2px 0px 20px 0px rgba(39, 36, 36, 0.04)",
      },
      backgroundImage: {
        "auth-dark": "url('/assets/images/auth-dark.png')",
        "auth-light": "url('/assets/images/auth-light.png')",
      },
      screens: {
        xs: "420px",
      },
      keyframes: {
        "accordion-down": {
          from: { height: "0" },
          to: { height: "var(--radix-accordion-content-height)" },
        },
        "accordion-up": {
          from: { height: "var(--radix-accordion-content-height)" },
          to: { height: "0" },
        },
      },
      animation: {
        "accordion-down": "accordion-down 0.2s ease-out",
        "accordion-up": "accordion-up 0.2s ease-out",
      },
    },
  },
  plugins: [require("tailwindcss-animate"), require("@tailwindcss/typography")],
};
export default config;

```

add the globals.css file

```css
@import url('../styles/theme.css');
@tailwind base;
@tailwind components;
@tailwind utilities;
body {
	font-family: 'Inter', sans-serif;
}
@layer utilities {
	.flex-center {
		@apply flex justify-center items-center;
	}
	.flex-between {
		@apply flex justify-between items-center;
	}
	.flex-start {
		@apply flex justify-start items-center;
	}
	.card-wrapper {
		@apply bg-light-900 dark:dark-gradient shadow-light-100 dar;
	}
	.btn {
		@apply bg-light-800 dark:bg-dark-300 !important;
	}
	.btn-secondary {
		@apply bg-light-800 dark:bg-dark-400 !important;
	}
	.btn-tertiary {
		@apply bg-light-700 dark:bg-dark-300 !important;
	}
	.markdown {
		@apply max-w-full prose dark:prose-p:text-light-700 dark:pros;
	}
	.primary-gradient {
		background: linear-gradient(129deg, #ff7000 0%, #e2995f 100%);
	}
	.dark-gradient {
		background: linear-gradient(
			232deg,
			rgba(23, 28, 35, 0.41) 0%,
			rgba(19, 22, 28, 0.7) 100%
		);
	}
	.tab {
		@apply min-h-full dark:bg-dark-400 bg-light-800 text-light-5;
	}
	.no-focus {
		@apply focus-visible:ring-0 focus-visible:ring-transparent focus;
	}
}

.active-theme {
	filter: invert(53%) sepia(98%) saturate(3332%) hue-rotate(0deg)
		brightness(104%) contrast(106%) !important;
}
.light-gradient {
	background: linear-gradient(
		132deg,
		rgba(247, 249, 255, 0.5) 0%,
		rgba(229, 237, 255, 0.25) 100%
	);
}
.primary-text-gradient {
	background: linear-gradient(129deg, #ff7000 0%, #e2995f 100%);
	background-clip: text;
	-webkit-background-clip: text;
	-webkit-text-fill-color: transparent;
}
.custom-scrollbar::-webkit-scrollbar {
	width: 3px;
	height: 3px;
	border-radius: 2px;
}
.custom-scrollbar::-webkit-scrollbar-track {
	background: #ffffff;
}
.custom-scrollbar::-webkit-scrollbar-thumb {
	background: #888;
	border-radius: 50px;
}
.custom-scrollbar::-webkit-scrollbar-thumb:hover {
	background: #555;
}
/* Markdown Start */
.markdown a {
	color: #1da1f2;
}
.markdown a,
code {
	/* These are technically the same, but use both */
	overflow-wrap: break-word;
	word-wrap: break-word;
	-ms-word-break: break-all;
	/* This is the dangerous one in WebKit, as it breaks things whereve
word-break: break-all;
/* Instead use this non-standard one: */
	word-break: break-word;
	/* Adds a hyphen where the word breaks, if supported (No Blink) */
	-ms-hyphens: auto;
	-moz-hyphens: auto;
	-webkit-hyphens: auto;
	hyphens: auto;
	padding: 2px;
	color: #ff7000 !important;
}
.markdown pre {
	display: grid;
	width: 100%;
}
.markdown pre code {
	width: 100%;
	display: block;
	overflow-x: auto;
	color: inherit !important;
}
/* Markdown End */

/* Clerk */
.cl-internal-b3fm6y {
	background: linear-gradient(129deg, #ff7000 0%, #e2995f 100%);
}
.hash-span {
	margin-top: -140px;
	padding-bottom: 140px;
	display: block;
}
/* Hide scrollbar for Chrome, Safari and Opera */
.no-scrollbar::-webkit-scrollbar {
	display: none;
}
/* Hide scrollbar for IE, Edge and Firefox */
.no-scrollbar {
	-ms-overflow-style: none; /* IE and Edge */
	scrollbar-width: none; /* Firefox */
}
```
navBar.tsx

```tsx
import { FC } from "react";
import Link from "next/link";
import Image from "next/image";
import { SignedIn, UserButton } from "@clerk/nextjs";
import Theme from "@/components/shared/navbar/Theme";

type TNavBar = {};
const NavBar: FC<TNavBar> = () => {
  return (
    <nav
      className={
        "flex-between background-light900_dark200 fixed z-50 flex w-full gap-5  p-6 shadow-light-300 dark:shadow-none sm:px-12"
      }
    >
      <Link href={"/"} className={"flex items-center gap-1"}>
        <Image
          src={"/assets/images/site-logo.svg"}
          width={23}
          height={23}
          alt={"StackFlow"}
        />
        <p
          className={
            "h2-bold font-spaceGrotesk text-dark-100 dark:text-light-900 max-sm:hidden"
          }
        >
          Stack <span className={"text-primary-500"}>Flow</span>
        </p>
      </Link>
      {/*  GLOBAL SEARCH COMPONENT */}
      <div className={"flex-between gap-5"}>
        <Theme />
        <SignedIn>
          <UserButton
            appearance={{
              elements: {
                avatarBox: "h-10 w-10",
              },
              variables: {
                colorPrimary: "#ff7000",
              },
            }}
            afterSignOutUrl="/"
          />
        </SignedIn>
        {/* Mobile Navigation */}
      </div>
    </nav>
  );
};

export default NavBar;
```

Theme.tsx

```tsx
"use client";
import { TTheme, useTheme } from "@/context/ThemeProvider";
import {
  Menubar,
  MenubarContent,
  MenubarItem,
  MenubarMenu,
  MenubarTrigger,
} from "@/components/ui/menubar";
import Image from "next/image";
import { THEMES } from "@/CONSTANTS";

const Theme = () => {
  const { theme: mode, setTheme } = useTheme();

  return (
    <Menubar className={"relative border-none bg-transparent shadow-none"}>
      <MenubarMenu>
        <MenubarTrigger
          className={
            "focus:bg-light-900 data-[state=open]:bg-light-900 dark:focus:bg-dark-200 dark:data-[state=open]:bg-dark-200"
          }
        >
          {mode === "light" ? (
            <Image
              src={"/assets/icons/sun.svg"}
              width={20}
              height={20}
              alt={"sun"}
              className={"active-theme"}
            />
          ) : (
            <Image
              src={"/assets/icons/moon.svg"}
              width={20}
              height={20}
              alt={"moon"}
              className={"active-theme"}
            />
          )}
        </MenubarTrigger>
        <MenubarContent
          className={
            "absolute right-[-3rem] mt-3 min-w-[120px] rounded border py-2  dark:border-dark-400 dark:bg-dark-300"
          }
        >
          {THEMES.map((theme) => (
            <MenubarItem
              className={
                "flex items-center gap-4 px-2.5 py-2 dark:focus:bg-dark-400"
              }
              onClick={() => {
                setTheme(theme.value as TTheme);
                if (theme.value !== "system") {
                  localStorage.setItem("theme", theme.value);
                } else {
                  localStorage.removeItem("theme");
                }
              }}
              key={theme.value}
            >
              <Image
                src={theme.icon}
                height={20}
                width={20}
                alt={theme.value}
                className={`${mode === theme.value ? "active-theme" : ""}`}
              />
              <p
                className={`body-semibold text-light-500  ${
                  mode === theme.value
                    ? "text-primary-500"
                    : "text-dark100_light900"
                }`}
              >
                {theme.label}
              </p>
            </MenubarItem>
          ))}
        </MenubarContent>
      </MenubarMenu>
    </Menubar>
  );
};

export default Theme;

```

light mode 

![Alt text](image-114.png)

dark mode

![Alt text](image-115.png)

theme selector

![Alt text](image-116.png)

### MobileNavigation

let's use sheet component from shadcn https://ui.shadcn.com/docs/components/sheet

```bash
npx shadcn-ui@latest add sheet
```
let's create a mobile navigation component

```tsx
"use client";
import {
  Sheet,
  SheetClose,
  SheetContent,
  SheetTrigger,
} from "@/components/ui/sheet";
import Image from "next/image";
import Link from "next/link";
import { SignedOut } from "@clerk/nextjs";
import { Button } from "@/components/ui/button";
import { sidebarLinks } from "@/CONSTANTS";
import { usePathname } from "next/navigation";

const NavContent = () => {
  const pathName = usePathname();
  return (
    <section className={"flex h-full flex-col gap-6 pt-16"}>
      {sidebarLinks.map((link) => {
        const isActive =
          pathName === link.route ||
          (pathName.includes(link.route) && link.route.length > 0);
        return (
          <SheetClose asChild key={link.route}>
            <Link
              href={link.route}
              className={`${
                isActive
                  ? "primary-gradient rounded-lg text-light-900"
                  : "text-dark300_light900"
              } flex items-center justify-start gap-4 bg-transparent p-4`}
            >
              <Image
                src={link.imgURL}
                width={20}
                height={20}
                alt={link.label}
                className={`${isActive ? "" : "invert-colors"}`}
              />
              <p className={`${isActive ? "base-medium" : "base-bold"}`}>
                {link.label}
              </p>
            </Link>
          </SheetClose>
        );
      })}
    </section>
  );
};

const MobileNav = () => {
  return (
    <Sheet>
      <SheetTrigger asChild>
        <Image
          src={"/assets/icons/hamburger.svg"}
          alt={"hamburger menue"}
          width={36}
          height={36}
          className={"invert-colors sm:hidden"}
        />
      </SheetTrigger>
      <SheetContent
        side={"left"}
        className={"background-light900_dark200 border-none"}
      >
        <Link href={"/"} className={"flex items-center gap-1"}>
          <Image
            src={"/assets/images/site-logo.svg"}
            width={23}
            height={23}
            alt={"StackFlow"}
          />
          <p className={"h2-bold text-dark100_light900 font-spaceGrotesk"}>
            Stack <span className={"text-primary-500"}>Flow</span>
          </p>
        </Link>
        <div>
          <SheetClose asChild>
            <NavContent />
          </SheetClose>
          <SignedOut>
            <div className={"flex flex-col gap-3"}>
              <SheetClose>
                <Link href={"/sign-in"}>
                  <Button
                    className={
                      "small-medium btn-secondary min-h-[41px] w-full rounded-lg px-4 py-3"
                    }
                  >
                    <span className={"primary-text-gradient"}>Log In</span>
                  </Button>
                </Link>
              </SheetClose>
              <SheetClose>
                <Link href={"/sign-up"}>
                  <Button
                    className={
                      "small-medium light-border-2 btn-tertiary text-dark400_light900 min-h-[41px] w-full rounded-lg px-4 py-3"
                    }
                  >
                    Sign Up
                  </Button>
                </Link>
              </SheetClose>
            </div>
          </SignedOut>
        </div>
      </SheetContent>
    </Sheet>
  );
};

export default MobileNav;
```

import the MobineNav component to the navBar component

```tsx
import { FC } from "react";
import Link from "next/link";
import Image from "next/image";
import { SignedIn, UserButton } from "@clerk/nextjs";
import Theme from "@/components/shared/navbar/Theme";
import MobileNav from "@/components/shared/navbar/MobileNav";

type TNavBar = {};
const NavBar: FC<TNavBar> = () => {
  return (
    <nav
      className={
        "flex-between background-light900_dark200 fixed z-50 flex w-full gap-5  p-6 shadow-light-300 dark:shadow-none sm:px-12"
      }
    >
      <Link href={"/"} className={"flex items-center gap-1"}>
        <Image
          src={"/assets/images/site-logo.svg"}
          width={23}
          height={23}
          alt={"StackFlow"}
        />
        <p
          className={
            "h2-bold font-spaceGrotesk text-dark-100 dark:text-light-900 max-sm:hidden"
          }
        >
          Stack <span className={"text-primary-500"}>Flow</span>
        </p>
      </Link>
      {/*  GLOBAL SEARCH COMPONENT */}
      <div className={"flex-between gap-5"}>
        <Theme />
        <SignedIn>
          <UserButton
            appearance={{
              elements: {
                avatarBox: "h-10 w-10",
              },
              variables: {
                colorPrimary: "#ff7000",
              },
            }}
            afterSignOutUrl="/"
          />
        </SignedIn>
        <MobileNav />
      </div>
    </nav>
  );
};

export default NavBar;
```


## Sidebar 🔲 
### 11_Sidebar 🔲
## Home Page 🔲
### 01_Home Route 🔲
### 02_Active Lesson 3 — Create a LocalSearchbar 🔲
### 03_LocalSearchbar Component 🔲
### 04_Active Lesson 4 — Create a Filter 🔲
### 05_Home Filters 🔲
### 07_Create Question Card 🔲
## Ask a Question Page 🔲
### 
### 
### 
### 
### 
### 
## Develop Backend
## Create a Question
## Fetching Questions on the Home Page
## The Webhooks
## Community Page
## Tags Page
## Question Details
## Voting
## Collections Page
## Views
## Tag Details Page
## Profile Page
## Edit_Delete User Actions
## Show Top Results
## The Local Search Functionality
## The Filters
## The Pagination
## Global Search
## Reputation
## Badge System
## Generate AI Answer
## Loadings _ Toasts
## Meta Data
## Bug Fixing and Recommendation
## Next.js 13.5+
## Deployment
### 
### 
### 
### 
### 
### 
### 