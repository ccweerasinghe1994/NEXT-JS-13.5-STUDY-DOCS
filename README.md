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
  - [Theme ✅](#theme-)
    - [Creating a Global Theme Context for DevFlow ✅](#creating-a-global-theme-context-for-devflow-)
  - [Navbar ✅](#navbar-)
    - [Container and User Account ✅](#container-and-user-account-)
    - [Shadcn Installation](#shadcn-installation)
    - [Theme Switcher and Mobile Navigation](#theme-switcher-and-mobile-navigation)
    - [theme switcher ✅](#theme-switcher-)
    - [MobileNavigation ✅](#mobilenavigation-)
    - [Global Search ✅](#global-search-)
  - [Sidebar ✅](#sidebar-)
    - [Sidebar ✅](#sidebar--1)
    - [left Side Bar ✅](#left-side-bar-)
  - [Home Page ✅](#home-page-)
    - [01\_Home Route ✅](#01_home-route-)
    - [Active Lesson 3 — Create a LocalSearch bar](#active-lesson-3--create-a-localsearch-bar)
    - [LocalSearchbar Component ✅](#localsearchbar-component-)
    - [Home Filters ✅](#home-filters-)
    - [Create Question Card ✅](#create-question-card-)
  - [Ask a Question Page ✅](#ask-a-question-page-)
    - [Question Form and Validations ✅](#question-form-and-validations-)
    - [The Question Editor ✅](#the-question-editor-)
    - [Custom Multiple Tags Input ✅](#custom-multiple-tags-input-)
    - [Making the Form Reusable ✅](#making-the-form-reusable-)
  - [Develop Backend 🔲](#develop-backend-)
    - [Thinking in Backend ✅](#thinking-in-backend-)
      - [What can I do with Next.js Server Actions?](#what-can-i-do-with-nextjs-server-actions)
    - [MongoDB and Server Actions Setup 🔲](#mongodb-and-server-actions-setup-)
    - [Creating Question Model 🔲](#creating-question-model-)
    - [Creating a User Model 🔲](#creating-a-user-model-)
    - [Creating a Tag Model 🔲](#creating-a-tag-model-)
  - [Create a Question 🔲](#create-a-question-)
  - [Fetching Questions on the Home Page 🔲](#fetching-questions-on-the-home-page-)
  - [The Webhooks 🔲](#the-webhooks-)
  - [Community Page 🔲](#community-page-)
  - [Tags Page 🔲](#tags-page-)
  - [Question Details 🔲](#question-details-)
  - [Voting 🔲](#voting-)
  - [Collections Page 🔲](#collections-page-)
  - [Views 🔲](#views-)
  - [Tag Details Page 🔲](#tag-details-page-)
  - [Profile Page 🔲](#profile-page-)
  - [Edit\_Delete User Actions 🔲](#edit_delete-user-actions-)
  - [Show Top Results 🔲](#show-top-results-)
  - [The Local Search Functionality 🔲](#the-local-search-functionality-)
  - [The Filters 🔲](#the-filters-)
  - [The Pagination 🔲](#the-pagination-)
  - [Global Search 🔲](#global-search--1)
  - [Reputation 🔲](#reputation-)
  - [Badge System 🔲](#badge-system-)
  - [Generate AI Answer 🔲](#generate-ai-answer-)
  - [Loadings \_ Toasts 🔲](#loadings-_-toasts-)
  - [Meta Data 🔲](#meta-data-)
  - [Bug Fixing and Recommendation 🔲](#bug-fixing-and-recommendation-)
  - [Next.js 13.5+ 🔲](#nextjs-135-)
  - [Deployment 🔲](#deployment-)
    - [](#)
    - [](#-1)
    - [](#-2)
    - [](#-3)
    - [](#-4)
    - [](#-5)
    - [](#-6)


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


## Theme ✅
### Creating a Global Theme Context for DevFlow ✅

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
## Navbar ✅

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

### MobileNavigation ✅

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

output

![Alt text](image-117.png)

### Global Search ✅ 

let's install the input component from shadcn https://ui.shadcn.com/docs/components/input

```bash
npx shadcn-ui@latest add input
```

let's create a global search component

```tsx
import Image from "next/image";
import { Input } from "@/components/ui/input";

const GlobalSearch = () => {
  return (
    <div className={"relative w-full max-w-[600px] max-lg:hidden"}>
      <div className="background-light800_darkgradient relative flex min-h-[56px] grow items-center  gap-1 rounded-xl px-4">
        <Image
          src={"/assets/icons/search.svg"}
          alt={"search"}
          width={24}
          height={24}
          className={"cursor-pointer"}
        />
        <Input
          className={
            "paragraph-regular no-focus placeholder background-light800_darkgradient border-none shadow-none outline-none"
          }
          type={"text"}
          placeholder={"Search Globally"}
          value={""}
        />
      </div>
    </div>
  );
};

export default GlobalSearch;
```

add it to the navBar component

```tsx
import { FC } from "react";
import Link from "next/link";
import Image from "next/image";
import { SignedIn, UserButton } from "@clerk/nextjs";
import Theme from "@/components/shared/navbar/Theme";
import MobileNav from "@/components/shared/navbar/MobileNav";
import GlobalSearch from "@/components/shared/search/GlobalSearch";

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
      <GlobalSearch />
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
![Alt text](image-118.png)

![Alt text](image-119.png)


## Sidebar ✅
### Sidebar ✅

let's create a SideBar component
```tsx
"use client";
import { usePathname } from "next/navigation";
import { sidebarLinks } from "@/CONSTANTS";
import Link from "next/link";
import Image from "next/image";
import { SignedIn, SignedOut, SignOutButton } from "@clerk/nextjs";
import { Button } from "@/components/ui/button";

const SideBar = () => {
  const pathName = usePathname();
  return (
    <section
      className={
        "background-light900_dark200 light-border custom-scrollbar sticky left-0 top-0 flex h-screen flex-col justify-between overflow-y-auto border-r p-6 pt-36 shadow-light-300 dark:shadow-none max-sm:hidden lg:w-[266px]"
      }
    >
      <div className="flex flex-1 flex-col gap-6">
        {sidebarLinks.map((link) => {
          const isActive =
            pathName === link.route ||
            (pathName.includes(link.route) && link.route.length > 0);
          return (
            <div key={link.route}>
              <Link
                href={link.route}
                className={`${
                  isActive
                    ? "primary-gradient rounded-lg text-light-900"
                    : "text-dark300_light900"
                } flex items-center justify-start gap-4 bg-transparent p-4 max-sm:justify-center max-sm:gap-0 max-sm:px-0`}
              >
                <Image
                  src={link.imgURL}
                  width={20}
                  height={20}
                  alt={link.label}
                  className={`${isActive ? "" : "invert-colors"}`}
                />
                <p
                  className={`${
                    isActive ? "base-medium" : "base-bold"
                  } max-lg:hidden`}
                >
                  {link.label}
                </p>
              </Link>
            </div>
          );
        })}
      </div>
      <SignedIn>
        <Button
          className={
            "small-medium light-border-2 btn-tertiary text-dark400_light900 min-h-[41px] w-full rounded-lg px-4 py-3"
          }
        >
          <SignOutButton>Logout</SignOutButton>
        </Button>
      </SignedIn>
      <SignedOut>
        <div className={"flex flex-col gap-3"}>
          <Link href={"/sign-in"}>
            <Button
              className={
                "small-medium btn-secondary min-h-[41px] w-full rounded-lg px-4 py-3"
              }
            >
              <Image
                src={"/assets/icons/account.svg"}
                alt={"account"}
                width={20}
                height={20}
                className={"invert-colors lg:hidden"}
              />
              <span className={"primary-text-gradient max-lg:hidden"}>
                Log In
              </span>
            </Button>
          </Link>

          <Link href={"/sign-up"}>
            <Button
              className={
                "small-medium light-border-2 btn-tertiary text-dark400_light900 min-h-[41px] w-full rounded-lg px-4 py-3"
              }
            >
              <Image
                src={"/assets/icons/sign-up.svg"}
                alt={"sign up"}
                width={20}
                height={20}
                className={"invert-colors lg:hidden"}
              />
              <span className={"max-lg:hidden"}>Sign Up</span>
            </Button>
          </Link>
        </div>
      </SignedOut>
    </section>
  );
};

export default SideBar;

```


```tsx
import { FC, ReactNode } from "react";
import NavBar from "@/components/shared/navbar/NavBar";
import SideBar from "@/components/shared/sidebar/SideBar";

type TLayout = {
  children: ReactNode;
};

const Layout: FC<TLayout> = ({ children }) => {
  return (
    <main className={"background-light850_dark100 relative"}>
      <NavBar />
      <div className="flex">
        <SideBar />
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

![Alt text](image-120.png)

![Alt text](image-121.png)

### left Side Bar ✅
```tsx
import { FC, ReactNode } from "react";
import NavBar from "@/components/shared/navbar/NavBar";
import LeftSideBar from "@/components/shared/sidebar/LeftSideBar";
import RightSideBar from "@/components/shared/sidebar/RightSideBar";

type TLayout = {
  children: ReactNode;
};

const Layout: FC<TLayout> = ({ children }) => {
  return (
    <main className={"background-light850_dark100 relative"}>
      <NavBar />
      <div className="flex">
        <LeftSideBar />
        <section
          className={
            "flex min-h-screen flex-1 flex-col px-6 pb-6 pt-36 max-md:pb-14 sm:px-14"
          }
        >
          <div className={"mx-auto w-full max-w-5xl"}>{children}</div>
        </section>
        <RightSideBar />
      </div>
      Toaster
    </main>
  );
};

export default Layout;
```

RightSideBar.tsx

```tsx
"use client";
import { usePathname } from "next/navigation";
import { sidebarLinks } from "@/CONSTANTS";
import Link from "next/link";
import Image from "next/image";
import { SignedIn, SignedOut, SignOutButton } from "@clerk/nextjs";
import { Button } from "@/components/ui/button";

const LeftSideBar = () => {
  const pathName = usePathname();
  return (
    <section
      className={
        "background-light900_dark200 light-border custom-scrollbar sticky left-0 top-0 flex h-screen flex-col justify-between overflow-y-auto border-r p-6 pt-36 shadow-light-300 dark:shadow-none max-sm:hidden lg:w-[266px]"
      }
    >
      <div className="flex flex-1 flex-col gap-6">
        {sidebarLinks.map((link) => {
          const isActive =
            pathName === link.route ||
            (pathName.includes(link.route) && link.route.length > 0);
          return (
            <div key={link.route}>
              <Link
                href={link.route}
                className={`${
                  isActive
                    ? "primary-gradient rounded-lg text-light-900"
                    : "text-dark300_light900"
                } flex items-center justify-start gap-4 bg-transparent p-4 max-sm:justify-center max-sm:gap-0 max-sm:px-0`}
              >
                <Image
                  src={link.imgURL}
                  width={20}
                  height={20}
                  alt={link.label}
                  className={`${isActive ? "" : "invert-colors"}`}
                />
                <p
                  className={`${
                    isActive ? "base-medium" : "base-bold"
                  } max-lg:hidden`}
                >
                  {link.label}
                </p>
              </Link>
            </div>
          );
        })}
      </div>
      <SignedIn>
        <Button
          className={
            "small-medium light-border-2 btn-tertiary text-dark400_light900 min-h-[41px] w-full rounded-lg px-4 py-3"
          }
        >
          <SignOutButton>Logout</SignOutButton>
        </Button>
      </SignedIn>
      <SignedOut>
        <div className={"flex flex-col gap-3"}>
          <Link href={"/sign-in"}>
            <Button
              className={
                "small-medium btn-secondary min-h-[41px] w-full rounded-lg px-4 py-3"
              }
            >
              <Image
                src={"/assets/icons/account.svg"}
                alt={"account"}
                width={20}
                height={20}
                className={"invert-colors lg:hidden"}
              />
              <span className={"primary-text-gradient max-lg:hidden"}>
                Log In
              </span>
            </Button>
          </Link>

          <Link href={"/sign-up"}>
            <Button
              className={
                "small-medium light-border-2 btn-tertiary text-dark400_light900 min-h-[41px] w-full rounded-lg px-4 py-3"
              }
            >
              <Image
                src={"/assets/icons/sign-up.svg"}
                alt={"sign up"}
                width={20}
                height={20}
                className={"invert-colors lg:hidden"}
              />
              <span className={"max-lg:hidden"}>Sign Up</span>
            </Button>
          </Link>
        </div>
      </SignedOut>
    </section>
  );
};

export default LeftSideBar;

```

RenderTags.tsx

```tsx
import { FC } from "react";
import Link from "next/link";
import { Badge } from "@/components/ui/badge";

type TRenderTagsProps = {
  _id: number;
  name: string;
  totalQuestions: number;
  showCount?: boolean;
};

const RenderTags: FC<TRenderTagsProps> = ({
  name,
  totalQuestions,
  showCount,
  _id,
}) => {
  return (
    <Link href={`/tags/${_id}`} className="flex justify-between gap-2">
      <Badge
        className={
          "subtle-medium background-light800_dark300 rounded-md border-none px-4 py-2 uppercase text-light-400"
        }
      >
        {name}
      </Badge>
      {showCount && (
        <p className={"small-medium text-dark500_light700"}>{totalQuestions}</p>
      )}
    </Link>
  );
};

export default RenderTags;
```

and install the badge component from shadcn https://ui.shadcn.com/docs/components/badge

```bash
npx shadcn-ui@latest add badge
```

## Home Page ✅
### 01_Home Route ✅
let's add the top part of the home page
![Alt text](image-122.png)

```tsx
import Link from "next/link";
import { Button } from "@/components/ui/button";

export default function Home() {
  return (
    <>
      <div className="flex w-full flex-col-reverse justify-between gap-4 sm:flex-row sm:items-center">
        <h1 className={"h1-bold text-dark100_light900"}>All Questions</h1>
        <Link
          href={"/ask-question"}
          className={"flex justify-end max-sm:w-full"}
        >
          <Button
            className={
              "primary-gradient min-h-[46px] px-4 py-3 !text-light-900"
            }
          >
            Ask Question
          </Button>
        </Link>
      </div>
    </>
  );
}

```

![Alt text](image-123.png)

on mobile

![Alt text](image-124.png)
### Active Lesson 3 — Create a LocalSearch bar 
let's build the search bar component

![Alt text](image-125.png)
### LocalSearchbar Component ✅
let's create a local search bar component

```tsx
"use client";

import { FC } from "react";
import Image from "next/image";
import { Input } from "@/components/ui/input";

type TLocationProps = {
  route: string;
  iconPosition: "left" | "right";
  imageSrc: string;
  placeholder: string;
  otherClasses?: string;
};

const LocalSearch: FC<TLocationProps> = ({
  otherClasses,
  route,
  imageSrc,
  iconPosition,
  placeholder,
}) => {
  return (
    <div
      className={`background-light800_darkgradient flex min-h-[56px] grow items-center gap-4 rounded-[10px] px-4 ${otherClasses}`}
    >
      {iconPosition === "left" && (
        <Image
          src={imageSrc}
          alt={"search icon"}
          width={24}
          height={24}
          className={"cursor-pointer"}
        />
      )}
      <Input
        type={"text"}
        placeholder={placeholder}
        value={""}
        onChange={() => {}}
        className={
          "paragraph-regular no-focus placeholder background-light800_darkgradient border-none shadow-none outline-none"
        }
      />
      {iconPosition === "right" && (
        <Image
          src={imageSrc}
          alt={"search icon"}
          width={24}
          height={24}
          className={"cursor-pointer"}
        />
      )}
    </div>
  );
};

export default LocalSearch;

```
light mode

![Alt text](image-126.png)

dark mode

![Alt text](image-127.png)

let's add this component to the home page

```tsx
import Link from "next/link";
import { Button } from "@/components/ui/button";
import LocalSearch from "@/components/shared/search/LocalSearch";
import Filter from "@/components/shared/filters/Filter";
import { HOME_PAGE_FILTERS } from "@/CONSTANTS/filters";
import HomeFilter from "@/components/home/HomeFilter";

export default function Home() {
  return (
    <>
      <div className="flex w-full flex-col-reverse justify-between gap-4 sm:flex-row sm:items-center">
        <h1 className={"h1-bold text-dark100_light900"}>All Questions</h1>
        <Link
          href={"/ask-question"}
          className={"flex justify-end max-sm:w-full"}
        >
          <Button
            className={
              "primary-gradient min-h-[46px] px-4 py-3 !text-light-900"
            }
          >
            Ask Question
          </Button>
        </Link>
      </div>
      <div className="mt-11 flex justify-between gap-5 max-sm:flex-col sm:items-center">
        <LocalSearch
          imageSrc={"/assets/icons/search.svg"}
          route={"/"}
          iconPosition={"left"}
          placeholder={"Search Questions ..."}
          otherClasses={"flex-1"}
        />
      </div>
      <HomeFilter />
    </>
  );
}
``` 
### Home Filters ✅

let's create a Filter component

```tsx
"use client";
import { FC } from "react";
import { TFilterItem } from "@/types/types";
import {
  Select,
  SelectContent,
  SelectGroup,
  SelectItem,
  SelectTrigger,
  SelectValue,
} from "@/components/ui/select";

type TFilterProps = {
  filters: TFilterItem[];
  otherClasses?: string;
  containerClasses?: string;
};

const Filter: FC<TFilterProps> = ({
  filters,
  otherClasses,
  containerClasses,
}) => {
  return (
    <div className={`relative ${containerClasses}`}>
      <Select>
        <SelectTrigger
          className={`${otherClasses} body-regular light-border background-light800_dark300 text-dark500_light700 border px-5 py-2.5`}
        >
          <div className={"line-clamp-1 flex-1 text-left"}>
            <SelectValue placeholder="Select a Filter" />
          </div>
        </SelectTrigger>
        <SelectContent>
          <SelectGroup>
            {filters.map((filter) => (
              <SelectItem key={filter.value} value={filter.value}>
                {filter.name}
              </SelectItem>
            ))}
          </SelectGroup>
        </SelectContent>
      </Select>
    </div>
  );
};

export default Filter;
```

let's add this component to the home page

```tsx  
import Link from "next/link";
import { Button } from "@/components/ui/button";
import LocalSearch from "@/components/shared/search/LocalSearch";
import Filter from "@/components/shared/filters/Filter";
import { HOME_PAGE_FILTERS } from "@/CONSTANTS/filters";
import HomeFilter from "@/components/home/HomeFilter";

export default function Home() {
  return (
    <>
      <div className="flex w-full flex-col-reverse justify-between gap-4 sm:flex-row sm:items-center">
        <h1 className={"h1-bold text-dark100_light900"}>All Questions</h1>
        <Link
          href={"/ask-question"}
          className={"flex justify-end max-sm:w-full"}
        >
          <Button
            className={
              "primary-gradient min-h-[46px] px-4 py-3 !text-light-900"
            }
          >
            Ask Question
          </Button>
        </Link>
      </div>
      <div className="mt-11 flex justify-between gap-5 max-sm:flex-col sm:items-center">
        <LocalSearch
          imageSrc={"/assets/icons/search.svg"}
          route={"/"}
          iconPosition={"left"}
          placeholder={"Search Questions ..."}
          otherClasses={"flex-1"}
        />
        <Filter
          filters={HOME_PAGE_FILTERS}
          otherClasses={"min-h-[56px] sm:min-w-[170px]"}
          containerClasses={"hidden max-md:flex"}
        />
      </div>
      <HomeFilter />
    </>
  );
}
```

let's create a HomeFilter component

```tsx
"use client";
import { HOME_PAGE_FILTERS } from "@/CONSTANTS/filters";
import { Button } from "@/components/ui/button";

const HomeFilter = () => {
  const isActive = "newest";
  return (
    <div className="mt-10 hidden flex-wrap gap-3 md:flex ">
      {HOME_PAGE_FILTERS.map((filter) => (
        <Button
          className={`body-medium rounded-lg px-6 py-3 capitalize shadow-none ${
            isActive === filter.value
              ? "bg-primary-100 text-primary-500"
              : "bg-light-800 text-light-500 hover:bg-light-900 dark:bg-dark-300 dark:text-light-500"
          }`}
          key={filter.value}
          onClick={() => {}}
        >
          {filter.name}
        </Button>
      ))}
    </div>
  );
};
export default HomeFilter;
```
### Create Question Card ✅

let's create a No Result component

```tsx
import Link from "next/link";
import { Button } from "@/components/ui/button";
import LocalSearch from "@/components/shared/search/LocalSearch";
import Filter from "@/components/shared/filters/Filter";
import { HOME_PAGE_FILTERS } from "@/CONSTANTS/filters";
import HomeFilter from "@/components/home/HomeFilter";
import NoResult from "@/components/shared/noResult/NoResult";

const questions = [
  // {
  //   _id: 1,
  //   title: "How to use React Query?",
  //   tags: [
  //     {
  //       _id: 1,
  //       name: "react",
  //     },
  //     {
  //       _id: 2,
  //       name: "react-query",
  //     },
  //   ],
  //   author: "John Doe",
  //   upVotes: 10,
  //   views: 100,
  //   answers: 2,
  //   createdAt: "2021-09-01T12:00:00.000Z",
  // },
  // {
  //   _id: 2,
  //   title: "How to use add a new route in Next.js?",
  //   tags: [
  //     {
  //       _id: 1,
  //       name: "next.js",
  //     },
  //     {
  //       _id: 2,
  //       name: "react",
  //     },
  //   ],
  //   author: "John Doe",
  //   upVotes: 10,
  //   views: 100,
  //   answers: 2,
  //   createdAt: "2021-09-01T12:00:00.000Z",
  // },
];

export default function Home() {
  return (
    <>
      <div className="flex w-full flex-col-reverse justify-between gap-4 sm:flex-row sm:items-center">
        <h1 className={"h1-bold text-dark100_light900"}>All Questions</h1>
        <Link
          href={"/ask-question"}
          className={"flex justify-end max-sm:w-full"}
        >
          <Button
            className={
              "primary-gradient min-h-[46px] px-4 py-3 !text-light-900"
            }
          >
            Ask Question
          </Button>
        </Link>
      </div>
      <div className="mt-11 flex justify-between gap-5 max-sm:flex-col sm:items-center">
        <LocalSearch
          imageSrc={"/assets/icons/search.svg"}
          route={"/"}
          iconPosition={"left"}
          placeholder={"Search Questions ..."}
          otherClasses={"flex-1"}
        />
        <Filter
          filters={HOME_PAGE_FILTERS}
          otherClasses={"min-h-[56px] sm:min-w-[170px]"}
          containerClasses={"hidden max-md:flex"}
        />
      </div>
      <HomeFilter />
      <div className="mt-10 flex w-full flex-col gap-6">
        {questions.length > 0 ? (
          questions.map(
            (question) =>
              // <QuestionCard key={question._id} question={question} />
              " Question card",
          )
        ) : (
          <NoResult
            title={"There is no questions to show"}
            description={
              "  It appears that there are no saved questions in your collection at the\n" +
              "        moment 😔.Start exploring and saving questions that pique your interest\n" +
              "        🌟"
            }
            LinkHref={"/ask-question"}
            LinkText={"Ask a Question"}
          />
        )}
      </div>
    </>
  );
}
```

No Result component

```tsx
import Image from "next/image";
import Link from "next/link";
import { Button } from "@/components/ui/button";
import { FC } from "react";

type TNoResultProps = {
  title: string;
  description: string;
  LinkText: string;
  LinkHref: string;
};

const NoResult: FC<TNoResultProps> = ({
  LinkHref,
  LinkText,
  title,
  description,
}) => {
  return (
    <div className="mt-10 flex w-full flex-col items-center justify-center">
      <Image
        src={"/assets/images/light-illustration.png"}
        alt={"no result"}
        width={270}
        height={200}
        className={"block object-contain dark:hidden"}
      />
      <Image
        src={"/assets/images/dark-illustration.png"}
        alt={"no result"}
        width={270}
        height={200}
        className={"hidden object-contain dark:flex"}
      />
      <h2 className={"h2-bold text-dark200_light900 mt-8"}>{title}</h2>
      <p
        className={
          "body-regular text-dark500_light700 my-3.5 max-w-md text-center"
        }
      >
        {description}
      </p>
      <Link href={LinkHref}>
        <Button
          className={
            "paragraph-medium mt-5 min-h-[46px] rounded-lg bg-primary-500 px-4 py-3 text-light-900 "
          }
        >
          {LinkText}
        </Button>
      </Link>
    </div>
  );
};

export default NoResult;
```
![Alt text](image-128.png)

![Alt text](image-129.png)

let's build the question card


types
```ts

export type TTag = {
  _id: number;
  name: string;
};

export type TAuthor = {
  _id: number;
  name: string;
  picture: string;
};

export type TQuestion = {
  _id: number;
  title: string;
  tags: TTag[];
  author: TAuthor;
  upVotes: number | string;
  views: number;
  answers: number;
  createdAt: Date;
};

```

Page Component
```tsx
import Link from "next/link";
import { Button } from "@/components/ui/button";
import LocalSearch from "@/components/shared/search/LocalSearch";
import Filter from "@/components/shared/filters/Filter";
import { HOME_PAGE_FILTERS } from "@/CONSTANTS/filters";
import HomeFilter from "@/components/home/HomeFilter";
import NoResult from "@/components/shared/noResult/NoResult";
import { TQuestion } from "@/types/types";
import QuestionCard from "@/components/cards/QuestionCard";

const questions: TQuestion[] = [
  {
    _id: 1,
    title: "How to use React Query?",
    tags: [
      {
        _id: 1,
        name: "react",
      },
      {
        _id: 2,
        name: "react-query",
      },
    ],
    author: {
      _id: 1,
      name: "John Doe",
      picture: "/assets/icons/avatar.svg",
    },
    upVotes: 1000000,
    views: 4000000,
    answers: 12222222,
    createdAt: new Date("2021-09-01T12:00:00.000Z"),
  },
  {
    _id: 2,
    title: "How to use add a new route in Next.js?",
    tags: [
      {
        _id: 1,
        name: "next.js",
      },
      {
        _id: 2,
        name: "react",
      },
    ],
    author: {
      _id: 1,
      name: "John Doe",
      picture: "/assets/icons/avatar.svg",
    },
    upVotes: 10,
    views: 100,
    answers: 2,
    createdAt: new Date("2023-09-01T12:00:00.000Z"),
  },
];

export default function Home() {
  return (
    <>
      <div className="flex w-full flex-col-reverse justify-between gap-4 sm:flex-row sm:items-center">
        <h1 className={"h1-bold text-dark100_light900"}>All Questions</h1>
        <Link
          href={"/ask-question"}
          className={"flex justify-end max-sm:w-full"}
        >
          <Button
            className={
              "primary-gradient min-h-[46px] px-4 py-3 !text-light-900"
            }
          >
            Ask Question
          </Button>
        </Link>
      </div>
      <div className="mt-11 flex justify-between gap-5 max-sm:flex-col sm:items-center">
        <LocalSearch
          imageSrc={"/assets/icons/search.svg"}
          route={"/"}
          iconPosition={"left"}
          placeholder={"Search Questions ..."}
          otherClasses={"flex-1"}
        />
        <Filter
          filters={HOME_PAGE_FILTERS}
          otherClasses={"min-h-[56px] sm:min-w-[170px]"}
          containerClasses={"hidden max-md:flex"}
        />
      </div>
      <HomeFilter />
      <div className="mt-10 flex w-full flex-col gap-6">
        {questions.length > 0 ? (
          questions.map((question) => (
            // <QuestionCard key={question._id} question={question} />
            <QuestionCard key={question._id} question={question} />
          ))
        ) : (
          <NoResult
            title={"There is no questions to show"}
            description={
              "  It appears that there are no saved questions in your collection at the\n" +
              "        moment 😔.Start exploring and saving questions that pique your interest\n" +
              "        🌟"
            }
            LinkHref={"/ask-question"}
            LinkText={"Ask a Question"}
          />
        )}
      </div>
    </>
  );
}

```

Question Card
```tsx
import { FC } from "react";
import { TQuestion } from "@/types/types";
import Link from "next/link";
import RenderTags from "@/components/shared/tags/RenderTags";
import Metric from "@/components/shared/metric/Metric";
import { getTimStamp } from "@/lib/utils";

export type TQuestionCardProps = {
  question: TQuestion;
};

const QuestionCard: FC<TQuestionCardProps> = ({
  question: { _id, author, tags, title, upVotes, views, createdAt, answers },
}) => {
  return (
    <div
      className={
        "card-wrapper rounded-[10px] border-2 p-9 dark:border-none sm:px-11"
      }
    >
      <div className="flex flex-col-reverse items-start justify-between gap-5 sm:flex-row">
        <div className=" ">
          <span className="subtle-regular text-dark400_light700 line-clamp-1 flex sm:hidden">
            {getTimStamp(createdAt)}
          </span>
          <Link href={`/question/${_id}`}>
            <h3
              className={
                "sm:h3-semibold base-semibold text-dark200_light900 line-clamp-1 flex-1"
              }
            >
              {title}
            </h3>
          </Link>
        </div>
        {/*  if signed in add edit delete actions */}
      </div>
      <div className="mt-3.5 flex flex-wrap gap-2">
        {tags.map((tag) => (
          <RenderTags key={tag._id} _id={tag._id} name={tag.name} />
        ))}
      </div>
      <div className="flex-between mt-6 flex w-full flex-wrap gap-3">
        <Metric
          imageUrl={author.picture}
          alt={"user"}
          value={author.name}
          title={` - asked ${getTimStamp(createdAt)}`}
          textStyles={"text-dark400_light700 body-medium"}
          href={`/profile/${author._id}`}
          isAuthor={true}
        />
        <Metric
          imageUrl={"/assets/icons/like.svg"}
          alt={"message"}
          value={upVotes}
          title={" Votes"}
          textStyles={"text-dark400_light800 small-medium"}
        />
        <Metric
          imageUrl={"/assets/icons/message.svg"}
          alt={"Upvotes"}
          value={answers}
          title={" Answers"}
          textStyles={"text-dark400_light800 small-medium"}
        />
        <Metric
          imageUrl={"/assets/icons/eye.svg"}
          alt={"eye"}
          value={views}
          title={" Views"}
          textStyles={"text-dark400_light800 small-medium"}
        />
      </div>
    </div>
  );
};
export default QuestionCard;

```
Metric Card
```tsx
import { FC } from "react";
import Image from "next/image";
import Link from "next/link";
import { formatNumber } from "@/lib/utils";

type TMetricProps = {
  imageUrl: string;
  alt: string;
  value: number | string;
  title: string;
  textStyles?: string;
  isAuthor?: boolean;
  href?: string;
};
const Metric: FC<TMetricProps> = ({
  textStyles,
  title,
  imageUrl,
  value,
  alt,
  isAuthor,
  href,
}) => {
  const metric = (
    <>
      <Image
        src={imageUrl}
        alt={alt}
        height={16}
        width={16}
        className={`object-contain ${href ? "rounded-full" : ""}`}
      />
      <p className={`${textStyles} flex items-center gap-1`}>
        {typeof value === "number" ? formatNumber(value) : value}
        <span
          className={`small-regular line-clamp-1 ${
            isAuthor ? "max-sm:hidden" : ""
          }`}
        >
          {title}
        </span>
      </p>
    </>
  );
  if (href) {
    return (
      <Link href={href} className={"flex-center gap-1"}>
        {metric}
      </Link>
    );
  }
  return <div className={"flex-center flex-wrap gap-1"}>{metric}</div>;
};

export default Metric;

```

Util function

```ts
import { type ClassValue, clsx } from "clsx";
import { twMerge } from "tailwind-merge";

export function cn(...inputs: ClassValue[]) {
  return twMerge(clsx(inputs));
}

export const getTimStamp = (date: Date): string => {
  const today = new Date();
  const seconds = Math.round((today.getTime() - date.getTime()) / 1000);
  const minutes = Math.round(seconds / 60);
  const hours = Math.round(minutes / 60);
  const days = Math.round(hours / 24);
  const weeks = Math.round(days / 7);
  const months = Math.round(days / 30);
  const years = Math.round(days / 365);

  if (seconds < 60) {
    return `${seconds} seconds ago`;
  } else if (minutes < 60) {
    return `${minutes} minutes ago`;
  } else if (hours < 24) {
    return `${hours} hours ago`;
  } else if (days < 7) {
    return `${days} days ago`;
  } else if (weeks < 4) {
    return `${weeks} weeks ago`;
  } else if (months < 12) {
    return `${months} months ago`;
  } else {
    return `${years} years ago`;
  }
};

export function formatNumber(num: number) {
  if (num >= 1e12) {
    return (num / 1e12).toFixed(1) + "T";
  } else if (num >= 1e9) {
    return (num / 1e9).toFixed(1) + "B";
  } else if (num >= 1e6) {
    return (num / 1e6).toFixed(1) + "M";
  } else if (num >= 1e3) {
    return (num / 1e3).toFixed(1) + "K";
  } else {
    return num.toString();
  }
}

```
output

![Alt text](image-130.png)

![Alt text](image-131.png)

## Ask a Question Page ✅
### Question Form and Validations ✅
let's install shadcn form component 
```shell
npx shadcn-ui@latest add form
```

and follow the docs https://ui.shadcn.com/docs/components/form
![Alt text](image-132.png)

in the asked question section
```shell
import Question from "@/components/forms/Question";

const AskQuestionPage = () => {
  return (
    <div>
      <h1 className="h1-bold text-dark100_light900">Ask a question</h1>
      <div className="mt-9">
        <Question />
      </div>
    </div>
  );
};

export default AskQuestionPage;

```

let's create a Question component
```tsx
"use client";
import { FC } from "react";
import { zodResolver } from "@hookform/resolvers/zod";
import { useForm } from "react-hook-form";
import { Button } from "@/components/ui/button";
import {
  Form,
  FormControl,
  FormDescription,
  FormField,
  FormItem,
  FormLabel,
  FormMessage,
} from "@/components/ui/form";
import { Input } from "@/components/ui/input";
import { QuestionsSchema, TQuestionsSchema } from "@/lib/validations";

type TQuestionProps = {};

const Question: FC<TQuestionProps> = () => {
  const form = useForm<TQuestionsSchema>({
    resolver: zodResolver(QuestionsSchema),
    defaultValues: {
      title: "",
      explanation: "",
      tags: [],
    },
  });

  // 2. Define a submit handler.
  function onSubmit(values: TQuestionsSchema) {
    // Do something with the form values.
    // ✅ This will be type-safe and validated.
    console.log(values);
  }
  return (
    <Form {...form}>
      <form
        onSubmit={form.handleSubmit(onSubmit)}
        className="flex w-full flex-col gap-10"
      >
        <FormField
          control={form.control}
          name="title"
          render={({ field }) => (
            <FormItem className={"flex w-full flex-col"}>
              <FormLabel
                className={"paragraph-semibold text-dark400_light800 "}
              >
                Question Title <span className={"text-primary-500"}>*</span>
              </FormLabel>
              <FormControl className={"mt-3.5"}>
                <Input
                  className={
                    "no-focus paragraph-regular background-light900_dark300 light-border-2 text-dark300_light700 min-h-[56px] border"
                  }
                  {...field}
                />
              </FormControl>
              <FormDescription className={"body-regular mt-2.5 text-light-500"}>
                Be specific and imagine you’re asking a question from another
                person
              </FormDescription>
              <FormMessage className={"text-red-500"} />
            </FormItem>
          )}
        />

        <FormField
          control={form.control}
          name="explanation"
          render={({ field }) => (
            <FormItem className={"flex w-full flex-col gap-3"}>
              <FormLabel
                className={"paragraph-semibold text-dark400_light800 "}
              >
                Detail explanation of your problem
                <span className={"text-primary-500"}>*</span>
              </FormLabel>
              <FormControl className={"mt-3.5"}>{/*  TODO */}</FormControl>
              <FormDescription className={"body-regular mt-2.5 text-light-500"}>
                Introduce the problem and expand on what you want to put in the
                title Minimum 20 characters
              </FormDescription>
              <FormMessage className={"text-red-500"} />
            </FormItem>
          )}
        />

        <FormField
          control={form.control}
          name="tags"
          render={({ field }) => (
            <FormItem className={"flex w-full flex-col"}>
              <FormLabel
                className={"paragraph-semibold text-dark400_light800 "}
              >
                Question Title <span className={"text-primary-500"}>*</span>
              </FormLabel>
              <FormControl className={"mt-3.5"}>
                <Input
                  className={
                    "no-focus paragraph-regular background-light900_dark300 light-border-2 text-dark300_light700 min-h-[56px] border"
                  }
                  placeholder={'Add tags (e.g. "javascript" "react")'}
                  {...field}
                />
              </FormControl>
              <FormDescription className={"body-regular mt-2.5 text-light-500"}>
                Add up to 3 tags to describe what your question is about. You
                need to press enter to add a tag.
              </FormDescription>
              <FormMessage className={"text-red-500"} />
            </FormItem>
          )}
        />

        <Button type="submit">Submit</Button>
      </form>
    </Form>
  );
};

export default Question;
```

let's add the zod validation schema
```ts
import * as z from "zod";

export const QuestionsSchema = z.object({
  title: z
    .string()
    .min(5, {
      message: "UserName must be at least 5 characters",
    })
    .max(130, {
      message: "UserName can't be more than 130 characters",
    }),
  explanation: z.string().min(100),
  tags: z
    .array(
      z
        .string()
        .min(1, "tag must be at least 1 character")
        .max(15, "cannot have more than 15 characters"),
    )
    .min(1, "must have at least 1 tag")
    .max(3, "cannot have more than 3 tags"),
});

export type TQuestionsSchema = z.infer<typeof QuestionsSchema>;
```

![Alt text](image-133.png)
![Alt text](image-134.png)
### The Question Editor ✅
![Alt text](image-135.png)
setup tiny -> https://www.tiny.cloud/my-account/integrate/

install tiny editor
![Alt text](image-136.png)


adding tiny editor to the question form
```tsx
"use client";
import React, { FC, useRef } from "react";
import { zodResolver } from "@hookform/resolvers/zod";
import { useForm } from "react-hook-form";
import { Button } from "@/components/ui/button";
import {
  Form,
  FormControl,
  FormDescription,
  FormField,
  FormItem,
  FormLabel,
  FormMessage,
} from "@/components/ui/form";
import { Input } from "@/components/ui/input";
import { QuestionsSchema, TQuestionsSchema } from "@/lib/validations";
import { Editor } from "@tinymce/tinymce-react";

type TQuestionProps = {};

const Question: FC<TQuestionProps> = () => {
  const editorRef = useRef(null);
  const form = useForm<TQuestionsSchema>({
    resolver: zodResolver(QuestionsSchema),
    defaultValues: {
      title: "",
      explanation: "",
      tags: [],
    },
  });
  // const log = () => {
  //   if (editorRef.current) {
  //     console.log(editorRef.current.getContent());
  //   }
  // };
  // 2. Define a submit handler.
  function onSubmit(values: TQuestionsSchema) {
    // Do something with the form values.
    // ✅ This will be type-safe and validated.
    console.log(values);
  }
  // @ts-ignore
  return (
    <Form {...form}>
      <form
        onSubmit={form.handleSubmit(onSubmit)}
        className="flex w-full flex-col gap-10"
      >
        <FormField
          control={form.control}
          name="title"
          render={({ field }) => (
            <FormItem className={"flex w-full flex-col"}>
              <FormLabel
                className={"paragraph-semibold text-dark400_light800 "}
              >
                Question Title <span className={"text-primary-500"}>*</span>
              </FormLabel>
              <FormControl className={"mt-3.5"}>
                <Input
                  className={
                    "no-focus paragraph-regular background-light900_dark300 light-border-2 text-dark300_light700 min-h-[56px] border"
                  }
                  {...field}
                />
              </FormControl>
              <FormDescription className={"body-regular mt-2.5 text-light-500"}>
                Be specific and imagine you’re asking a question from another
                person
              </FormDescription>
              <FormMessage className={"text-red-500"} />
            </FormItem>
          )}
        />

        <FormField
          control={form.control}
          name="explanation"
          render={({ field }) => (
            <FormItem className={"flex w-full flex-col gap-3"}>
              <FormLabel
                className={"paragraph-semibold text-dark400_light800 "}
              >
                Detail explanation of your problem
                <span className={"text-primary-500"}>*</span>
              </FormLabel>
              <FormControl className={"mt-3.5"}>
                <Editor
                  apiKey={process.env.NEXT_PUBLIC_TINY_API_KEY}
                  onInit={(evt, editor) => {
                    // @ts-ignore
                    editorRef.current = editor;
                  }}
                  initialValue=""
                  init={{
                    height: 350,
                    menubar: false,
                    plugins: [
                      "advlist",
                      "autolink",
                      "lists",
                      "link image",
                      "charmap",
                      "preview anchor",
                      "searchreplace",
                      "visualblocks",
                      "codesample",
                      "fullscreen",
                      "insertdatetime",
                      "media",
                      "table",
                    ],
                    toolbar:
                      "undo redo | codesample | " +
                      "bold italic forecolor | alignleft aligncenter " +
                      "alignright alignjustify | bullist numlist",
                    content_style: "body { font-family:Inter; font-size:16px }",
                  }}
                />
              </FormControl>
              <FormDescription className={"body-regular mt-2.5 text-light-500"}>
                Introduce the problem and expand on what you want to put in the
                title Minimum 20 characters
              </FormDescription>
              <FormMessage className={"text-red-500"} />
            </FormItem>
          )}
        />

        <FormField
          control={form.control}
          name="tags"
          render={({ field }) => (
            <FormItem className={"flex w-full flex-col"}>
              <FormLabel
                className={"paragraph-semibold text-dark400_light800 "}
              >
                Question Title <span className={"text-primary-500"}>*</span>
              </FormLabel>
              <FormControl className={"mt-3.5"}>
                <Input
                  className={
                    "no-focus paragraph-regular background-light900_dark300 light-border-2 text-dark300_light700 min-h-[56px] border"
                  }
                  placeholder={'Add tags (e.g. "javascript" "react")'}
                  {...field}
                />
              </FormControl>
              <FormDescription className={"body-regular mt-2.5 text-light-500"}>
                Add up to 3 tags to describe what your question is about. You
                need to press enter to add a tag.
              </FormDescription>
              <FormMessage className={"text-red-500"} />
            </FormItem>
          )}
        />

        <Button type="submit">Submit</Button>
      </form>
    </Form>
  );
};

export default Question;
```
### Custom Multiple Tags Input ✅
```tsx
"use client";
import React, { FC, KeyboardEvent, useRef, useState } from "react";
import { zodResolver } from "@hookform/resolvers/zod";
import { ControllerRenderProps, useForm } from "react-hook-form";
import { Button } from "@/components/ui/button";
import {
  Form,
  FormControl,
  FormDescription,
  FormField,
  FormItem,
  FormLabel,
  FormMessage,
} from "@/components/ui/form";
import { Input } from "@/components/ui/input";
import { QuestionsSchema, TQuestionsSchema } from "@/lib/validations";
import { Editor } from "@tinymce/tinymce-react";
import { Badge } from "@/components/ui/badge";
import Image from "next/image";

type TQuestionProps = {};

const Question: FC<TQuestionProps> = () => {
  const editorRef = useRef(null);
  const form = useForm<TQuestionsSchema>({
    resolver: zodResolver(QuestionsSchema),
    defaultValues: {
      title: "",
      explanation: "",
      tags: [],
    },
  });
  // const log = () => {
  //   if (editorRef.current) {
  //     console.log(editorRef.current.getContent());
  //   }
  // };
  // 2. Define a submit handler.
  function onSubmit(values: TQuestionsSchema) {
    // Do something with the form values.
    // ✅ This will be type-safe and validated.
    console.log(values);
  }

  const handleInputKeyDown = (
    event: KeyboardEvent<HTMLInputElement>,
    field: ControllerRenderProps<TQuestionsSchema, "tags">,
  ) => {
    if (event.key === "Enter" && field.name === "tags") {
      event.preventDefault();
      const tagInput = event.target as HTMLInputElement;
      const value = tagInput.value.trim();

      if (value !== "") {
        if (value.length > 15) {
          return form.setError("tags", {
            type: "maxLength",
            message: "Tag length must be less than 15 characters",
          });
        }
        if (!field.value.includes(value as never)) {
          form.setValue("tags", [...field.value, value]);
          tagInput.value = "";
          form.clearErrors("tags");
        }
      } else {
        form.trigger("tags");
      }
    }
  };
  const handleTagRemove = (
    tag: string,
    field: ControllerRenderProps<TQuestionsSchema, "tags">,
  ) => {
    const newTags = field.value.filter((t) => t !== tag);
    form.setValue("tags", newTags);
  };

  return (
    <Form {...form}>
      <form
        onSubmit={form.handleSubmit(onSubmit)}
        className="flex w-full flex-col gap-10"
      >
        <FormField
          control={form.control}
          name="title"
          render={({ field }) => (
            <FormItem className={"flex w-full flex-col"}>
              <FormLabel
                className={"paragraph-semibold text-dark400_light800 "}
              >
                Question Title <span className={"text-primary-500"}>*</span>
              </FormLabel>
              <FormControl className={"mt-3.5"}>
                <Input
                  className={
                    "no-focus paragraph-regular background-light900_dark300 light-border-2 text-dark300_light700 min-h-[56px] border"
                  }
                  {...field}
                />
              </FormControl>
              <FormDescription className={"body-regular mt-2.5 text-light-500"}>
                Be specific and imagine you’re asking a question from another
                person
              </FormDescription>
              <FormMessage className={"text-red-500"} />
            </FormItem>
          )}
        />

        <FormField
          control={form.control}
          name="explanation"
          render={({ field }) => (
            <FormItem className={"flex w-full flex-col gap-3"}>
              <FormLabel
                className={"paragraph-semibold text-dark400_light800 "}
              >
                Detail explanation of your problem
                <span className={"text-primary-500"}>*</span>
              </FormLabel>
              <FormControl className={"mt-3.5"}>
                <Editor
                  apiKey={process.env.NEXT_PUBLIC_TINY_API_KEY}
                  onInit={(evt, editor) => {
                    // @ts-ignore
                    editorRef.current = editor;
                  }}
                  initialValue=""
                  init={{
                    height: 350,
                    menubar: false,
                    plugins: [
                      "advlist",
                      "autolink",
                      "lists",
                      "link image",
                      "charmap",
                      "preview anchor",
                      "searchreplace",
                      "visualblocks",
                      "codesample",
                      "fullscreen",
                      "insertdatetime",
                      "media",
                      "table",
                    ],
                    toolbar:
                      "undo redo | codesample | " +
                      "bold italic forecolor | alignleft aligncenter " +
                      "alignright alignjustify | bullist numlist",
                    content_style: "body { font-family:Inter; font-size:16px }",
                  }}
                />
              </FormControl>
              <FormDescription className={"body-regular mt-2.5 text-light-500"}>
                Introduce the problem and expand on what you want to put in the
                title Minimum 20 characters
              </FormDescription>
              <FormMessage className={"text-red-500"} />
            </FormItem>
          )}
        />

        <FormField
          control={form.control}
          name="tags"
          render={({ field }) => (
            <FormItem className={"flex w-full flex-col"}>
              <FormLabel
                className={"paragraph-semibold text-dark400_light800 "}
              >
                Question Title <span className={"text-primary-500"}>*</span>
              </FormLabel>
              <FormControl className={"mt-3.5"}>
                <>
                  <Input
                    className={
                      "no-focus paragraph-regular background-light900_dark300 light-border-2 text-dark300_light700 min-h-[56px] border"
                    }
                    placeholder={'Add tags (e.g. "javascript" "react")'}
                    onKeyDown={(e) => handleInputKeyDown(e, field)}
                  />
                  {field.value.length > 0 && (
                    <div className={"flex-start mt-2.5 gap-2.5"}>
                      {field.value.map((tag) => {
                        return (
                          <Badge
                            key={tag}
                            className={
                              "subtle-medium background-light800_dark300 text-dark400_light500 flex items-center justify-center gap-2 rounded-md border-none px-4 py-2 capitalize"
                            }
                            onClick={() => handleTagRemove(tag, field)}
                          >
                            {tag}
                            <Image
                              src={"/assets/icons/close.svg"}
                              alt={"close icons"}
                              width={16}
                              height={16}
                              className={
                                "cursor-pointer object-contain invert-0 dark:invert"
                              }
                            />
                          </Badge>
                        );
                      })}
                    </div>
                  )}
                </>
              </FormControl>
              <FormDescription className={"body-regular mt-2.5 text-light-500"}>
                Add up to 3 tags to describe what your question is about. You
                need to press enter to add a tag.
              </FormDescription>
              <FormMessage className={"text-red-500"} />
            </FormItem>
          )}
        />

        <Button type="submit">Submit</Button>
      </form>
    </Form>
  );
};

export default Question;

```
### Making the Form Reusable ✅
adding the form 
```tsx
"use client";
import React, { FC, KeyboardEvent, useRef, useState } from "react";
import { zodResolver } from "@hookform/resolvers/zod";
import { ControllerRenderProps, useForm } from "react-hook-form";
import { Button } from "@/components/ui/button";
import {
  Form,
  FormControl,
  FormDescription,
  FormField,
  FormItem,
  FormLabel,
  FormMessage,
} from "@/components/ui/form";
import { Input } from "@/components/ui/input";
import { QuestionsSchema, TQuestionsSchema } from "@/lib/validations";
import { Editor } from "@tinymce/tinymce-react";
import { Badge } from "@/components/ui/badge";
import Image from "next/image";

type TQuestionProps = {};

const formType = "edit";

const Question: FC<TQuestionProps> = () => {
  const [isFormSubmitting, setIsFormSubmitting] = useState(false);
  const editorRef = useRef(null);
  const form = useForm<TQuestionsSchema>({
    resolver: zodResolver(QuestionsSchema),
    defaultValues: {
      title: "",
      explanation: "",
      tags: [],
    },
  });
  // const log = () => {
  //   if (editorRef.current) {
  //     console.log(editorRef.current.getContent());
  //   }
  // };
  // 2. Define a submit handler.
  function onSubmit(values: TQuestionsSchema) {
    setIsFormSubmitting(true);

    try {
    } catch (error) {
    } finally {
      setIsFormSubmitting(false);
    }
  }

  const handleInputKeyDown = (
    event: KeyboardEvent<HTMLInputElement>,
    field: ControllerRenderProps<TQuestionsSchema, "tags">,
  ) => {
    if (event.key === "Enter" && field.name === "tags") {
      event.preventDefault();
      const tagInput = event.target as HTMLInputElement;
      const value = tagInput.value.trim();

      if (value !== "") {
        if (value.length > 15) {
          return form.setError("tags", {
            type: "maxLength",
            message: "Tag length must be less than 15 characters",
          });
        }
        if (!field.value.includes(value as never)) {
          form.setValue("tags", [...field.value, value]);
          tagInput.value = "";
          form.clearErrors("tags");
        }
      } else {
        form.trigger("tags");
      }
    }
  };
  const handleTagRemove = (
    tag: string,
    field: ControllerRenderProps<TQuestionsSchema, "tags">,
  ) => {
    const newTags = field.value.filter((t) => t !== tag);
    form.setValue("tags", newTags);
  };

  return (
    <Form {...form}>
      <form
        onSubmit={form.handleSubmit(onSubmit)}
        className="flex w-full flex-col gap-10"
      >
        <FormField
          control={form.control}
          name="title"
          render={({ field }) => (
            <FormItem className={"flex w-full flex-col"}>
              <FormLabel
                className={"paragraph-semibold text-dark400_light800 "}
              >
                Question Title <span className={"text-primary-500"}>*</span>
              </FormLabel>
              <FormControl className={"mt-3.5"}>
                <Input
                  className={
                    "no-focus paragraph-regular background-light900_dark300 light-border-2 text-dark300_light700 min-h-[56px] border"
                  }
                  {...field}
                />
              </FormControl>
              <FormDescription className={"body-regular mt-2.5 text-light-500"}>
                Be specific and imagine you’re asking a question from another
                person
              </FormDescription>
              <FormMessage
                className={
                  "rounded bg-red-500/10 py-2 text-center text-red-500"
                }
              />
            </FormItem>
          )}
        />

        <FormField
          control={form.control}
          name="explanation"
          render={({ field }) => (
            <FormItem className={"flex w-full flex-col gap-3"}>
              <FormLabel
                className={"paragraph-semibold text-dark400_light800 "}
              >
                Detail explanation of your problem
                <span className={"text-primary-500"}>*</span>
              </FormLabel>
              <FormControl className={"mt-3.5"}>
                <Editor
                  apiKey={process.env.NEXT_PUBLIC_TINY_API_KEY}
                  onInit={(evt, editor) => {
                    // @ts-ignore
                    editorRef.current = editor;
                  }}
                  initialValue=""
                  init={{
                    height: 350,
                    menubar: false,
                    plugins: [
                      "advlist",
                      "autolink",
                      "lists",
                      "link image",
                      "charmap",
                      "preview anchor",
                      "searchreplace",
                      "visualblocks",
                      "codesample",
                      "fullscreen",
                      "insertdatetime",
                      "media",
                      "table",
                    ],
                    toolbar:
                      "undo redo | codesample | " +
                      "bold italic forecolor | alignleft aligncenter " +
                      "alignright alignjustify | bullist numlist",
                    content_style: "body { font-family:Inter; font-size:16px }",
                  }}
                />
              </FormControl>
              <FormDescription className={"body-regular mt-2.5 text-light-500"}>
                Introduce the problem and expand on what you want to put in the
                title Minimum 20 characters
              </FormDescription>
              <FormMessage
                className={
                  "rounded bg-red-500/10 py-2 text-center text-red-500"
                }
              />
            </FormItem>
          )}
        />

        <FormField
          control={form.control}
          name="tags"
          render={({ field }) => (
            <FormItem className={"flex w-full flex-col"}>
              <FormLabel
                className={"paragraph-semibold text-dark400_light800 "}
              >
                Question Title <span className={"text-primary-500"}>*</span>
              </FormLabel>
              <FormControl className={"mt-3.5"}>
                <>
                  <Input
                    className={
                      "no-focus paragraph-regular background-light900_dark300 light-border-2 text-dark300_light700 min-h-[56px] border"
                    }
                    placeholder={'Add tags (e.g. "javascript" "react")'}
                    onKeyDown={(e) => handleInputKeyDown(e, field)}
                  />
                  {field.value.length > 0 && (
                    <div className={"flex-start mt-2.5 gap-2.5"}>
                      {field.value.map((tag) => {
                        return (
                          <Badge
                            key={tag}
                            className={
                              "subtle-medium background-light800_dark300 text-dark400_light500 flex items-center justify-center gap-2 rounded-md border-none px-4 py-2 capitalize"
                            }
                            onClick={() => handleTagRemove(tag, field)}
                          >
                            {tag}
                            <Image
                              src={"/assets/icons/close.svg"}
                              alt={"close icons"}
                              width={16}
                              height={16}
                              className={
                                "cursor-pointer object-contain invert-0 dark:invert"
                              }
                            />
                          </Badge>
                        );
                      })}
                    </div>
                  )}
                </>
              </FormControl>
              <FormDescription className={"body-regular mt-2.5 text-light-500"}>
                Add up to 3 tags to describe what your question is about. You
                need to press enter to add a tag.
              </FormDescription>
              <FormMessage
                className={
                  "rounded bg-red-500/10 py-2 text-center text-red-500"
                }
              />
            </FormItem>
          )}
        />

        <Button
          className={"primary-gradient w-fit text-light-900"}
          type="submit"
          disabled={isFormSubmitting}
        >
          {isFormSubmitting ? (
            <> {formType === "edit" ? "Editing..." : "Posting..."}</>
          ) : (
            <>{formType === "edit" ? "Edit Question" : "Ask a Question"}</>
          )}
        </Button>
      </form>
    </Form>
  );
};

export default Question;
```

output

![Alt text](image-137.png)

![Alt text](image-138.png)


## Develop Backend 🔲
### Thinking in Backend ✅
typical app vs nextjs app

![Alt text](image-139.png)

we can use 

![Alt text](image-140.png)

One of the most exciting features is the introduction of Server Actions or Server Functions. Just like the word says, Server Actions are functions that run on the server, but that we can call from the client, just like a normal function. This is a huge step forward for Next.js, as it allows us to run code on the server without having to create an API endpoint. This is a whole new DX for Next.js developers, and it's going to be a game changer.

#### What can I do with Next.js Server Actions?

Server Actions are a very powerful feature, and they can be used for a lot of different use cases. Here are a few examples:

- writing to a database: you can write to a database directly from the client, without having to create an API endpoint - just by defining your logic in a server action.
- server logic: executing any server-related business logic, such as sending emails, creating files, etc.
- calling external APIs: you can call external APIs directly from server actions, without having to create an API endpoint

In summary, you can do anything you would normally do on the server, but without having to create an API endpoint.

let's configure next config
```ts
/** @type {import('next').NextConfig} */
const nextConfig = {
  experimental: {
    serverActions: true,
    mdxRs: true,
    serverComponentsExternalPackages: ["mongoose"],
  },
};

module.exports = nextConfig;
```

let's create a question server action

![Alt text](image-141.png)

```ts
"use server";

export async function createQuestion(params: any) {
  try {
  } catch (e) {}
}
```
### MongoDB and Server Actions Setup 🔲
### Creating Question Model 🔲
### Creating a User Model 🔲
### Creating a Tag Model 🔲
## Create a Question 🔲
## Fetching Questions on the Home Page 🔲
## The Webhooks 🔲
## Community Page 🔲
## Tags Page 🔲
## Question Details 🔲
## Voting 🔲
## Collections Page 🔲
## Views 🔲
## Tag Details Page 🔲
## Profile Page 🔲
## Edit_Delete User Actions 🔲
## Show Top Results 🔲
## The Local Search Functionality 🔲
## The Filters 🔲
## The Pagination 🔲
## Global Search 🔲
## Reputation 🔲
## Badge System 🔲
## Generate AI Answer 🔲
## Loadings _ Toasts 🔲
## Meta Data 🔲
## Bug Fixing and Recommendation 🔲
## Next.js 13.5+ 🔲
## Deployment 🔲
### 
### 
### 
### 
### 
### 
### 