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
  - [Develop Backend ✅](#develop-backend-)
    - [Thinking in Backend ✅](#thinking-in-backend-)
      - [What can I do with Next.js Server Actions?](#what-can-i-do-with-nextjs-server-actions)
    - [MongoDB and Server Actions Setup ✅](#mongodb-and-server-actions-setup-)
    - [Creating Question Model 🔲](#creating-question-model-)
    - [Creating a User Model ✅](#creating-a-user-model-)
    - [Creating a Tag Model ✅](#creating-a-tag-model-)
  - [Create a Question ✅](#create-a-question-)
  - [Fetching Questions on the Home Page ✅](#fetching-questions-on-the-home-page-)
  - [The Webhooks ✅](#the-webhooks-)
    - [Why \_ what are Webhooks ✅](#why-_-what-are-webhooks-)
    - [Implement Webhooks and User Actions ✅](#implement-webhooks-and-user-actions-)
    - [Deploy Webhooks ✅](#deploy-webhooks-)
  - [Community Page ✅](#community-page-)
    - [Create Community Page ✅](#create-community-page-)
  - [Tags Page ✅](#tags-page-)
    - [Create Tags Page ✅](#create-tags-page-)
  - [Question Details Page ✅](#question-details-page-)
    - [Create Question Details Page ✅](#create-question-details-page-)
    - [Parse \_ display Question Content ✅](#parse-_-display-question-content-)
    - [Create Answer Form ✅](#create-answer-form-)
    - [Create Answer Model ✅](#create-answer-model-)
    - [Implement Create Answer action ✅](#implement-create-answer-action-)
    - [Integrate Create Answer action inside Answer Form](#integrate-create-answer-action-inside-answer-form)
    - [Display All Answers ✅](#display-all-answers-)
  - [Voting ✅](#voting-)
    - [Create Votes UI ✅](#create-votes-ui-)
    - [Create Upvote-DownVote actions for Question ✅](#create-upvote-downvote-actions-for-question-)
    - [Integrate Question upvote-downvote actions on UI ✅](#integrate-question-upvote-downvote-actions-on-ui-)
    - [Create Answer Voting ✅](#create-answer-voting-)
  - [Collections Page ✅](#collections-page-)
    - [Implement Save Question Action and Create Collection Page ✅](#implement-save-question-action-and-create-collection-page-)
    - [Display all saved questions ✅](#display-all-saved-questions-)
  - [Views ✅](#views-)
    - [Create Question Details Page View ✅](#create-question-details-page-view-)
  - [Tag Details Page ✅](#tag-details-page-)
    - [Create a Tag Details Page ✅](#create-a-tag-details-page-)
  - [Profile Page ✅](#profile-page-)
    - [Create Profile Page ✅](#create-profile-page-)
    - [Create User Stats UI ✅](#create-user-stats-ui-)
    - [Implement User Questions Tab ✅](#implement-user-questions-tab-)
    - [Implement User Answers Tabs ✅](#implement-user-answers-tabs-)
  - [Edit\_Delete User Actions ✅](#edit_delete-user-actions-)
    - [Implement Edit-Delete Question-Answer Component ✅](#implement-edit-delete-question-answer-component-)
    - [Create Edit Question Page ✅](#create-edit-question-page-)
    - [Create Edit Profile Page ✅](#create-edit-profile-page-)
  - [Show Top Results ✅](#show-top-results-)
    - [Show Top Questions ✅](#show-top-questions-)
    - [Show Popular Tags ✅](#show-popular-tags-)
  - [The Local Search Functionality 🔲](#the-local-search-functionality-)
    - [Manage search state ✅](#manage-search-state-)
    - [Implement Search functionality for the Home page ✅](#implement-search-functionality-for-the-home-page-)
    - [Implement Search functionality for the Community page ✅](#implement-search-functionality-for-the-community-page-)
    - [Implement Search functionality for the Collection page ✅](#implement-search-functionality-for-the-collection-page-)
    - [Implement Search functionality for the Tags page ✅](#implement-search-functionality-for-the-tags-page-)
  - [The Filters 🔲](#the-filters-)
    - [Manage Filter state ✅](#manage-filter-state-)
    - [Integrate Filters on Home page](#integrate-filters-on-home-page)
    - [Integrate Filters on the Community page](#integrate-filters-on-the-community-page)
    - [Integrate Filters on the Collection page](#integrate-filters-on-the-collection-page)
    - [Integrate Filters for Tags and Answers](#integrate-filters-for-tags-and-answers)
  - [The Pagination 🔲](#the-pagination-)
    - [Create Pagination component](#create-pagination-component)
    - [Implement pagination on the Home page](#implement-pagination-on-the-home-page)
    - [Implement pagination for the rest of the pages](#implement-pagination-for-the-rest-of-the-pages)
  - [Global Search 🔲](#global-search--1)
    - [Create the Global Search UI](#create-the-global-search-ui)
    - [Create GlobalSearch Result Component](#create-globalsearch-result-component)
    - [Create Global Search Filters](#create-global-search-filters)
    - [Implement the GlobalSearch action](#implement-the-globalsearch-action)
  - [Reputation 🔲](#reputation-)
    - [What is Reputation and how to approach it](#what-is-reputation-and-how-to-approach-it)
    - [Implement Reputation points for Questions](#implement-reputation-points-for-questions)
    - [Implement Reputation points for Answers](#implement-reputation-points-for-answers)
    - [More on Reputation and how to extend it](#more-on-reputation-and-how-to-extend-it)
  - [Badge System 🔲](#badge-system-)
    - [Implement the Badge System](#implement-the-badge-system)
  - [Generate AI Answer 🔲](#generate-ai-answer-)
    - [Setup AI Answer feature](#setup-ai-answer-feature)
    - [Implement the API route for the AI feature](#implement-the-api-route-for-the-ai-feature)
    - [Display the AI results on the UI](#display-the-ai-results-on-the-ui)
  - [Loadings \_ Toasts 🔲](#loadings-_-toasts-)
    - [Setup AI Answer feature](#setup-ai-answer-feature-1)
    - [Create a Loading state for the Community page](#create-a-loading-state-for-the-community-page)
    - [Create Loading states for the rest of the pages](#create-loading-states-for-the-rest-of-the-pages)
    - [Create toasts for a few actions](#create-toasts-for-a-few-actions)
  - [Meta Data 🔲](#meta-data-)
    - [What is Metadata and how to implement it](#what-is-metadata-and-how-to-implement-it)
  - [Bug Fixing and Recommendation 🔲](#bug-fixing-and-recommendation-)
    - [Fix bugs and implement Recommendations.](#fix-bugs-and-implement-recommendations)
  - [Next.js 13.5+ 🔲](#nextjs-135-)
    - [Upgrade Next.js to the latest version](#upgrade-nextjs-to-the-latest-version)
  - [Deployment 🔲](#deployment-)
    - [Deploy the application](#deploy-the-application)


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


## Develop Backend ✅
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
### MongoDB and Server Actions Setup ✅
let's install mongodb and mongoose 

![Alt text](image-142.png)

```
npm i mongodb mongoose
```

let's create a mongoose file

![Alt text](image-143.png)

```ts
import mongoose from "mongoose";

let isConnected: boolean = false;

export const connectToDatabase = async () => {
  mongoose.set("strictQuery", true);
  if (!process.env.MOGODB_URL) {
    return console.log("No DB URL found");
  }

  if (isConnected) {
    return console.log("MongoDB is already connected");
  }

  try {
    await mongoose.connect(process.env.MOGODB_URL, {
      dbName: "event-flow",
    });
    isConnected = true;
    console.log("MongoDB is connected");
  } catch (error) {
    console.log("MongoDB connection failed", error);
  }
};

```

and call this in server action file

```ts
"use server";

import { connectToDatabase } from "@/lib/mogoose";

export async function createQuestion(params: any) {
  try {
    await connectToDatabase();
  } catch (e) {}
}
```

and call this action in the question form

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
import { createQuestion } from "@/lib/actions/question.action";

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
  async function onSubmit(values: TQuestionsSchema) {
    setIsFormSubmitting(true);

    try {
      console.log(values);
      await createQuestion({});
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
                  onBlur={field.onBlur}
                  onEditorChange={(content) => field.onChange(content)}
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

### Creating Question Model 🔲
![Alt text](image-144.png)
```ts
import type { Document, ObjectId } from "mongoose";
import { model, models, Schema } from "mongoose";

export interface IQuestion extends Document {
  title: string;
  content: string;
  tags: ObjectId[];
  views: number;
  upvotes: ObjectId[];
  downvotes: ObjectId[];
  author: ObjectId;
  answers: ObjectId[];
  createdAt: Date;
}

const QuestionSchema = new Schema<IQuestion>({
  title: {
    type: String,
    required: true,
  },
  content: {
    type: String,
    required: true,
  },
  tags: [
    {
      type: Schema.Types.ObjectId,
      ref: "Tag",
    },
  ],
  views: {
    type: Number,
    default: 0,
  },
  upvotes: [
    {
      type: Schema.Types.ObjectId,
      ref: "User",
    },
  ],
  downvotes: [
    {
      type: Schema.Types.ObjectId,
      ref: "User",
    },
  ],
  author: {
    type: Schema.Types.ObjectId,
    ref: "User",
  },
  answers: [
    {
      type: Schema.Types.ObjectId,
      ref: "Answer",
    },
  ],
  createdAt: {
    type: Date,
    default: Date.now,
  },
});

const Question =
  models.Question || model<IQuestion>("Question", QuestionSchema);

export default Question;

```
### Creating a User Model ✅
```ts
import type { Document, ObjectId } from "mongoose";
import { model, models, Schema } from "mongoose";

export interface IUser extends Document {
  clearId: string;
  name: string;
  username: string;
  email: string;
  password?: string;
  bio?: string;
  picture: string;
  location?: string;
  portfolioWebsite?: string;
  reputation?: number;
  saved: ObjectId[];
  joinedAt: Date;
}

const UserSchema = new Schema<IUser>({
  clearId: {
    type: String,
    require: true,
  },
  name: {
    type: String,
    require: true,
  },
  username: {
    type: String,
    require: true,
    unique: true,
  },
  email: {
    type: String,
    unique: true,
    require: true,
  },
  password: {
    type: String,
  },
  bio: {
    type: String,
    required: false,
  },
  picture: {
    type: String,
    required: true,
  },
  location: {
    type: String,
    required: false,
  },
  portfolioWebsite: {
    type: String,
    required: false,
  },
  reputation: {
    type: Number,
    required: false,
    default: 0,
  },
  saved: [
    {
      type: Schema.Types.ObjectId,
      ref: "Question",
    },
  ],
  joinedAt: {
    type: Date,
    default: Date.now,
  },
});

const User = models.User || model<IUser>("User", UserSchema);

export default User;

```
### Creating a Tag Model ✅
```ts
import type { Document, ObjectId } from "mongoose";
import { model, models, Schema } from "mongoose";

export interface IUser extends Document {
  clearId: string;
  name: string;
  username: string;
  email: string;
  password?: string;
  bio?: string;
  picture: string;
  location?: string;
  portfolioWebsite?: string;
  reputation?: number;
  saved: ObjectId[];
  joinedAt: Date;
}

const UserSchema = new Schema<IUser>({
  clearId: {
    type: String,
    require: true,
  },
  name: {
    type: String,
    require: true,
  },
  username: {
    type: String,
    require: true,
    unique: true,
  },
  email: {
    type: String,
    unique: true,
    require: true,
  },
  password: {
    type: String,
  },
  bio: {
    type: String,
    required: false,
  },
  picture: {
    type: String,
    required: true,
  },
  location: {
    type: String,
    required: false,
  },
  portfolioWebsite: {
    type: String,
    required: false,
  },
  reputation: {
    type: Number,
    required: false,
    default: 0,
  },
  saved: [
    {
      type: Schema.Types.ObjectId,
      ref: "Question",
    },
  ],
  joinedAt: {
    type: Date,
    default: Date.now,
  },
});

const User = models.User || model<IUser>("User", UserSchema);

export default User;
```
## Create a Question ✅
```ts
"use server";

import { connectToDatabase } from "@/lib/mogoose";
import User, { IUser } from "@/database/user.model";

type TGetUserById = {
  userId: string;
};
export async function getUserById(params: TGetUserById): Promise<IUser> {
  try {
    const { userId } = params;
    await connectToDatabase();
    const user = await User.findOne({ clerkId: "123" });
    return user;
  } catch (error) {
    console.error(error);
    throw error;
  }
}

```

let's create a questio action

```ts
"use server";

import { connectToDatabase } from "@/lib/mogoose";
import Question from "@/database/question.model";
import Tag, { ITag } from "@/database/tag.model";

type TCreateQuestion = {
  title: string;
  content: string;
  tags: string[];
  author: string;
  path: string;
};
export async function createQuestion(params: TCreateQuestion) {
  try {
    await connectToDatabase();
    const { title, content, tags, author } = params;
    const question = await Question.create({
      title,
      content,
      author,
    });

    const tagDocuments: ITag[] = [];
    //   create the tag document if it doesn't exist or get the existing one
    for (const tag of tags) {
      const existingTag: ITag = await Tag.findOneAndUpdate(
        {
          name: { $regex: new RegExp(`^${tag}$`, "i") },
        },
        {
          $setOnInsert: {
            name: tag,
          },
          $push: {
            questions: question._id,
          },
        },
        {
          upsert: true,
          new: true,
        },
      );
      tagDocuments.push(existingTag);
    }
    //   let's update the question with the tags
    await Question.findByIdAndUpdate(question._id, {
      $push: {
        tags: { $each: tagDocuments },
      },
    });
  } catch (error) {
    console.error(error);
    throw error;
  }
}
```

let's get the user id from the server action

```ts
import Question from "@/components/forms/Question";
import { auth } from "@clerk/nextjs";
import { redirect } from "next/navigation";
import { getUserById } from "@/lib/actions/user.action";

const AskQuestionPage = async () => {
  const { userId } = auth();
  if (!userId) redirect("/sign-in");
  const mongoUser = await getUserById({ userId });
  console.table(mongoUser);
  return (
    <div>
      <h1 className="h1-bold text-dark100_light900">Ask a question</h1>
      <div className="mt-9">
        <Question mongoUserId={JSON.stringify("653c791cc9e6e4ed1b36e755")} />
      </div>
    </div>
  );
};

export default AskQuestionPage;
```

and submit form 

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
import { createQuestion } from "@/lib/actions/question.action";
import { usePathname, useRouter } from "next/navigation";

type TQuestionProps = {
  mongoUserId: string;
};

const formType = "edit";

const Question: FC<TQuestionProps> = ({ mongoUserId }) => {
  const [isFormSubmitting, setIsFormSubmitting] = useState(false);
  const editorRef = useRef(null);
  const router = useRouter();
  const pathName = usePathname();
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
  async function onSubmit(values: TQuestionsSchema) {
    setIsFormSubmitting(true);

    try {
      console.log(values);
      console.log("mongoUserId", mongoUserId);
      await createQuestion({
        title: values.title,
        content: values.explanation,
        tags: values.tags,
        author: JSON.parse(mongoUserId),
        path: pathName,
      });
      router.push("/");
    } catch (error) {
    } finally {
      setIsFormSubmitting(false);
    }
  }
```
## Fetching Questions on the Home Page ✅

remove the hard code data

```tsx
import Link from "next/link";
import { Button } from "@/components/ui/button";
import LocalSearch from "@/components/shared/search/LocalSearch";
import Filter from "@/components/shared/filters/Filter";
import { HOME_PAGE_FILTERS } from "@/constants/filters";
import HomeFilter from "@/components/home/HomeFilter";
import NoResult from "@/components/shared/noResult/NoResult";
import QuestionCard from "@/components/cards/QuestionCard";
import { getQuestions } from "@/lib/actions/question.action";

export default async function Home() {
  const { questions } = await getQuestions({});
  console.log(questions);
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

```ts
"use server";

import { connectToDatabase } from "@/lib/mogoose";
import Question from "@/database/question.model";
import Tag, { ITag } from "@/database/tag.model";
import {
  ICreateQuestionParams,
  IGetQuestionsParams,
} from "@/lib/actions/shared";
import User from "@/database/user.model";
import { revalidatePath } from "next/cache";

export async function createQuestion(params: ICreateQuestionParams) {
  try {
    await connectToDatabase();
    const { title, content, tags, author, path } = params;
    const question = await Question.create({
      title,
      content,
      author,
    });

    const tagDocuments: ITag[] = [];
    //   create the tag document if it doesn't exist or get the existing one
    for (const tag of tags) {
      const existingTag: ITag = await Tag.findOneAndUpdate(
        {
          name: { $regex: new RegExp(`^${tag}$`, "i") },
        },
        {
          $setOnInsert: {
            name: tag,
          },
          $push: {
            questions: question._id,
          },
        },
        {
          upsert: true,
          new: true,
        },
      );
      tagDocuments.push(existingTag);
    }
    //   let's update the question with the tags
    await Question.findByIdAndUpdate(question._id, {
      $push: {
        tags: { $each: tagDocuments },
      },
    });
    revalidatePath(path);
  } catch (error) {
    console.error(error);
    throw error;
  }
}

export async function getQuestions(params: IGetQuestionsParams) {
  try {
    await connectToDatabase();
    const questions = await Question.find({})
      .populate({
        path: "tags",
        model: Tag,
      })
      .populate({
        path: "author",
        model: User,
      })
      .sort({ createdAt: -1 });
    return { questions };
  } catch (error) {
    console.error(error);
    throw error;
  }
}

```

![Alt text](image-145.png)
## The Webhooks ✅
### Why _ what are Webhooks ✅
![Alt text](image-146.png)
### Implement Webhooks and User Actions ✅

clerk webhooks docs https://clerk.com/docs/integrations/webhooks

Sync data to your backend with webhooks https://clerk.com/docs/users/sync-data 

```shell
npm install svix
```

webhook.ts

```ts
import { Webhook } from "svix";
import { headers } from "next/headers";
import { WebhookEvent } from "@clerk/nextjs/server";
import { createUser, deleteUser, updateUser } from "@/lib/actions/user.action";
import { NextResponse } from "next/server";

export async function POST(req: Request) {
  // You can find this in the Clerk Dashboard -> Webhooks -> choose the webhook
  const WEBHOOK_SECRET = process.env.WEBHOOK_SECRET;

  if (!WEBHOOK_SECRET) {
    throw new Error(
      "Please add WEBHOOK_SECRET from Clerk Dashboard to .env or .env.local",
    );
  }

  // Get the headers
  const headerPayload = headers();
  const svixId = headerPayload.get("svix-id");
  const svixTimestamp = headerPayload.get("svix-timestamp");
  const svixSignature = headerPayload.get("svix-signature");

  // If there are no headers, error out
  if (!svixId || !svixTimestamp || !svixSignature) {
    return new Response("Error occurred -- no svix headers", {
      status: 400,
    });
  }

  // Get the body
  const payload = await req.json();
  const body = JSON.stringify(payload);

  // Create a new SVIX instance with your secret.
  const wh = new Webhook(WEBHOOK_SECRET);

  let evt: WebhookEvent;

  // Verify the payload with the headers
  try {
    evt = wh.verify(body, {
      "svix-id": svixId,
      "svix-timestamp": svixTimestamp,
      "svix-signature": svixSignature,
    }) as WebhookEvent;
  } catch (err) {
    console.error("Error verifying webhook:", err);
    return new Response("Error occurred", {
      status: 400,
    });
  }

  const eventType = evt.type;

  if (eventType === "user.created") {
    // eslint-disable-next-line camelcase
    const { id, email_addresses, image_url, first_name, last_name, username } =
      evt.data;
    const createdData = await createUser({
      clerkId: id,
      // eslint-disable-next-line camelcase
      email: email_addresses[0].email_address,
      // eslint-disable-next-line camelcase
      name: `${first_name} ${last_name ?? ""}`,
      // eslint-disable-next-line camelcase
      picture: image_url,
      username: username ?? "USER NAME NOT FOUND",
    });
    return NextResponse.json({
      message: "OK",
      user: createdData,
    });
  }
  if (eventType === "user.updated") {
    // eslint-disable-next-line camelcase
    const { id, email_addresses, image_url, first_name, last_name, username } =
      evt.data;
    const updatedUser = await updateUser({
      clerkId: id,
      updateData: {
        // eslint-disable-next-line camelcase
        email: email_addresses[0].email_address,
        // eslint-disable-next-line camelcase
        name: `${first_name} ${last_name ?? ""}`,
        // eslint-disable-next-line camelcase
        picture: image_url,
        username: username ?? "USER NAME NOT FOUND",
      },
      path: `/profile/${id}`,
    });
    return NextResponse.json({
      message: "OK",
      user: updatedUser,
    });
  }

  if (eventType === "user.deleted") {
    // eslint-disable-next-line camelcase
    const { id } = evt.data;
    const deletedUser = await deleteUser({
      clerkId: id!,
    });
    return NextResponse.json({
      message: "OK",
      user: deletedUser,
    });
  }

  return new Response("", { status: 201 });
}
```
server actions 
```ts
"use server";

import { connectToDatabase } from "@/lib/mogoose";
import User, { IUser } from "@/database/user.model";
import {
  DeleteUserParams,
  ICreateUserParams,
  UpdateUserParams,
} from "@/lib/actions/shared";
import { revalidatePath } from "next/cache";
import Question from "@/database/question.model";

type TGetUserById = {
  userId: string;
};
export async function getUserById(params: TGetUserById): Promise<IUser> {
  try {
    const { userId } = params;
    await connectToDatabase();
    const user = await User.findOne({ clerkId: userId });
    return user;
  } catch (error) {
    console.error(error);
    throw error;
  }
}

export async function createUser(userData: ICreateUserParams): Promise<IUser> {
  try {
    await connectToDatabase();
    return await User.create(userData);
  } catch (error) {
    console.error(error);
    throw error;
  }
}

export const updateUser = async (params: UpdateUserParams) => {
  try {
    await connectToDatabase();
    await User.findOneAndUpdate(
      { clerkId: params.clerkId },
      params.updateData,
      {
        new: true,
      },
    );

    revalidatePath(params.path);
  } catch (error) {
    console.error(error);
    throw error;
  }
};

export const deleteUser = async (params: DeleteUserParams) => {
  try {
    await connectToDatabase();
    const findUser = await User.findOne({
      clerkId: params.clerkId,
    });

    if (!findUser) {
      throw new Error("User not found");
    }

    // delete user from database
    // cleanup user's questions
    // cleanup user's answers
    // cleanup user's comments

    // const userQuestions = await Question.find({
    //   author: findUser._id,
    // }).distinct("_id");

    await Question.deleteMany({
      author: findUser._id,
    });
    return await User.findByIdAndDelete(findUser._id);
  } catch (error) {
    console.error(error);
    throw error;
  }
};

```
### Deploy Webhooks ✅
![Alt text](image-147.png)

middleware.ts
```ts
import { authMiddleware } from "@clerk/nextjs";

// This example protects all routes including api/trpc routes
// Please edit this to allow other routes to be public as needed.
// See https://clerk.com/docs/references/nextjs/auth-middleware for more information about configuring your Middleware
export default authMiddleware({
  publicRoutes: [
    "/",
    "/api/webhook",
    "question/:id",
    "/tags/:id",
    "/tags",
    "/profile/:id",
    "/community",
    "/jobs",
  ],
  ignoredRoutes: ["/api/webhook"],
});

export const config = {
  matcher: ["/((?!.+\\.[\\w]+$|_next).*)", "/", "/(api|trpc)(.*)"],
};

```

deploy the code to vercel
https://next-js-13-5-study-git-22thewebhooks-chamaraweerasinghe.vercel.app/
https://next-js-13-5-study-git-22thewebhooks-chamaraweerasinghe.vercel.app/

![Alt text](image-148.png)

add a webhook in the clerk dashboard

our app url -> https://next-js-13-5-study-git-22thewebhooks-chamaraweerasinghe.vercel.app/api/webhook

![Alt text](image-149.png)

![Alt text](image-150.png)

![Alt text](image-151.png)

![Alt text](image-152.png)

removing hardcorded data

```tsx
import Question from "@/components/forms/Question";
import { auth } from "@clerk/nextjs";
import { redirect } from "next/navigation";
import { getUserById } from "@/lib/actions/user.action";

const AskQuestionPage = async () => {
  const { userId } = auth();
  if (!userId) redirect("/sign-in");
  const mongoUser = await getUserById({ userId });
  return (
    <div>
      <h1 className="h1-bold text-dark100_light900">Ask a question</h1>
      <div className="mt-9">
        <Question mongoUserId={JSON.stringify(mongoUser._id)} />
      </div>
    </div>
  );
};

export default AskQuestionPage;
```

adding image urls

```ts
/** @type {import('next').NextConfig} */
const nextConfig = {
  experimental: {
    mdxRs: true,
    serverComponentsExternalPackages: ["mongoose"],
  },
  images: {
    remotePatterns: [
      {
        protocol: "https",
        hostname: "*",
      },
      {
        protocol: "https",
        hostname: "img.clerk.com",
      },
    ],
  },
};

module.exports = nextConfig;
  
```

## Community Page ✅
### Create Community Page ✅
get all user server action
```ts
export const getAllUsers = async (params: GetAllUsersParams) => {
  try {
    const { page = 1, pageSize = 20, searchQuery, filter } = params;
    console.log(page, pageSize, searchQuery, filter);
    await connectToDatabase();
    const users = await User.find({}).sort({
      createdAt: -1,
    });

    return {
      users,
    };
  } catch (error) {
    console.error(error);
    throw error;
  }
};
```
tag server action
```ts
"use server";

import { connectToDatabase } from "@/lib/mogoose";
import User from "@/database/user.model";
import { GetTopInteractedTagsParams } from "@/lib/actions/shared";

export const getTopInteractiveTags = async (
  params: GetTopInteractedTagsParams,
) => {
  try {
    const { userId } = params;
    await connectToDatabase();
    const user = await User.findById(userId);
    if (!user) {
      throw new Error("User not found");
    }
    // find interactions for user and group by tags...
    //   Interactions

    return [
      {
        _id: "1",
        name: "tag1",
      },
      {
        _id: "2",
        name: "tag2",
      },
      {
        _id: "3",
        name: "tag3",
      },
    ];
  } catch (error) {
    console.error(error);
    throw error;
  }
};
```
userCard component
```tsx
import { FC } from "react";
import Link from "next/link";
import Image from "next/image";
import { getTopInteractiveTags } from "@/lib/actions/tag.action";
import { Badge } from "@/components/ui/badge";
import RenderTags from "@/components/shared/tags/RenderTags";

type TUserCardProps = {
  user: {
    name: string;
    _id: string;
    clerkId: string;
    picture: string;
    username: string;
  };
};

const UserCard: FC<TUserCardProps> = async ({
  user: { name, picture, username, clerkId, _id },
}) => {
  const interactedTags = await getTopInteractiveTags({ userId: _id });
  return (
    <Link
      href={`/profile/${_id}`}
      className={
        "w-full border shadow-xl dark:border-none max-xs:min-w-full xs:w-[260px]"
      }
    >
      <article className="background-light900_dark200 light-border flex w-full flex-col items-center justify-center rounded-2xl border p-8">
        <Image
          src={picture}
          alt={"profile picture"}
          width={100}
          height={100}
          className={"rounded-full"}
        />
        <div className="mt-4 text-center">
          <h3 className="h3-bold text-dark200_light900 line-clamp-1">{name}</h3>
          <p className="body-regular text-dark500_light500 mt-2">@{username}</p>
        </div>

        <div className="mt-5">
          {interactedTags.length > 0 ? (
            <div className={"flex items-center gap-2"}>
              {interactedTags.map((tag) => (
                <RenderTags key={tag._id} _id={tag._id} name={tag.name} />
              ))}
            </div>
          ) : (
            <Badge>No tags yet</Badge>
          )}
        </div>
      </article>
    </Link>
  );
};

export default UserCard;
```
creating Community page
```tsx
import LocalSearch from "@/components/shared/search/LocalSearch";
import Filter from "@/components/shared/filters/Filter";
import { UserFilters } from "@/constants/filters";
import { getAllUsers } from "@/lib/actions/user.action";
import Link from "next/link";
import UserCard from "@/components/cards/UserCard";

const CommunityPage = async () => {
  const results = await getAllUsers({});
  console.log(results);
  return (
    <>
      <h1 className={"h1-bold text-dark100_light900"}>All Users</h1>

      <div className="mt-11 flex justify-between gap-5 max-sm:flex-col sm:items-center">
        <LocalSearch
          imageSrc={"/assets/icons/search.svg"}
          route={"/community"}
          iconPosition={"left"}
          placeholder={"Search for amazing minds"}
          otherClasses={"flex-1"}
        />
        <Filter
          filters={UserFilters}
          otherClasses={"min-h-[56px] sm:min-w-[170px]"}
        />
      </div>
      <section className={"mt-12 flex flex-wrap gap-4 "}>
        {results.users.length > 0 ? (
          results.users.map((user) => <UserCard key={user._id} user={user} />)
        ) : (
          <div
            className={
              "paragraph-regular text-dark200_light800 mx-auto max-w-4xl text-center"
            }
          >
            <p>No users Yet</p>
            <Link
              href={"/sign-up"}
              className={"mt-2 font-bold text-accent-blue"}
            >
              Join To Be The First
            </Link>
          </div>
        )}
      </section>
    </>
  );
};

export default CommunityPage;
```
![Alt text](image-153.png)
## Tags Page ✅
### Create Tags Page ✅
let's createa  tags page 
```tsx
import { FC } from "react";
import LocalSearch from "@/components/shared/search/LocalSearch";
import Filter from "@/components/shared/filters/Filter";
import { TagFilters } from "@/constants/filters";
import { getAllTags } from "@/lib/actions/tag.action";
import TagCard from "@/components/cards/TagCard";
import NoResult from "@/components/shared/noResult/NoResult";

type TTagsPageProps = {};

const TagsPage: FC<TTagsPageProps> = async () => {
  const results = await getAllTags({});
  return (
    <div>
      <h1 className={"h1-bold text-dark100_light900"}>Tags</h1>

      <div className="mt-11 flex justify-between gap-5 max-sm:flex-col sm:items-center">
        <LocalSearch
          imageSrc={"/assets/icons/search.svg"}
          route={"/tags"}
          iconPosition={"left"}
          placeholder={"Search for amazing minds"}
          otherClasses={"flex-1"}
        />
        <Filter
          filters={TagFilters}
          otherClasses={"min-h-[56px] sm:min-w-[170px]"}
        />
      </div>
      <section className={"mt-12 flex flex-wrap gap-4 "}>
        {results.tags.length > 0 ? (
          results.tags.map((tag) => <TagCard key={tag._id} tag={tag} />)
        ) : (
          <NoResult
            title={"No Tags Found"}
            description={"It seems that there are no tags yet"}
            LinkText={"Ask a question"}
            LinkHref={"/ask-question"}
          />
        )}
      </section>
    </div>
  );
};

export default TagsPage;
```

server action for the tags page
```ts
export const getAllTags = async (params: GetAllTagsParams) => {
  try {
    await connectToDatabase();
    const tags = await Tag.find({});
    return { tags };
  } catch (error) {
    console.error(error);
    throw error;
  }
};
```

TagCard component
```tsx
import { FC } from "react";
import Link from "next/link";

type TTageProps = {
  tag: {
    _id: string;
    createdOn: Date;
    followers: string[];
    name: string;
    questions: Array<string>;
  };
};

const TagCard: FC<TTageProps> = ({ tag }) => {
  const { _id, questions } = tag;
  return (
    <Link href={`/tags/${_id}`} className={"shadow-2xl dark:shadow-none"}>
      <article
        className={
          "background-light900_dark200 light-border flex w-full flex-col rounded-2xl border px-8 py-10 sm:w-[260px]"
        }
      >
        <div className="background-light800_dark400 w-fit rounded-sm px-5 py-1.5">
          <p className="paragraph-semibold text-dark300_light900">{tag.name}</p>
        </div>
        <p className="small-medium text-dark400_light500 mt-3.5">
          <span className="body-semibold primary-text-gradient mr-2.5">
            {questions.length}+
          </span>{" "}
          Questions
        </p>
      </article>
    </Link>
  );
};

export default TagCard;
```

![Alt text](image-154.png)
## Question Details Page ✅
### Create Question Details Page ✅
let's create a server action for the question details page
```ts
export const getQuestionById = async (
  params: GetQuestionByIdParams,
): Promise<{
  question: {
    _id: ObjectId;
    views: number;
    title: string;
    upvotes: any;
    downvotes: any;
    author: IUser;
    tags: ITag[];
    answers: any;
    createdAt: Date;
    content: string;
  };
}> => {
  const { questionId } = params;
  try {
    const result = await Question.findById(questionId)
      .populate({
        path: "tags",
        model: Tag,
        select: "_id name",
      })
      .populate({
        path: "author",
        model: User,
        select: "_id name picture clerkId",
      });
    return { question: result };
  } catch (error) {
    console.error(error);
    throw error;
  }
};
```

let's create a question details page
```tsx
import { getQuestionById } from "@/lib/actions/question.action";
import Image from "next/image";
import Link from "next/link";
import Metric from "@/components/shared/metric/Metric";
import { getTimStamp } from "@/lib/utils";
import ParseHTML from "@/components/shared/parseHtml/ParseHTML";

const Page = async ({ params }) => {
  const { question } = await getQuestionById({ questionId: params.id });

  return (
    <>
      <div className="flex-start w-full flex-col">
        <div className="flex w-full flex-col-reverse justify-between gap-5 sm:flex-row sm:items-center sm:gap-2">
          <Link
            className={"flex items-center justify-start gap-1"}
            href={`/profile/${question.author.clerkId}`}
          >
            <Image
              className={"rounded-full"}
              src={question.author.picture}
              alt={"profile picture"}
              height={22}
              width={22}
            />
            <p className="paragraph-semibold text-dark300_light700">
              {question.author.name}
            </p>
          </Link>
          <div className="flex justify-end">VOTING</div>
        </div>
        <h2 className="h2-semibold text-dark200_light900 mt-3.5 w-full text-left">
          {question.title}
        </h2>
      </div>
      <div className=" mb-8 mt-5 flex flex-wrap gap-4">
        <Metric
          imageUrl={"/assets/icons/clock.svg"}
          alt={"clock icons"}
          value={` asked ${getTimStamp(question.createdAt)}`}
          title={""}
          textStyles={"text-dark400_light800 small-medium"}
        />
        <Metric
          imageUrl={"/assets/icons/message.svg"}
          alt={"Upvotes"}
          value={question.answers.length}
          title={" Answers"}
          textStyles={"text-dark400_light800 small-medium"}
        />
        <Metric
          imageUrl={"/assets/icons/eye.svg"}
          alt={"eye"}
          value={question.views}
          title={" Views"}
          textStyles={"text-dark400_light800 small-medium"}
        />
      </div>
      <ParseHTML data={question.content} />
    </>
  );
};

export default Page;
```

and parseHTML component
```tsx
import { FC } from "react";

type TParseHTMLProps = {
  data: string;
};

const ParseHTML: FC<TParseHTMLProps> = ({ data }) => {
  return <div>{data}</div>;
};

export default ParseHTML;
```
### Parse _ display Question Content ✅
![Alt text](image-155.png)
let's install the react-html-parser prismjs and @types/prismjs

```shell
npm i react-html-parser prismjs 
```

```shell
npm i -D @types/prismjs
```

let's choose a css theme for the prismjs
![Alt text](image-156.png)

adding render tags part
```tsx
import { getQuestionById } from "@/lib/actions/question.action";
import Image from "next/image";
import Link from "next/link";
import Metric from "@/components/shared/metric/Metric";
import { getTimStamp } from "@/lib/utils";
import ParseHTML from "@/components/shared/parseHtml/ParseHTML";
import RenderTag from "@/components/shared/tags/RenderTag";
import { FC } from "react";
import Answer from "@/components/forms/Answer";

type TPageProps = {
  params: {
    id: string;
  };
};

const Page: FC<TPageProps> = async ({ params }) => {
  const { question } = await getQuestionById({ questionId: params.id });

  return (
    <>
      <div className="flex-start w-full flex-col">
        <div className="flex w-full flex-col-reverse justify-between gap-5 sm:flex-row sm:items-center sm:gap-2">
          <Link
            className={"flex items-center justify-start gap-1"}
            href={`/profile/${question.author.clerkId}`}
          >
            <Image
              className={"rounded-full"}
              src={question.author.picture}
              alt={"profile picture"}
              height={22}
              width={22}
            />
            <p className="paragraph-semibold text-dark300_light700">
              {question.author.name}
            </p>
          </Link>
          <div className="flex justify-end">VOTING</div>
        </div>
        <h2 className="h2-semibold text-dark200_light900 mt-3.5 w-full text-left">
          {question.title}
        </h2>
      </div>
      <div className=" mb-8 mt-5 flex flex-wrap gap-4">
        <Metric
          imageUrl={"/assets/icons/clock.svg"}
          alt={"clock icons"}
          value={` asked ${getTimStamp(question.createdAt)}`}
          title={""}
          textStyles={"text-dark400_light800 small-medium"}
        />
        <Metric
          imageUrl={"/assets/icons/message.svg"}
          alt={"Upvotes"}
          value={question.answers.length}
          title={" Answers"}
          textStyles={"text-dark400_light800 small-medium"}
        />
        <Metric
          imageUrl={"/assets/icons/eye.svg"}
          alt={"eye"}
          value={question.views}
          title={" Views"}
          textStyles={"text-dark400_light800 small-medium"}
        />
      </div>
      <ParseHTML data={question.content} />
      <div className="mt-8 flex flex-wrap gap-4">
        {question.tags.map((tag) => (
          <RenderTag key={tag._id} _id={tag._id} name={tag.name} />
        ))}
      </div>
      <Answer />
    </>
  );
};

export default Page;

```

ParseHtml Componet
```tsx
"use client";
import { FC, useEffect } from "react";
import parse from "html-react-parser";
import Prism from "prismjs";
import "prismjs/components/prism-python";
import "prismjs/components/prism-java";
import "prismjs/components/prism-c";
import "prismjs/components/prism-cpp";
import "prismjs/components/prism-csharp";
import "prismjs/components/prism-aspnet";
import "prismjs/components/prism-sass";
import "prismjs/components/prism-jsx";
import "prismjs/components/prism-typescript";
import "prismjs/components/prism-solidity";
import "prismjs/components/prism-json";
import "prismjs/components/prism-dart";
import "prismjs/components/prism-ruby";
import "prismjs/components/prism-rust";
import "prismjs/components/prism-r";
import "prismjs/components/prism-kotlin";
import "prismjs/components/prism-go";
import "prismjs/components/prism-bash";
import "prismjs/components/prism-sql";
import "prismjs/components/prism-mongodb";
import "prismjs/plugins/line-numbers/prism-line-numbers.js";
import "prismjs/plugins/line-numbers/prism-line-numbers.css";

type TParseHTMLProps = {
  data: string;
};

const ParseHTML: FC<TParseHTMLProps> = ({ data }) => {
  useEffect(() => {
    Prism.highlightAll();
  }, []);
  return <div>{parse(data)}</div>;
};

export default ParseHTML;
```


### Create Answer Form ✅
schema 
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

export const AnswerSchema = z.object({
  answer: z.string().min(100),
});

export type TQuestionsSchema = z.infer<typeof QuestionsSchema>;
export type TAnswerSchema = z.infer<typeof AnswerSchema>;

```

Answer Form
```tsx
"use client";
import {
  Form,
  FormControl,
  FormField,
  FormItem,
  FormMessage,
} from "@/components/ui/form";
import { useForm } from "react-hook-form";
import { AnswerSchema, TAnswerSchema } from "@/lib/validations";
import { zodResolver } from "@hookform/resolvers/zod";
import { Editor } from "@tinymce/tinymce-react";
import React, { useRef, useState } from "react";
import { useTheme } from "@/context/ThemeProvider";
import { Button } from "@/components/ui/button";
import Image from "next/image";

const Answer = () => {
  const [isSubmitting, setIsSubmitting] = useState(false);
  const editorRef = useRef(null);
  const form = useForm<TAnswerSchema>({
    resolver: zodResolver(AnswerSchema),
    defaultValues: {
      answer: "",
    },
  });
  const { theme } = useTheme();
  const handleCreateAnswer = async (data: TAnswerSchema) => {
    setIsSubmitting(true);
  };
  return (
    <div>
      <div className="mt-8 flex flex-col justify-between gap-5 sm:flex-row sm:items-center sm:gap-2">
        <h4 className="paragraph-semibold text-dark400_light800">
          Write your answer here
        </h4>
        <Button
          className={
            "btn  light-border-2 gap-1.5 rounded-md px-4 py-2.5 text-primary-500 shadow-none"
          }
        >
          <Image
            src={"/assets/icons/stars.svg"}
            alt={"AI image"}
            width={12}
            height={12}
            className={"object-contain "}
          />
          Generate AI Answer
        </Button>
      </div>
      <Form {...form}>
        <form
          className={"mt-6 flex w-full flex-col gap-10"}
          onSubmit={form.handleSubmit(handleCreateAnswer)}
        >
          <FormField
            control={form.control}
            name="answer"
            render={({ field }) => (
              <FormItem className={"flex w-full flex-col gap-3"}>
                <FormControl className={"mt-3.5"}>
                  <Editor
                    apiKey={process.env.NEXT_PUBLIC_TINY_API_KEY}
                    onInit={(evt, editor) => {
                      // @ts-ignore
                      editorRef.current = editor;
                    }}
                    onBlur={field.onBlur}
                    onEditorChange={(content) => field.onChange(content)}
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
                      content_style:
                        "body { font-family:Inter; font-size:16px }",
                      skin: theme === "dark" ? "oxide-dark" : "oxide",
                      content_css: theme === "dark" ? "dark" : "default",
                    }}
                  />
                </FormControl>
                <FormMessage
                  className={
                    "rounded bg-red-500/10 py-2 text-center text-red-500"
                  }
                />
              </FormItem>
            )}
          />
          <div className="flex justify-end">
            <Button
              disabled={isSubmitting}
              type={"submit"}
              className={"primary-gradient w-fit text-white"}
            >
              {isSubmitting ? "Submitting..." : "Submit"}
            </Button>
          </div>
        </form>
      </Form>
    </div>
  );
};

export default Answer;
```
### Create Answer Model ✅

```ts
import type { Document, ObjectId } from "mongoose";
import { model, models, Schema } from "mongoose";

export interface IAnswer extends Document {
  author: ObjectId;
  question: ObjectId;
  content: string;
  upvotes: ObjectId[];
  downvotes: ObjectId[];
  createdAt: Date;
}

const AnswerSchema = new Schema<IAnswer>({
  author: {
    type: Schema.Types.ObjectId,
    ref: "User",
    required: true,
  },
  question: {
    type: Schema.Types.ObjectId,
    ref: "Question",
    required: true,
  },
  content: {
    type: String,
    required: true,
  },
  upvotes: {
    type: [Schema.Types.ObjectId],
    ref: "User",
    default: [],
  },
  downvotes: {
    type: [Schema.Types.ObjectId],
    ref: "User",
    default: [],
  },
});

const Question = models.Answer || model<IAnswer>("Answer", AnswerSchema);

export default Question;
```
### Implement Create Answer action ✅

```ts
"use server";

import { CreateAnswerParams, GetAnswersParams } from "@/lib/actions/shared";
import { connectToDatabase } from "@/lib/mogoose";
import { revalidatePath } from "next/cache";
import Answer from "@/database/answer.model";
import Question from "@/database/question.model";

export const createAnswer = async (params: CreateAnswerParams) => {
  const { content, author, question, path } = params;
  try {
    await connectToDatabase();
    const newAnswer = new Answer({
      content,
      author,
      question,
    });
    // add answer to question
    await Question.findByIdAndUpdate(question, {
      $push: { answers: newAnswer._id },
    });
    newAnswer.save();
    revalidatePath(path);
    return newAnswer;
  } catch (error) {
    console.error(error);
    throw error;
  }
};
```


implement the onSubmit method 
```tsx
const Answer: FC<TAnswerProps> = ({ question, questionId, authorId }) => {
  const [isSubmitting, setIsSubmitting] = useState(false);
  const editorRef = useRef(null);
  const form = useForm<TAnswerSchema>({
    resolver: zodResolver(AnswerSchema),
    defaultValues: {
      answer: "",
    },
  });
  const { theme } = useTheme();
  const pathName = usePathname();
  const handleCreateAnswer = async (data: TAnswerSchema) => {
    setIsSubmitting(true);
    const { answer } = data;
    try {
      await createAnswer({
        content: answer,
        author: JSON.parse(authorId),
        question: JSON.parse(questionId),
        path: pathName,
      });
      form.reset();
      const editor = editorRef.current as any;
      editor.setContent("");
      setIsSubmitting(false);
    } catch (e) {
      console.log(e);
      throw e;
    }
  };
```

passing the props to Answer component
```tsx

const Page: FC<TPageProps> = async ({ params }) => {
  const { question } = await getQuestionById({ questionId: params.id });
  const { userId: clerkId } = auth();
  let mongoUser;
  if (clerkId) {
    mongoUser = await getUserById({ userId: clerkId });
  }


---------------------- rest of the content

      </div>
      <Answer
        question={question.content}
        questionId={JSON.stringify(question._id)}
        authorId={JSON.stringify(mongoUser?._id ?? "")}
      />
    </>
  );

```


### Integrate Create Answer action inside Answer Form
get answer by question id server action
```ts
export const getAnswerByQuestionId = async (params: GetAnswersParams) => {
  const { questionId } = params;

  try {
    const answers = await Answer.find({
      question: questionId,
    })
      .populate({
        path: "author",
        model: "User",
        select: "_id clerkId picture name",
      })
      .sort({
        createdAt: -1,
      });
    return {
      answers,
    };
  } catch (error) {
    console.log(error);
    throw error;
  }
};
```
### Display All Answers ✅
display all answers
```tsx
import Filter from '@/components/shared/filters/Filter';
import { AnswerFilters } from '@/constants/filters';
import { getAnswerByQuestionId } from '@/lib/actions/answer.action';
import { getTimStamp } from '@/lib/utils';
import { ObjectId } from 'mongoose';
import Image from 'next/image';
import Link from 'next/link';
import { FC } from 'react';
import ParseHTML from '../parseHtml/ParseHTML';

type TAllAnswerProps = {
	questionId: ObjectId;
	userId: ObjectId;
	totalAnswers: number;
	page?: number;
	filter?: string;
};

const AllAnswers: FC<TAllAnswerProps> = async ({
	totalAnswers,
	userId,
	questionId
}) => {
	const result = await getAnswerByQuestionId({
		questionId
	});
	const { answers } = result;
	return (
		<div className={'mt-11'}>
			<div className="flex items-center justify-between">
				<h3 className="primary-text-gradient">{totalAnswers} Answers</h3>
				<Filter filters={AnswerFilters} />
			</div>
			<div className="">
				{answers.map((answer) => (
					<article className={'light-border border-b py-10'} key={answer._id}>
						<div className="mb-8 flex items-center justify-between">
							<div className="flex flex-col-reverse justify-between gap-5 sm:flex-row sm:items-center sm:gap-2">
								<Link
									href={`/profile/${answer.author.clerkId}`}
									className={'flex flex-1 items-start gap-1 sm:items-center'}
								>
									<Image
										src={answer.author.picture}
										width={18}
										height={18}
										alt={'profile'}
										className={'rounded-full object-cover max-sm:mt-0.5'}
									/>
									<div className="flex flex-col sm:flex-row sm:items-center">
										<p className="body-semibold text-dark300_light700">
											{answer.author.name}
										</p>
										<p className="small-regular text-dark400_light500 ml-0.5 mt-0.5 line-clamp-1">
											<span className="max-sm:hidden"> -</span>
											answered {getTimStamp(answer.createdAt)}
										</p>
									</div>
								</Link>
							</div>
							<div className="flex justify-end">VOTTING</div>
						</div>
						<ParseHTML data={answer.content} />
					</article>
				))}
			</div>
		</div>
	);
};

export default AllAnswers;
```
![Alt text](image-157.png)
## Voting ✅
### Create Votes UI ✅

![Alt text](image-158.png)

Voting Component
```tsx
"use client";
import { FC } from "react";
import { ObjectId } from "mongoose";
import Image from "next/image";
import { formatNumber } from "@/lib/utils";

type TVotesProps = {
  type: "question" | "answer";
  itemId: ObjectId;
  userId: ObjectId;
  upvotes: number;
  hasUpVoted: boolean;
  downVotes: number;
  hasDownVoted: boolean;
  hasSaved: boolean;
};
const Votes: FC<TVotesProps> = ({
  hasUpVoted,
  upvotes,
  downVotes,
  hasDownVoted,
  itemId,
  type,
  hasSaved,
  userId,
}) => {
  const handleSave = () => {};
  const handleVote = (type: "upvote" | "downVote") => {};
  return (
    <div className={"flex gap-5"}>
      <div className="flex-center gap-2.5">
        <div className="flex-center gap-1.5">
          <Image
            src={
              hasUpVoted
                ? "/assets/icons/upvoted.svg"
                : "/assets/icons/upvote.svg"
            }
            alt={"upvote icon"}
            width={18}
            height={18}
            className={"cursor-pointer"}
            onClick={() => handleVote("upvote")}
          />
          <div className="background-light700_dark400 flex min-w-[18px] items-center rounded-sm p-1">
            <p className="subtle-medium text-dark400_light900">
              {formatNumber(upvotes)}
            </p>
          </div>
        </div>
        <div className="flex-center gap-1.5">
          <Image
            src={
              hasDownVoted
                ? "/assets/icons/downvoted.svg"
                : "/assets/icons/downvote.svg"
            }
            alt={"upvote icon"}
            width={18}
            height={18}
            className={"cursor-pointer"}
            onClick={() => handleVote("downVote")}
          />
          <div className="background-light700_dark400 flex min-w-[18px] items-center rounded-sm p-1">
            <p className="subtle-medium text-dark400_light900">
              {formatNumber(downVotes)}
            </p>
          </div>
        </div>
      </div>
      <Image
        src={
          hasSaved
            ? "/assets/icons/start-filled.svg"
            : "/assets/icons/star-red.svg"
        }
        alt={"upvote icon"}
        width={18}
        height={18}
        className={"cursor-pointer"}
        onClick={handleSave}
      />
    </div>
  );
};

export default Votes;

```



### Create Upvote-DownVote actions for Question ✅

```ts
export const upVoteQuestion = async (params: QuestionVoteParams) => {
  try {
    await connectToDatabase();
    const { questionId, path, hasUpVoted, hasDownVoted, userId } = params;
    let updateQuery: any = {};
    if (hasUpVoted) {
      updateQuery = { $pull: { upvotes: userId } };
    } else if (hasDownVoted) {
      updateQuery = { 
        $pull: { downvotes: userId },
        $push: { upvotes: userId },
      };
    } else {
      updateQuery = { $addToSet: { upvotes: userId } };
    }
    const question = await Question.findByIdAndUpdate(questionId, updateQuery, {
      new: true,
    });
    if (!question) {
      throw new Error("Question not found");
    }

    revalidatePath(path);
  } catch (error) {
    console.error(error);
    throw error;
  }
};

export const downVoteQuestion = async (params: QuestionVoteParams) => {
  try {
    await connectToDatabase();
    const { questionId, path, hasUpVoted, hasDownVoted, userId } = params;
    let updateQuery: any = {};
    if (hasDownVoted) {
      updateQuery = { $pull: { downvotes: userId } };
    } else if (hasUpVoted) {
      updateQuery = {
        $pull: { upvotes: userId },
        $push: { downvotes: userId },
      };
    } else {
      updateQuery = { $addToSet: { downvotes: userId } };
    }
    const question = await Question.findByIdAndUpdate(questionId, updateQuery, {
      new: true,
    });
    if (!question) {
      throw new Error("Question not found");
    }

    revalidatePath(path);
  } catch (error) {
    console.error(error);
    throw error;
  }
};
```
### Integrate Question upvote-downvote actions on UI ✅

![Alt text](image-159.png)

```tsx
  const pathName = usePathname();
  const handleSave = () => {};
  const handleVote = async (action: "upvote" | "downVote") => {
    if (!userId) return;

    if (action === "upvote") {
      if (type === "question") {
        await upVoteQuestion({
          questionId: itemId,
          userId,
          hasUpVoted,
          hasDownVoted,
          path: pathName,
        });
      } else if (type === "answer") {
        // await upVoteAnswer({
        //   questionId: itemId,
        //   userId,
        //   hasUpVoted,
        //   hasDownVoted,
        //   path: pathName,
        // });
      }
    }

    if (action === "downVote") {
      if (type === "question") {
        await downVoteQuestion({
          questionId: itemId,
          userId,
          hasUpVoted,
          hasDownVoted,
          path: pathName,
        });
      } else if (type === "answer") {
        // await downVoteAnswer({
        //   questionId: itemId,
        //   userId,
        //   hasUpVoted,
        //   hasDownVoted,
        //   path: pathName,
        // });
      }
    }
  };
```

![Alt text](image-160.png)

![Alt text](image-161.png)
### Create Answer Voting ✅
server actions 
```ts
export const upVoteAnswer = async (params: AnswerVoteParams) => {
  try {
    await connectToDatabase();
    const { userId, path, answerId, hasUpVoted, hasDownVoted } = params;
    let updateQuery: any = {};
    if (hasUpVoted) {
      updateQuery = { $pull: { upvotes: userId } };
    } else if (hasDownVoted) {
      updateQuery = {
        $pull: { downvotes: userId },
        $push: { upvotes: userId },
      };
    } else {
      updateQuery = { $addToSet: { upvotes: userId } };
    }
    const answer = await Answer.findByIdAndUpdate(answerId, updateQuery, {
      new: true,
    });
    if (!answer) {
      throw new Error("Answer not found");
    }

    revalidatePath(path);
  } catch (error) {
    console.error(error);
    throw error;
  }
};

export const downVoteAnswer = async (params: AnswerVoteParams) => {
  try {
    await connectToDatabase();
    const { userId, path, answerId, hasUpVoted, hasDownVoted } = params;
    let updateQuery: any = {};
    if (hasDownVoted) {
      updateQuery = { $pull: { downvotes: userId } };
    } else if (hasUpVoted) {
      updateQuery = {
        $pull: { upvotes: userId },
        $push: { downvotes: userId },
      };
    } else {
      updateQuery = { $addToSet: { downvotes: userId } };
    }
    const answer = await Answer.findByIdAndUpdate(answerId, updateQuery, {
      new: true,
    });
    if (!answer) {
      throw new Error("Answer not found");
    }

    revalidatePath(path);
  } catch (error) {
    console.error(error);
    throw error;
  }
};
```

add it to the all action file
```tsx
                      answered {getTimStamp(answer.createdAt)}
                    </p>
                  </div>
                </Link>
              </div>
              <div className="flex justify-end">
                <Votes
                  type={"answer"}
                  itemId={answer._id}
                  userId={userId}
                  upvotes={answer.upvotes.length}
                  hasUpVoted={answer.upvotes.includes(userId)}
                  downVotes={answer.downvotes.length}
                  hasDownVoted={answer.downvotes.includes(userId)}
                />
              </div>
            </div>
            <ParseHTML data={answer.content} />
          </article>
        ))}
      </div>
    </div>
  );
};
```

conditionaly render the votes saved icon.

![Alt text](image-162.png)

## Collections Page ✅

### Implement Save Question Action and Create Collection Page ✅

let's implement the server action to save question
```ts
export const toggleSaveQuestion = async (params: ToggleSaveQuestionParams) => {
  try {
    const { userId, questionId, path } = params;
    await connectToDatabase();
    const user = await User.findById(userId);

    if (!user) {
      throw new Error("User not found");
    }

    const isSaved = user.saved.includes(questionId);
    if (isSaved) {
      // remove question from saved
      await User.findByIdAndUpdate(
        userId,
        {
          $pull: {
            saved: questionId,
          },
        },
        {
          new: true,
        },
      );
    } else {
      // add question to saved
      await User.findByIdAndUpdate(
        userId,
        {
          $addToSet: {
            saved: questionId,
          },
        },
        {
          new: true,
        },
      );
    }
    revalidatePath(path);
  } catch (error) {
    console.error(error);
    throw error;
  }
};
```

let's use it in the Votes component
```tsx
  const handleSave = async () => {
    try {
      if (type !== "question") return;
      await toggleSaveQuestion({
        questionId: itemId,
        userId,
        path: pathName,
      });
    } catch (error) {
      console.log(error);
      throw error;
    }
  };
```

and create the collection page

![Alt text](image-163.png)

![Alt text](image-164.png)
### Display all saved questions ✅

let's create the server action to get all saved questions
```ts
export const getSavedQuestion = async (params: GetSavedQuestionsParams) => {
  try {
    const { page = 1, pageSize = 10, searchQuery, filter, clerkId } = params;
    console.log(page, pageSize, searchQuery, filter);
    await connectToDatabase();
    const query: FilterQuery<typeof Question> = searchQuery
      ? { title: { regex: new RegExp(searchQuery, "i") } }
      : {};
    const user = await User.findOne({ clerkId }).populate({
      path: "saved",
      match: query,
      options: {
        sort: {
          createdAt: -1,
        },
        populate: [
          {
            path: "tags",
            model: Tag,
            select: "name _id",
          },
          {
            path: "author",
            model: User,
            select: "name _id clerkId picture",
          },
        ],
      },
    });

    if (!user) {
      throwError("User not found");
    }

    const savedQuestions = user.saved;

    return {
      questions: savedQuestions,
    };
  } catch (error) {
    console.error(error);
    throw error;
  }
};
```

and the collection page
```tsx
import LocalSearch from "@/components/shared/search/LocalSearch";
import Filter from "@/components/shared/filters/Filter";
import { QuestionFilters } from "@/constants/filters";
import NoResult from "@/components/shared/noResult/NoResult";
import QuestionCard from "@/components/cards/QuestionCard";
import { TQuestion } from "@/types/types";
import { getSavedQuestion } from "@/lib/actions/user.action";
import { auth } from "@clerk/nextjs";

export default async function Home() {
  const { userId } = auth();

  if (!userId) return null;

  const { questions } = await getSavedQuestion({
    clerkId: userId,
  });
  return (
    <>
      <h1 className={"h1-bold text-dark100_light900"}>Saved Questions</h1>

      <div className="mt-11 flex justify-between gap-5 max-sm:flex-col sm:items-center">
        <LocalSearch
          imageSrc={"/assets/icons/search.svg"}
          route={"/"}
          iconPosition={"left"}
          placeholder={"Search Questions ..."}
          otherClasses={"flex-1"}
        />
        <Filter
          filters={QuestionFilters}
          otherClasses={"min-h-[56px] sm:min-w-[170px]"}
        />
      </div>
      <div className="mt-10 flex w-full flex-col gap-6">
        {questions.length > 0 ? (
          questions.map((question: TQuestion) => (
            // <QuestionCard key={question._id} question={question} />
            <QuestionCard key={question._id} question={question} />
          ))
        ) : (
          <NoResult
            title={"There is no saved questions to show"}
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

![Alt text](image-165.png)


## Views ✅
### Create Question Details Page View ✅
let's create interaction model
```ts
import { model, models, ObjectId, Schema } from "mongoose";

export interface IInteraction {
  user: ObjectId;
  action: string;
  question: ObjectId;
  answer: ObjectId;
  tags: ObjectId[];
  createdAt: Date;
}

const interactionSchema = new Schema<IInteraction>({
  user: {
    type: Schema.Types.ObjectId,
    ref: "User",
    required: true,
  },
  action: {
    type: String,
    required: true,
  },
  question: {
    type: Schema.Types.ObjectId,
    ref: "Question",
  },
  answer: {
    type: Schema.Types.ObjectId,
    ref: "Answer",
  },
  tags: [
    {
      type: Schema.Types.ObjectId,
      ref: "Tag",
    },
  ],
  createdAt: {
    type: Date,
    default: Date.now,
  },
});

const Interaction =
  models.Interaction || model<IInteraction>("Interaction", interactionSchema);

export default Interaction;
```
server action
```ts
"use server";

import { ViewQuestionParams } from "@/lib/actions/shared";
import { connectToDatabase } from "@/lib/mogoose";
import Question from "@/database/question.model";
import Interaction from "@/database/interaction.model";

export const viewQuestion = async (params: ViewQuestionParams) => {
  try {
    await connectToDatabase();
    const { userId, questionId } = params;
    await Question.findByIdAndUpdate(questionId, {
      $inc: { views: 1 },
    });

    if (userId) {
      const existingInteraction = await Interaction.findOne({
        user: userId,
        action: "view",
        question: questionId,
      });
      if (existingInteraction) return console.log("Already viewed");
      await Interaction.create({
        user: userId,
        action: "view",
        question: questionId,
      });
    }
  } catch (e) {
    console.log(e);
    throw e;
  }
};
```

let's add the server action in the Votes page 
```ts

  useEffect(() => {
    viewQuestion({ questionId: itemId, userId });
  }, [itemId, userId, router, pathName]);
```

![Alt text](image-166.png)

## Tag Details Page ✅
### Create a Tag Details Page ✅
let's create a server action 
```ts
export const getQuestionByTagId = async (params: GetQuestionsByTagIdParams) => {
  try {
    await connectToDatabase();
    const { tagId, searchQuery } = params;
    const tagFilter: FilterQuery<ITag> = {
      _id: tagId,
    };
    const tag = await Tag.findOne(tagFilter).populate({
      path: "questions",
      model: Question,
      match: searchQuery
        ? { title: { $regex: new RegExp(searchQuery, "i") } }
        : {},
      options: {
        sort: {
          createdAt: -1,
        },
        populate: [
          {
            path: "tags",
            model: Tag,
            select: "name _id",
          },
          {
            path: "author",
            model: User,
            select: "name _id clerkId picture",
          },
        ],
      },
    });

    if (!tag) {
      throwError("Tag not found");
    }

    const questions = tag.questions;

    return {
      tagTitle: tag.name,
      questions,
    };
  } catch (e) {
    console.log(e);
    throw e;
  }
};
```
![Alt text](image-167.png)

tags details page
```tsx
import { FC } from "react";
import { getQuestionByTagId } from "@/lib/actions/tag.action";
import LocalSearch from "@/components/shared/search/LocalSearch";
import { TQuestion, URLProps } from "@/types/types";
import QuestionCard from "@/components/cards/QuestionCard";
import NoResult from "@/components/shared/noResult/NoResult";

const Page: FC<URLProps> = async ({ params, searchParams }) => {
  const { questions, tagTitle } = await getQuestionByTagId({
    tagId: params.id,
    page: 1,
    searchQuery: searchParams.q,
  });

  return (
    <div>
      <h1 className={"h1-bold text-dark100_light900"}>{tagTitle}</h1>

      <div className="mt-11 w-full">
        <LocalSearch
          imageSrc={"/assets/icons/search.svg"}
          route={"/"}
          iconPosition={"left"}
          placeholder={"Search Tag Questions ..."}
          otherClasses={"flex-1"}
        />
      </div>
      <div className="mt-10 flex w-full flex-col gap-6">
        {questions.length > 0 ? (
          questions.map((question: TQuestion) => (
            // <QuestionCard key={question._id} question={question} />
            <QuestionCard key={question._id} question={question} />
          ))
        ) : (
          <NoResult
            title={"There is no tag questions to show"}
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
    </div>
  );
};

export default Page;
```

![Alt text](image-169.png)

## Profile Page ✅


### Create Profile Page ✅ 

![Alt text](image-170.png)

![Alt text](image-171.png)

```shell
npx shadcn-ui@latest add tabs
```

getUserInfo server action
```ts
export const getUserInfo = async (params: GetUserByIdParams) => {
  try {
    const { userId } = params;
    await connectToDatabase();
    const user = await User.findOne({
      clerkId: userId,
    });
    if (!user) {
      throwError("User not found");
    }
    const totalQuestions = await Question.countDocuments({
      author: user._id,
    });
    const totalAnswers = await Answer.countDocuments({
      author: user._id,
    });
    return { user, totalQuestions, totalAnswers };
  } catch (error) {
    console.error(error);
    throw error;
  }
};
```
util file 
```ts
export const convertDate = (date: Date) => {
  return date.toLocaleString("default", {
    month: "long",
    year: "numeric",
  });
};
```

ProfileLink componet
```tsx
import { FC } from "react";
import Image from "next/image";
import Link from "next/link";

type TProfileLinkProps = {
  imageUrl: string;
  title: string;
  href?: string;
};

const ProfileLink: FC<TProfileLinkProps> = ({ imageUrl, title, href }) => {
  return (
    <div className={"flex-center gap-1"}>
      <Image src={imageUrl} alt={"icon"} height={20} width={20} />
      {href ? (
        <Link
          href={href}
          target={"_blank"}
          className={"paragraph-medium text-accent-blue"}
        >
          {title}
        </Link>
      ) : (
        <p className={"paragraph-medium text-dark400_light700"}>{title}</p>
      )}
    </div>
  );
};

export default ProfileLink;
```

Stats component
```tsx
const Stats = () => {
  return <div>Stats</div>;
};

export default Stats;
```

profile id page
```tsx
import { FC } from "react";
import { URLProps } from "@/types/types";
import { getUserInfo } from "@/lib/actions/user.action";
import Image from "next/image";
import { auth, SignedIn } from "@clerk/nextjs";
import Link from "next/link";
import { Button } from "@/components/ui/button";
import { Tabs, TabsContent, TabsList, TabsTrigger } from "@/components/ui/tabs";
import { convertDate } from "@/lib/utils";
import ProfileLink from "@/components/shared/profileLink/ProfileLink";
import Stats from "@/components/shared/stats/Stats";

const Page: FC<URLProps> = async ({ params, searchParams }) => {
  const result = await getUserInfo({ userId: params.id });
  const { userId: clerkId } = auth();
  return (
    <>
      <div
        className={
          "flex flex-col-reverse items-start justify-between sm:flex-row"
        }
      >
        <div className={"flex flex-col items-start gap-4 lg:flex-row"}>
          <Image
            src={result.user.picture}
            alt={"profile picture"}
            height={128}
            width={128}
            className={"rounded-full object-cover"}
          />
          <div className="mt-3">
            <h2 className={"h2-bold text-dark100_light900"}>
              {result.user.name}
            </h2>
            <p className={"paragraph-regular text-dark200_light800"}>
              @{result.user.username}
            </p>
            <div className="mt-5 flex flex-wrap items-center justify-start gap-5">
              {result.user?.location && (
                <ProfileLink
                  imageUrl={"/assets/icons/location.svg"}
                  title={result.user?.location}
                />
              )}
              {result.user?.portfolioWebsite && (
                <ProfileLink
                  imageUrl={"/assets/icons/link.svg"}
                  href={result.user?.portfolioWebsite}
                  title={"Portfolio"}
                />
              )}
              {
                <ProfileLink
                  imageUrl={"/assets/icons/calendar.svg"}
                  title={convertDate(result.user?.joinedAt)}
                />
              }
            </div>
            {result.user?.bio && (
              <p className={"paragraph-regular text-dark400_light800 mt-8"}>
                {result.user?.bio}
              </p>
            )}
          </div>
        </div>
        <div className="flex justify-end max-sm:mb-5 max-sm:w-full sm:mt-3">
          <SignedIn>
            {clerkId === result.user.clerkId && (
              <Link href={`/profile/edit`}>
                <Button
                  className={
                    "paragraph-medium btn-secondary text-dark300_light900 min-h-[46px] min-w-[176px] px-4 py-3"
                  }
                >
                  Edit Profile
                </Button>
              </Link>
            )}
          </SignedIn>
        </div>
      </div>
      <Stats />
      <div className="mt-10 flex gap-10">
        <Tabs defaultValue="top-posts" className="flex-1">
          <TabsList className={"background-light800_dark400 min-h-[42px] p-1"}>
            <TabsTrigger className={"tab"} value="top-posts">
              Top Posts
            </TabsTrigger>
            <TabsTrigger className={"tab"} value="answers">
              Answers
            </TabsTrigger>
          </TabsList>
          <TabsContent value="top-posts">POSTS</TabsContent>
          <TabsContent value="answers">ANSWERS</TabsContent>
        </Tabs>
      </div>
    </>
  );
};

export default Page;
```

left side bar component small route logic
```tsx
"use client";
import { usePathname } from "next/navigation";
import { sidebarLinks } from "@/constants";
import Link from "next/link";
import Image from "next/image";
import { SignedOut, useAuth } from "@clerk/nextjs";
import { Button } from "@/components/ui/button";

const LeftSideBar = () => {
  const pathName = usePathname();
  const { userId } = useAuth();
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
            (pathName.includes(link.route) && link.route.length > 1);
          if (link.route === "/profile") {
            if (userId) {
              link.route = `/profile/${userId}`;
            } else {
              return null;
            }
          }
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
      {/* <SignedIn> */}
      {/*  <Button */}
      {/*    className={ */}
      {/*      "small-medium light-border-2 btn-tertiary text-dark400_light900 min-h-[41px] w-full rounded-lg px-4 py-3" */}
      {/*    } */}
      {/*  > */}
      {/*    <SignOutButton>Logout</SignOutButton> */}
      {/*  </Button> */}
      {/* </SignedIn> */}
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
![Alt text](image-172.png)

![Alt text](image-173.png)

### Create User Stats UI ✅
Stats component
```tsx
import { FC } from "react";
import { formatNumber } from "@/lib/utils";
import Image from "next/image";

type TStatsCard = {
  imageUrl: string;
  value: number;
  title: string;
};
const StatsCard: FC<TStatsCard> = ({ imageUrl, value, title }) => {
  return (
    <div className="light-border background-light900_dark300 flex flex-wrap items-center justify-start gap-4 rounded-md border p-6 shadow-light-300 dark:shadow-dark-200">
      <Image src={imageUrl} alt={title} height={50} width={40} />
      <div className="">
        <p className="paragraph-semibold text-dark200_light900">{value}</p>
        <p className="body-medium text-dark400_light900">{title}</p>
      </div>
    </div>
  );
};

type TStats = {
  totalQuestions: number;
  totalAnswers: number;
};

const Stats: FC<TStats> = ({ totalAnswers, totalQuestions }) => {
  return (
    <div className={"mt-10"}>
      <h4 className="h3-semibold text-dark200_light900">Stats</h4>
      <div className="mt-5 grid grid-cols-1 gap-5 xs:grid-cols-2 md:grid-cols-4 ">
        <div className="light-border background-light900_dark300 flex flex-wrap items-center justify-evenly gap-4 rounded-md border p-6 shadow-light-300 dark:shadow-dark-200">
          <div className="">
            <p className="paragraph-semibold text-dark200_light900">
              {formatNumber(totalQuestions)}
            </p>
            <p className="body-medium text-dark400_light900">Questions</p>
          </div>
          <div className="">
            <p className="paragraph-semibold text-dark200_light900">
              {formatNumber(totalAnswers)}
            </p>
            <p className="body-medium text-dark400_light900">Answers</p>
          </div>
        </div>
        <StatsCard
          value={0}
          title={"Gold Badges"}
          imageUrl={"/assets/icons/gold-medal.svg"}
        />{" "}
        <StatsCard
          value={0}
          title={"Silver Badges"}
          imageUrl={"/assets/icons/silver-medal.svg"}
        />{" "}
        <StatsCard
          value={0}
          title={"Bronze Badges"}
          imageUrl={"/assets/icons/bronze-medal.svg"}
        />
      </div>
    </div>
  );
};

export default Stats;
```

![Alt text](image-174.png)

using the Stats component
```tsx
import { FC } from "react";
import { URLProps } from "@/types/types";
import { getUserInfo } from "@/lib/actions/user.action";
import Image from "next/image";
import { auth, SignedIn } from "@clerk/nextjs";
import Link from "next/link";
import { Button } from "@/components/ui/button";
import { Tabs, TabsContent, TabsList, TabsTrigger } from "@/components/ui/tabs";
import { convertDate } from "@/lib/utils";
import ProfileLink from "@/components/shared/profileLink/ProfileLink";
import Stats from "@/components/shared/stats/Stats";
import QuestionTab from "@/components/shared/tabs/QuestionTab";
import AnswerTab from "@/components/shared/tabs/AnswerTab";

const Page: FC<URLProps> = async ({ params, searchParams }) => {
  const result = await getUserInfo({ userId: params.id });
  const { userId: clerkId } = auth();
  return (
    <>
      <div
        className={
          "flex flex-col-reverse items-start justify-between sm:flex-row"
        }
      >
        <div className={"flex flex-col items-start gap-4 lg:flex-row"}>
          <Image
            src={result.user.picture}
            alt={"profile picture"}
            height={128}
            width={128}
            className={"rounded-full object-cover"}
          />
          <div className="mt-3">
            <h2 className={"h2-bold text-dark100_light900"}>
              {result.user.name}
            </h2>
            <p className={"paragraph-regular text-dark200_light800"}>
              @{result.user.username}
            </p>
            <div className="mt-5 flex flex-wrap items-center justify-start gap-5">
              {result.user?.location && (
                <ProfileLink
                  imageUrl={"/assets/icons/location.svg"}
                  title={result.user?.location}
                />
              )}
              {result.user?.portfolioWebsite && (
                <ProfileLink
                  imageUrl={"/assets/icons/link.svg"}
                  href={result.user?.portfolioWebsite}
                  title={"Portfolio"}
                />
              )}
              {
                <ProfileLink
                  imageUrl={"/assets/icons/calendar.svg"}
                  title={convertDate(result.user?.joinedAt)}
                />
              }
            </div>
            {result.user?.bio && (
              <p className={"paragraph-regular text-dark400_light800 mt-8"}>
                {result.user?.bio}
              </p>
            )}
          </div>
        </div>
        <div className="flex justify-end max-sm:mb-5 max-sm:w-full sm:mt-3">
          <SignedIn>
            {clerkId === result.user.clerkId && (
              <Link href={`/profile/edit`}>
                <Button
                  className={
                    "paragraph-medium btn-secondary text-dark300_light900 min-h-[46px] min-w-[176px] px-4 py-3"
                  }
                >
                  Edit Profile
                </Button>
              </Link>
            )}
          </SignedIn>
        </div>
      </div>
      <Stats
        totalQuestions={result.totalQuestions}
        totalAnswers={result.totalAnswers}
      />
      <div className="mt-10 flex gap-10">
        <Tabs defaultValue="top-posts" className="flex-1">
          <TabsList className={"background-light800_dark400 min-h-[42px] p-1"}>
            <TabsTrigger className={"tab"} value="top-posts">
              Top Posts
            </TabsTrigger>
            <TabsTrigger className={"tab"} value="answers">
              Answers
            </TabsTrigger>
          </TabsList>
          <TabsContent value="top-posts">
            <QuestionTab />
          </TabsContent>
          <TabsContent value="answers">
            <AnswerTab />
          </TabsContent>
        </Tabs>
      </div>
    </>
  );
};

export default Page;
```

Tabs component
![Alt text](image-175.png)

![Alt text](image-176.png)

### Implement User Questions Tab ✅
create server action 
```ts
export const getUserQuestions = async (params: GetUserStatsParams) => {
  try {
    await connectToDatabase();
    const { page, pageSize, userId } = params;
    const totalQuestions = await Question.countDocuments({
      author: userId,
    });

    const userQuestions: TQuestion[] = await Question.find({
      author: userId,
    })
      .sort({
        views: -1,
        upvotes: -1,
      })
      .populate({
        path: "tags",
        model: Tag,
        select: "name _id",
      })
      .populate({
        path: "author",
        model: User,
        select: "name _id picture clerkId",
      });
    return {
      totalQuestions,
      questions: userQuestions,
    };
  } catch (error) {
    console.error(error);
    throw error;
  }
};
```

adding answertab and question tab

![Alt text](image-177.png)

```tsx
      <div className="mt-10 flex gap-10">
        <Tabs defaultValue="top-posts" className="flex-1">
          <TabsList className={"background-light800_dark400 min-h-[42px] p-1"}>
            <TabsTrigger className={"tab"} value="top-posts">
              Top Posts
            </TabsTrigger>
            <TabsTrigger className={"tab"} value="answers">
              Answers
            </TabsTrigger>
          </TabsList>
          <TabsContent value="top-posts">
            <QuestionTab
              userId={result.user._id}
              searchParams={searchParams}
              clerkId={clerkId}
            />
          </TabsContent>
          <TabsContent value="answers">
            <AnswerTab
              userId={result.user._id}
              searchParams={searchParams}
              clerkId={clerkId}
            />
          </TabsContent>
        </Tabs>
      </div>
    </>
  );
};
```

![Alt text](image-178.png)

question tab
```tsx
import { FC } from "react";
import { getUserQuestions } from "@/lib/actions/user.action";
import QuestionCard from "@/components/cards/QuestionCard";

type TQuestionTabProps = {
  userId: string;
  clerkId?: string | null;
  searchParams: { [key: string]: string | undefined };
};

const QuestionTab: FC<TQuestionTabProps> = async ({
  userId,
  searchParams,
  clerkId,
}) => {
  const result = await getUserQuestions({ userId, page: 1 });
  console.log(result);
  return (
    <div>
      {result.questions.map((question) => {
        return (
          <QuestionCard
            clerkId={clerkId}
            question={question}
            key={question._id}
          />
        );
      })}
    </div>
  );
};

export default QuestionTab;
```

### Implement User Answers Tabs ✅

server action
```ts
export const getUserAnswers = async (params: GetUserStatsParams) => {
  try {
    await connectToDatabase();
    const { page, pageSize, userId } = params;
    const totalAnswers = await Answer.countDocuments({
      author: userId,
    });

    const userAnswers: TAnswer[] = await Answer.find({
      author: userId,
    })
      .sort({
        upvotes: -1,
      })
      .populate({
        path: "question",
        model: Question,
        select: "title _id",
      })
      .populate({
        path: "author",
        model: User,
        select: "name _id picture clerkId",
      });
    return {
      totalAnswers,
      answers: userAnswers,
    };
  } catch (error) {
    console.error(error);
    throw error;
  }
};
```

AnswerCard 
```tsx

import { FC } from "react";
import Link from "next/link";
import { TAnswer } from "@/types/types";
import { getTimStamp } from "@/lib/utils";
import Metric from "@/components/shared/metric/Metric";

type TAnswerCardProps = {
  answer: TAnswer;
  clerkId?: string | null;
};

const AnswerCard: FC<TAnswerCardProps> = ({
  answer: { content, createdAt, downvotes, _id, upvotes, question, author },
  clerkId,
}) => {
  return (
    <Link
      href={`/question/${question?._id}/#${_id}`}
      className={"card-wrapper rounded-[10px] px-11 py-9"}
    >
      <div className="flex flex-col-reverse items-start justify-between gap-5 sm:flex-row">
        <div className="">
          <span className="subtle-regular text-dark400_light700 line-clamp-1 flex sm:hidden">
            {getTimStamp(createdAt)}
          </span>
          <h3
            className={
              "sm:h3-semibold base-semibold text-dark200_light900 line-clamp-1 flex-1"
            }
          >
            {question.title}
          </h3>
        </div>
      </div>

      <div className="flex-between mt-6 w-full flex-wrap gap-3">
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
          alt={"like"}
          value={upvotes.length}
          title={" Votes"}
          textStyles={"text-dark400_light800 small-medium"}
        />
      </div>
    </Link>
  );
};

export default AnswerCard;
```


Answertab component
```tsx
import { FC } from "react";
import { getUserAnswers } from "@/lib/actions/user.action";
import AnswerCard from "@/components/cards/AnswerCard";

type TAnswerTabProps = {
  userId: string;
  clerkId?: string | null;
  searchParams: { [key: string]: string | undefined };
};

const AnswerTab: FC<TAnswerTabProps> = async ({
  searchParams,
  clerkId,
  userId,
}) => {
  const result = await getUserAnswers({ userId, page: 1 });
  console.log(result);
  return (
    <>
      {result.answers.map((answer) => {
        return (
          <AnswerCard key={answer._id} answer={answer} clerkId={clerkId} />
        );
      })}
    </>
  );
};

export default AnswerTab;
```

small css fix
```tsx
      <div className="mt-10 flex gap-10">
        <Tabs defaultValue="top-posts" className="flex-1">
          <TabsList className={"background-light800_dark400 min-h-[42px] p-1"}>
            <TabsTrigger className={"tab"} value="top-posts">
              Top Posts
            </TabsTrigger>
            <TabsTrigger className={"tab"} value="answers">
              Answers
            </TabsTrigger>
          </TabsList>
          <TabsContent value="top-posts">
            <QuestionTab
              userId={result.user._id}
              searchParams={searchParams}
              clerkId={clerkId}
            />
          </TabsContent>
          <TabsContent value="answers" className={"flex w-full flex-col gap-6"}>
            <AnswerTab
              userId={result.user._id}
              searchParams={searchParams}
              clerkId={clerkId}
            />
          </TabsContent>
        </Tabs>
      </div>
    </>
  );
};

export default Page;
```
![Alt text](image-179.png)

![Alt text](image-180.png)

## Edit_Delete User Actions ✅

### Implement Edit-Delete Question-Answer Component ✅
let's create the edit question component
![Alt text](image-181.png)
```tsx
import Question from "@/components/forms/Question";
import { auth } from "@clerk/nextjs";
import { getUserById } from "@/lib/actions/user.action";
import { getQuestionById } from "@/lib/actions/question.action";
import { FC } from "react";
import { URLProps } from "@/types/types";

const Page: FC<URLProps> = async ({ params, searchParams }) => {
  const { userId } = auth();

  if (!userId) return null;
  const mongoUser = await getUserById({ userId });
  const result = await getQuestionById({
    questionId: params.id,
  });
  if (!mongoUser) return null;

  return (
    <>
      <h1 className={"h1-bold text-dark100_light900"}>Edit question</h1>
      <div className="mt-9">
        <Question
          type={"edit"}
          mongoUserId={mongoUser._id.toString()}
          questionDetails={JSON.stringify(result.question)}
        />
      </div>
    </>
  );
};

export default Page;
```

let's update the Question form component
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
import { createQuestion, editQuestion } from "@/lib/actions/question.action";
import { usePathname, useRouter } from "next/navigation";
import { useTheme } from "@/context/ThemeProvider";
import { ObjectId } from "mongoose";
import { IUser } from "@/database/user.model";
import { ITag } from "@/database/tag.model";

type TQuestionProps = {
  mongoUserId: string;
  type?: "edit";
  questionDetails?: string;
};

const formType = "edit";

const Question: FC<TQuestionProps> = ({
  mongoUserId,
  questionDetails,
  type,
}) => {
  const { theme } = useTheme();
  const [isFormSubmitting, setIsFormSubmitting] = useState(false);
  const editorRef = useRef(null);
  const router = useRouter();
  const pathName = usePathname();

  const parsedQuestionDetails: {
    _id: ObjectId;
    views: number;
    title: string;
    upvotes: any;
    downvotes: any;
    author: IUser;
    tags: ITag[];
    answers: any;
    createdAt: Date;
    content: string;
  } = JSON.parse(questionDetails || "{}");
  console.log(parsedQuestionDetails.tags);
  const form = useForm<TQuestionsSchema>({
    resolver: zodResolver(QuestionsSchema),
    defaultValues: {
      title: parsedQuestionDetails.title || "",
      explanation: parsedQuestionDetails.content || "",
      tags: parsedQuestionDetails.tags.map((item) => item.name) || [],
    },
  });
  // const log = () => {
  //   if (editorRef.current) {
  //     console.log(editorRef.current.getContent());
  //   }
  // };
  // 2. Define a submit handler.
  async function onSubmit(values: TQuestionsSchema) {
    setIsFormSubmitting(true);

    try {
      console.log(values);
      console.log("mongoUserId", mongoUserId);
      if (formType === "edit") {
        await editQuestion({
          title: values.title,
          content: values.explanation,
          path: pathName,
          questionId: parsedQuestionDetails._id.toString(),
        });
        router.push(`/question/${parsedQuestionDetails._id}`);
      } else {
        await createQuestion({
          title: values.title,
          content: values.explanation,
          tags: values.tags,
          author: JSON.parse(mongoUserId),
          path: pathName,
        });
        router.push("/");
      }
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
    if (type === "edit") return;
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
                  onBlur={field.onBlur}
                  onEditorChange={(content) => field.onChange(content)}
                  initialValue={parsedQuestionDetails.content || ""}
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
                    skin: theme === "dark" ? "oxide-dark" : "oxide",
                    content_css: theme === "dark" ? "dark" : "default",
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
                    disabled={formType === "edit"}
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
                            {type !== "edit" && (
                              <Image
                                src={"/assets/icons/close.svg"}
                                alt={"close icons"}
                                width={16}
                                height={16}
                                className={
                                  "cursor-pointer object-contain invert-0 dark:invert"
                                }
                              />
                            )}
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

![Alt text](image-182.png)

let's update the question card to show delete and edit button
```tsx
import { FC } from "react";
import { TQuestion } from "@/types/types";
import Link from "next/link";
import RenderTag from "@/components/shared/tags/RenderTag";
import Metric from "@/components/shared/metric/Metric";
import { getTimStamp } from "@/lib/utils";
import { SignedIn } from "@clerk/nextjs";
import EditDeleteAction from "@/components/shared/editDeleteAction/EditDeleteAction";

export type TQuestionCardProps = {
  question: TQuestion;
  clerkId?: string | null;
};

const QuestionCard: FC<TQuestionCardProps> = ({
  question: { _id, author, tags, title, upvotes, views, createdAt, answers },
  clerkId,
}) => {
  const showActionButton = clerkId && clerkId === author.clerkId;
  return (
    <div
      className={
        "card-wrapper my-2 rounded-[10px] border border-slate-500/10 p-9 dark:border-none sm:px-11"
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
        <SignedIn>
          {showActionButton && (
            <EditDeleteAction type={"question"} itemId={_id} />
          )}
        </SignedIn>
      </div>
    
export default QuestionCard;
```

let's do the same for the answer card
```tsx

const AnswerCard: FC<TAnswerCardProps> = ({
  answer: { content, createdAt, downvotes, _id, upvotes, question, author },
  clerkId,
}) => {
  const showActionButton = clerkId && clerkId === author.clerkId;
  return (
    <Link
      href={`/question/${question?._id}/#${_id}`}
      className={"card-wrapper my-2 rounded-[10px] px-11  py-9"}
    >
      <div className="flex flex-col-reverse items-start justify-between gap-5 sm:flex-row">
        <div className="">
          <span className="subtle-regular text-dark400_light700 line-clamp-1 flex sm:hidden">
            {getTimStamp(createdAt)}
          </span>
          <h3
            className={
              "sm:h3-semibold base-semibold text-dark200_light900 line-clamp-1 flex-1"
            }
          >
            {question.title}
          </h3>
        </div>
        <SignedIn>
          {showActionButton && (
            <EditDeleteAction type={"answer"} itemId={_id} />
          )}
        </SignedIn>
      </div>
```

edit delete Action component
```tsx
"use client";
import { FC } from "react";
import Image from "next/image";
import { deleteQuestion } from "@/lib/actions/question.action";
import { deleteAnswer } from "@/lib/actions/answer.action";
import { usePathname, useRouter } from "next/navigation";

type TEditDeleteAction = {
  type: "question" | "answer";
  itemId: string;
};

const EditDeleteAction: FC<TEditDeleteAction> = ({ itemId, type }) => {
  const pathName = usePathname();
  const router = useRouter();
  const handleEdit = () => {
    console.log("edit");
    router.push(`/question/edit/${itemId}`);
  };

  const handleDelete = async () => {
    if (type === "question") {
      await deleteQuestion({
        path: pathName,
        questionId: itemId,
      });
    } else if (type === "answer") {
      await deleteAnswer({
        path: pathName,
        answerId: itemId,
      });
    }
  };

  return (
    <div className={"flex items-center justify-end gap-3 max-sm:w-full"}>
      {type === "question" && (
        <Image
          src={"/assets/icons/edit.svg"}
          alt={"edit"}
          height={14}
          width={14}
          className={"cursor-pointer object-contain"}
          onClick={handleEdit}
        />
      )}
      <Image
        src={"/assets/icons/trash.svg"}
        alt={"delete"}
        height={14}
        width={14}
        className={"cursor-pointer object-contain"}
        onClick={handleDelete}
      />
    </div>
  );
};

export default EditDeleteAction;
```
![Alt text](image-183.png)

### Create Edit Question Page ✅

server action 
```ts
export const deleteQuestion = async (params: DeleteQuestionParams) => {
  try {
    await connectToDatabase();
    const { questionId, path } = params;

    await Question.deleteOne({ _id: questionId });
    // delete answers associated with the question
    await Answer.deleteMany({ question: questionId });

    await Interaction.deleteMany({ question: questionId });

    await Tag.updateMany(
      {
        questions: questionId,
      },
      {
        $pull: {
          questions: questionId,
        },
      },
    );
    revalidatePath(path);
  } catch (e) {
    console.error(e);
    throw e;
  }
};

export const editQuestion = async (params: EditQuestionParams) => {
  try {
    await connectToDatabase();
    const { title, content, questionId, path } = params;
    const question = await Question.findById(questionId);

    if (!question) {
      throwError("Question not found");
    }

    question.title = title;
    question.content = content;

    await question.save();

    revalidatePath(path);
  } catch (e) {
    console.error(e);
    throw e;
  }
};

```
```ts
export const deleteAnswer = async (params: DeleteAnswerParams) => {
  try {
    await connectToDatabase();
    const { answerId, path } = params;

    const answer: IAnswer | null = await Answer.findById(answerId);

    if (answer === null) {
      throwError("Answer not found");
      return;
    }

    await Answer.deleteOne({ _id: answerId });

    await Question.updateMany(
      { _id: answer.question },
      {
        $pull: { answers: answerId },
      },
    );

    await Interaction.deleteMany({ answer: answerId });

    revalidatePath(path);
  } catch (e) {
    console.error(e);
    throw e;
  }
};

```

### Create Edit Profile Page ✅

let's install textArea component
```bash
npx shadcn-ui@latest add textarea
```

form schema
```ts

export const ProfileFormSchema = z.object({
  name: z.string().min(5).max(50),
  username: z.string().min(5).max(50),
  bio: z.string().min(10).max(160),
  portfolioWebsite: z.string().url(),
  location: z.string().min(5).max(50),
});

export type TProfileFormSchema = z.infer<typeof ProfileFormSchema>;
export type TQuestionsSchema = z.infer<typeof QuestionsSchema>;
export type TAnswerSchema = z.infer<typeof AnswerSchema>;

```

Question Form component
```tsx
  const parsedQuestionDetails: {
    _id: ObjectId;
    views: number;
    title: string;
    upvotes: any;
    downvotes: any;
    author: IUser;
    tags: ITag[];
    answers: any;
    createdAt: Date;
    content: string;
  } = JSON.parse(questionDetails || "{}");
  console.log(parsedQuestionDetails.tags);
  const form = useForm<TQuestionsSchema>({
    resolver: zodResolver(QuestionsSchema),
    defaultValues: {
      title: parsedQuestionDetails?.title || "",
      explanation: parsedQuestionDetails?.content || "",
      tags: parsedQuestionDetails?.tags?.map((item) => item.name) || [],
    },
  });
```
![Alt text](image-184.png)

profile edit page
```tsx
import { auth } from "@clerk/nextjs";
import { getUserById } from "@/lib/actions/user.action";
import { FC } from "react";
import { URLProps } from "@/types/types";
import Profile from "@/components/forms/Profile";

const Page: FC<URLProps> = async ({ params, searchParams }) => {
  const { userId } = auth();

  if (!userId) return null;
  const mongoUser = await getUserById({ userId });
  if (!mongoUser) return null;

  return (
    <>
      <h1 className={"h1-bold text-dark100_light900"}>Edit Profile</h1>
      <div className="mt-9">
        <Profile clerkId={userId} user={JSON.stringify(mongoUser)} />
      </div>
    </>
  );
};

export default Page;
```
Profile Form component
```tsx
"use client";
import { FC, useState } from "react";
import { IUser } from "@/database/user.model";
import {
  Form,
  FormControl,
  FormField,
  FormItem,
  FormLabel,
  FormMessage,
} from "@/components/ui/form";
import { useForm } from "react-hook-form";
import { zodResolver } from "@hookform/resolvers/zod";
import { Input } from "@/components/ui/input";
import { Button } from "@/components/ui/button";
import { Textarea } from "@/components/ui/textarea";
import { ProfileFormSchema, TProfileFormSchema } from "@/lib/validations";
import { usePathname, useRouter } from "next/navigation";
import { updateUser } from "@/lib/actions/user.action";

type TProfileProps = {
  clerkId: string;
  user: string;
};

const Profile: FC<TProfileProps> = ({ user, clerkId }) => {
  const [isSubmitting, setIsSubmitting] = useState(false);
  const parsedUser: IUser = JSON.parse(user);
  const router = useRouter();
  const pathName = usePathname();
  const form = useForm<TProfileFormSchema>({
    resolver: zodResolver(ProfileFormSchema),
    defaultValues: {
      name: parsedUser.name || "",
      username: parsedUser.username || "",
      portfolioWebsite: parsedUser.portfolioWebsite || "",
      location: parsedUser.location || "",
      bio: parsedUser.bio || "",
    },
  });

  const onSubmit = async (values: TProfileFormSchema) => {
    setIsSubmitting(true);

    try {
      await updateUser({
        updateData: {
          name: values.name,
          username: values.username,
          portfolioWebsite: values.portfolioWebsite,
          location: values.location,
          bio: values.bio,
        },
        clerkId,
        path: pathName,
      });

      router.back();
      console.log(values);
    } catch (e) {
      console.log(e);
      throw e;
    } finally {
      setIsSubmitting(false);
    }
    console.log("submit");
  };
  return (
    <Form {...form}>
      <form
        onSubmit={form.handleSubmit(onSubmit)}
        className={"mt-9 flex w-full flex-col gap-9"}
      >
        <FormField
          control={form.control}
          name="name"
          render={({ field }) => (
            <FormItem className={"space-y-3.5 "}>
              <FormLabel>
                Name <span className="text-primary-500">*</span>
              </FormLabel>
              <FormControl>
                <Input
                  className={
                    "text-dark300_light700 background-light700_dark300 no-focus paragraph-regular light-border-2 min-h-[56px] border"
                  }
                  placeholder="your name"
                  {...field}
                />
              </FormControl>
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
          name="username"
          render={({ field }) => (
            <FormItem className={"space-y-3.5 "}>
              <FormLabel>
                Username <span className="text-primary-500">*</span>
              </FormLabel>
              <FormControl>
                <Input
                  className={
                    "text-dark300_light700 background-light700_dark300 no-focus paragraph-regular light-border-2 min-h-[56px] border"
                  }
                  placeholder="your username"
                  {...field}
                />
              </FormControl>
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
          name="portfolioWebsite"
          render={({ field }) => (
            <FormItem className={"space-y-3.5 "}>
              <FormLabel>Portfolio website</FormLabel>
              <FormControl>
                <Input
                  type={"url"}
                  className={
                    "text-dark300_light700 background-light700_dark300 no-focus paragraph-regular light-border-2 min-h-[56px] border"
                  }
                  placeholder="your portfolio URL"
                  {...field}
                />
              </FormControl>
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
          name="location"
          render={({ field }) => (
            <FormItem className={"space-y-3.5 "}>
              <FormLabel>Location</FormLabel>
              <FormControl>
                <Input
                  type={"text"}
                  className={
                    "text-dark300_light700 background-light700_dark300 no-focus paragraph-regular light-border-2 min-h-[56px] border"
                  }
                  placeholder="where are you from?"
                  {...field}
                />
              </FormControl>
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
          name="bio"
          render={({ field }) => (
            <FormItem className={"space-y-3.5 "}>
              <FormLabel>Bio</FormLabel>
              <FormControl>
                <Textarea
                  className={
                    "text-dark300_light700 background-light700_dark300 no-focus paragraph-regular light-border-2 min-h-[56px] border"
                  }
                  placeholder="what's your story?"
                  {...field}
                />
              </FormControl>
              <FormMessage
                className={
                  "rounded bg-red-500/10 py-2 text-center text-red-500"
                }
              />
            </FormItem>
          )}
        />
        <div className="mt-7 justify-end">
          <Button
            disabled={isSubmitting}
            className={"primary-gradient w-fit"}
            type="submit"
          >
            {isSubmitting ? "Saving..." : "Save"}
          </Button>
        </div>
      </form>
    </Form>
  );
};

export default Profile;
```

![Alt text](image-185.png)

## Show Top Results ✅

### Show Top Questions ✅
server action for top questions
```ts
export const getHotQuestions = async () => {
  try {
    await connectToDatabase();

    const questions = await Question.find({})
      .sort({
        views: -1,
        upvotes: -1,
      })
      .limit(5);
    return questions as IQuestion[];
  } catch (e) {
    console.log(e);
    throw e;
  }
};
```
![Alt text](image-186.png)

use the action in the RighSideBar component

```tsx

const RightSideBar = async () => {
  const hotQuestions = await getHotQuestions();
  return (
    <section
      className={
        "background-light900_dark200 light-border custom-scrollbar sticky right-0 top-0 flex h-screen w-[350px] flex-col overflow-y-auto border-l p-6 pt-36 shadow-light-300 dark:shadow-none max-xl:hidden"
      }
    >
      <div className="">
        <h3 className="h3-bold text-dark300_light900">Top Questions</h3>
        <div className="mt-7 flex w-full flex-col gap-[30px]">
          {hotQuestions.map((question) => {
            return (
              <Link
                key={question._id}
                href={`/question/${question._id}`}
                className={
                  "flex cursor-pointer items-center  justify-between gap-7"
                }
              >
```            
### Show Popular Tags ✅

get polular tags action

```ts
// This function returns the ten most popular tags

export const getPopularTags = async () => {
  try {
    await connectToDatabase();
    const tags = await Tag.aggregate([
      {
        $project: { name: 1, numberOsQuestions: { $size: "$questions" } },
      },
      { $sort: { numberOsQuestions: -1 } },
      { $limit: 10 },
    ]);
    return tags;
  } catch (error) {
    console.error(error);
    throw error;
  }
};

```
Here is the explanation for the code above:
1. First, we connect to the database using the connectToDatabase function we created in the previous step.
2. Then, we aggregate all the tags using the aggregate function of the mongoose object.
3. In the first stage of the aggregation, we project the name and the size of the questions array of each tag. We use the $size aggregation operator to get the number of questions of each tag.
4. In the second stage, we sort the tags by the number of questions in descending order. This way, we get the most popular tags first.
5. Finally, we limit the results to 10 tags.


here we are using the server action in the RightSideBar component
```tsx
import Link from "next/link";
import Image from "next/image";
import RenderTag from "@/components/shared/tags/RenderTag";
import { getHotQuestions } from "@/lib/actions/question.action";
import { getPopularTags } from "@/lib/actions/tag.action";

const popluarTags = [
  {
    _id: 1,
    title: "React",
    totalQuestions: 100,
  },
  {
    _id: 2,
    title: "Next.js",
    totalQuestions: 42,
  },
  {
    _id: 3,
    title: "React Query",
    totalQuestions: 10,
  },
];
const RightSideBar = async () => {
  const hotQuestions = await getHotQuestions();
  const popluarTags = await getPopularTags();
  console.log(popluarTags);
  return (
    <section
      className={
        "background-light900_dark200 light-border custom-scrollbar sticky right-0 top-0 flex h-screen w-[350px] flex-col overflow-y-auto border-l p-6 pt-36 shadow-light-300 dark:shadow-none max-xl:hidden"
      }
    >
      <div className="">
        <h3 className="h3-bold text-dark300_light900">Top Questions</h3>
        <div className="mt-7 flex w-full flex-col gap-[30px]">
          {hotQuestions.map((question) => {
            return (
              <Link
                key={question._id}
                href={`/question/${question._id}`}
                className={
                  "flex cursor-pointer items-center  justify-between gap-7"
                }
              >
                <p className={"body-medium text-dark500_light700"}>
                  {question.title}
                </p>
                <Image
                  src={"/assets/icons/chevron-right.svg"}
                  alt={"chevron-right"}
                  width={20}
                  height={20}
                  className={"invert-colors"}
                />
              </Link>
            );
          })}
        </div>
      </div>
      <div className="mt-16">
        <h3 className="h3-bold text-dark300_light900">Popular Tags</h3>
        <div className="mt-7 flex flex-col gap-4">
          {popluarTags.map((tag) => {
            return (
              <RenderTag
                _id={tag._id}
                totalQuestions={tag.numberOsQuestions}
                name={tag.name}
                showCount
                key={tag._id}
              />
            );
          })}
        </div>
      </div>
    </section>
  );
};

export default RightSideBar;
```

![Alt text](image-187.png)


## The Local Search Functionality 🔲

### Manage search state ✅

![Alt text](image-188.png)

```shell
npm install query-string  
```
util function
```ts
interface UrlQueryParams {
  params: string;
  key: string;
  value: string | null;
}

export const formatUrlQuery = ({ key, value, params }: UrlQueryParams) => {
  const currentUrl = qs.parse(params);
  currentUrl[key] = value;
  return qs.stringifyUrl(
    {
      url: window.location.pathname,
      query: currentUrl,
    },
    {
      skipNull: true,
    },
  );
};

export const removeKeysFromQuery = ({
  keys,
  params,
}: {
  keys: string[];
  params: string;
}) => {
  const currentUrl = qs.parse(params);
  keys.forEach((k) => {
    delete currentUrl[k];
  });
  return qs.stringifyUrl(
    {
      url: window.location.pathname,
      query: currentUrl,
    },
    {
      skipNull: true,
    },
  );
};
```
LocalSearch component
```tsx
"use client";

import { FC, useEffect, useState } from "react";
import Image from "next/image";
import { Input } from "@/components/ui/input";
import { usePathname, useRouter, useSearchParams } from "next/navigation";
import { formatUrlQuery, removeKeysFromQuery } from "@/lib/utils";

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
  const router = useRouter();
  const pathName = usePathname();
  const searchParams = useSearchParams();

  const query = searchParams.get("q");
  const [search, setSearch] = useState(query || "");
  useEffect(() => {
    const delayDebounceFn = setTimeout(() => {
      if (search) {
        const newUrl = formatUrlQuery({
          params: searchParams.toString(),
          key: "q",
          value: search,
        });
        router.push(newUrl, { scroll: false });
      } else {
        if (pathName === route) {
          const newUrl = removeKeysFromQuery({
            params: searchParams.toString(),
            keys: ["q"],
          });
          router.push(newUrl, { scroll: false });
        }
      }
    }, 500);

    return () => clearTimeout(delayDebounceFn);
  }, [search, pathName, router, searchParams, query, route]);

```

![Alt text](image-189.png)


### Implement Search functionality for the Home page ✅
```ts
import { FilterQuery, ObjectId } from "mongoose";

export async function getQuestions(params: IGetQuestionsParams) {
  const { searchQuery } = params;

  const query: FilterQuery<typeof Question> = {};

  if (searchQuery) {
    query.$or = [
      { title: { $regex: new RegExp(searchQuery, "i") } },
      { content: { $regex: new RegExp(searchQuery, "i") } },
    ];
  }
  try {
    await connectToDatabase();
    const questions = await Question.find(query)
      .populate({
        path: "tags",
        model: Tag,
      })
      .populate({
        path: "author",
        model: User,
      })
      .sort({ createdAt: -1 });
    return { questions };
  } catch (error) {
    console.error(error);
    throw error;
  }
}
```
adding the integration in the Home page
```tsx
import { SearchParamsProps, TQuestion } from "@/types/types";

export default async function Home({ searchParams }: SearchParamsProps) {
  const { questions } = await getQuestions({
    searchQuery: searchParams.q,
  });
```
![Alt text](image-190.png)

### Implement Search functionality for the Community page ✅

server component
```ts
export const getAllUsers = async (params: GetAllUsersParams) => {
  try {
    const { searchQuery } = params;
    console.log(searchQuery);
    const query: FilterQuery<typeof User> = {};

    if (searchQuery) {
      query.$or = [
        {
          name: { $regex: new RegExp(searchQuery, "i") },
          username: { $regex: new RegExp(searchQuery, "i") },
        },
      ];
    }

    await connectToDatabase();
    const users = await User.find(query).sort({
      createdAt: -1,
    });

    return {
      users,
    };
  } catch (error) {
    console.error(error);
    throw error;
  }
};
```

let's add the integration in the community page
```tsx
import { SearchParamsProps } from "@/types/types";
import { FC } from "react";

const CommunityPage: FC<SearchParamsProps> = async ({ searchParams }) => {
  const results = await getAllUsers({
    searchQuery: searchParams.q,
  });
```
### Implement Search functionality for the Collection page ✅
let's add the integration in the collection page
```tsx
import LocalSearch from "@/components/shared/search/LocalSearch";
import Filter from "@/components/shared/filters/Filter";
import { QuestionFilters } from "@/constants/filters";
import NoResult from "@/components/shared/noResult/NoResult";
import QuestionCard from "@/components/cards/QuestionCard";
import { SearchParamsProps, TQuestion } from "@/types/types";
import { getSavedQuestion } from "@/lib/actions/user.action";
import { auth } from "@clerk/nextjs";
import { FC } from "react";

const CollectionPage: FC<SearchParamsProps> = async ({ searchParams }) => {
  const { userId } = auth();

  if (!userId) return null;

  const { questions } = await getSavedQuestion({
    clerkId: userId,
    searchQuery: searchParams.q,
  });
  return (
    <>
      <h1 className={"h1-bold text-dark100_light900"}>Saved Questions</h1>

      <div className="mt-11 flex justify-between gap-5 max-sm:flex-col sm:items-center">
        <LocalSearch
          imageSrc={"/assets/icons/search.svg"}
          route={"/collection"}
          iconPosition={"left"}
          placeholder={"Search Questions ..."}
          otherClasses={"flex-1"}
        />
```

server action
```ts
export const getSavedQuestion = async (params: GetSavedQuestionsParams) => {
  try {
    await connectToDatabase();
    const { searchQuery, clerkId } = params;
    const query: FilterQuery<typeof Question> = {};
    if (searchQuery) {
      query.$or = [
        {
          title: { $regex: new RegExp(searchQuery, "i") },
        },
      ];
    }

    const user = await User.findOne({ clerkId }).populate({
      path: "saved",
      match: query,
      options: {
        sort: {
          createdAt: -1,
        },
        populate: [
          {
            path: "tags",
            model: Tag,
            select: "name _id",
          },
          {
            path: "author",
            model: User,
            select: "name _id clerkId picture",
          },
        ],
      },
    });

    if (!user) {
      throwError("User not found");
    }

    const savedQuestions = user.saved;

    return {
      questions: savedQuestions,
    };
  } catch (error) {
    console.error(error);
    throw error;
  }
};
```
### Implement Search functionality for the Tags page ✅
![Alt text](image-192.png)
![Alt text](image-191.png)

tags id page 

![Alt text](image-193.png)

```tsx
import { SearchParamsProps } from "@/types/types";

const TagsPage: FC<SearchParamsProps> = async ({ searchParams }) => {
  const results = await getAllTags({
    searchQuery: searchParams.q,
  });
```

server action 
```ts
export const getAllTags = async (params: GetAllTagsParams) => {
  const { searchQuery } = params;
  const query: FilterQuery<typeof Tag> = {};
  if (searchQuery) {
    query.$or = [
      {
        name: { $regex: new RegExp(searchQuery, "i") },
      },
    ];
  }
  try {
    await connectToDatabase();
    const tags = await Tag.find(query);
    return { tags };
  } catch (error) {
    console.error(error);
    throw error;
  }
};

export const getQuestionByTagId = async (params: GetQuestionsByTagIdParams) => {
  try {
    await connectToDatabase();
    const { tagId, searchQuery } = params;
    const query: FilterQuery<typeof Question> = {};

    if (searchQuery) {
      query.$or = [
        {
          title: { $regex: new RegExp(searchQuery, "i") },
        },
      ];
    }

    const tag = await Tag.findOne({
      _id: tagId,
    }).populate({
      path: "questions",
      model: Question,
      match: query,
      options: {
        sort: {
          createdAt: -1,
        },
        populate: [
          {
            path: "tags",
            model: Tag,
            select: "name _id",
          },
          {
            path: "author",
            model: User,
            select: "name _id clerkId picture",
          },
        ],
      },
    });

    if (!tag) {
      throwError("Tag not found");
    }

    const questions = tag.questions;

    return {
      tagTitle: tag.name,
      questions,
    };
  } catch (e) {
    console.log(e);
    throw e;
  }
};
```

## The Filters 🔲

### Manage Filter state ✅
HomeFilters component
```tsx
"use client";
import { HOME_PAGE_FILTERS } from "@/constants/filters";
import { Button } from "@/components/ui/button";
import { useRouter, useSearchParams } from "next/navigation";
import { useState } from "react";
import { formatUrlQuery } from "@/lib/utils";

type filterType = "newest" | "recommended" | "frequent" | "unanswered";
const HomeFilter = () => {
  const searchParams = useSearchParams();
  const [active, setActive] = useState<filterType | undefined>("recommended");
  const router = useRouter();
  const handleTypeClick = (type: filterType) => {
    if (active === type) {
      setActive(undefined);
      const newUrl = formatUrlQuery({
        params: searchParams.toString(),
        key: "filter",
        value: null,
      });
      router.push(newUrl, { scroll: false });
    } else {
      setActive(type);
      const newUrl = formatUrlQuery({
        params: searchParams.toString(),
        key: "filter",
        value: type,
      });
      router.push(newUrl, { scroll: false });
    }
  };
  return (
    <div className="mt-10 hidden flex-wrap gap-3 md:flex ">
      {HOME_PAGE_FILTERS.map((filter) => (
        <Button
          className={`body-medium rounded-lg px-6 py-3 capitalize shadow-none ${
            active === filter.value
              ? "bg-primary-100 text-primary-500"
              : "bg-light-800 text-light-500 hover:bg-light-900 dark:bg-dark-300 dark:text-light-500"
          }`}
          key={filter.value}
          onClick={() => {
            handleTypeClick(filter.value);
          }}
        >
          {filter.name}
        </Button>
      ))}
    </div>
  );
};
export default HomeFilter;
```
### Integrate Filters on Home page
### Integrate Filters on the Community page
### Integrate Filters on the Collection page
### Integrate Filters for Tags and Answers

## The Pagination 🔲

### Create Pagination component
### Implement pagination on the Home page
### Implement pagination for the rest of the pages

## Global Search 🔲
### Create the Global Search UI
### Create GlobalSearch Result Component
### Create Global Search Filters
### Implement the GlobalSearch action


## Reputation 🔲
### What is Reputation and how to approach it
### Implement Reputation points for Questions
### Implement Reputation points for Answers
### More on Reputation and how to extend it


## Badge System 🔲
### Implement the Badge System

## Generate AI Answer 🔲
### Setup AI Answer feature
### Implement the API route for the AI feature
### Display the AI results on the UI






## Loadings _ Toasts 🔲
### Setup AI Answer feature
### Create a Loading state for the Community page
### Create Loading states for the rest of the pages
### Create toasts for a few actions


## Meta Data 🔲
### What is Metadata and how to implement it

## Bug Fixing and Recommendation 🔲

### Fix bugs and implement Recommendations.

## Next.js 13.5+ 🔲
### Upgrade Next.js to the latest version

## Deployment 🔲
### Deploy the application

