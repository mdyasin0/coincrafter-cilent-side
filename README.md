# coincrafter

A responsive, role-based micro-tasking and earning platform that connects task creators (Buyers) with task performers (Workers). Users can create tasks, complete assignments, earn virtual coins, purchase additional coins, and manage their activities through dedicated dashboards.

**Live Website:** https://coincraft-a9594.web.app

**Project Type:** Full-Stack MERN Application  
**Repository:** Client-side (Frontend)

---

## Project Overview

The Micro-Task and Earning Platform provides an interactive environment where Buyers can publish small tasks and Workers can complete those tasks in exchange for virtual coins.

The application offers three role-based interfaces: Worker, Buyer, and Admin. Each role provides dedicated navigation, dashboards, and functionality according to the user's permissions.

This frontend application focuses on responsive UI development, user authentication, role-based navigation, task management interfaces, submission workflows, payment integration, and account management.

## Key Features

### 1. Authentication and User Management

- Email and password-based user registration and login.
- Google authentication integration.
- Role selection during registration (Worker or Buyer).
- Registration form validation and error handling.
- Role-based dashboard navigation.
- Protected routes for authenticated users.
- User profile and account information display.
- Initial coin balance displayed according to the assigned user role.

### 2. Responsive Homepage

- Modern homepage with an interactive hero banner slider.
- Swiper-powered carousel functionality.
- Top six Workers displayed based on available coins.
- Testimonial section with user feedback.
- Additional informational sections.
- Scroll-based animations using AOS.
- Responsive navigation bar and footer.
- Responsive layouts for mobile, tablet, and desktop devices.

### 3. Worker Dashboard

Workers can access dedicated dashboard features to manage their tasks and earnings.

- Worker dashboard with submission and earning statistics.
- Browse available tasks with remaining worker requirements.
- View detailed task information and submission instructions.
- Submit completed work through a submission form.
- Track personal submission history.
- View approved submissions.
- Monitor pending and approved submission statuses.
- View available coins and estimated withdrawal amounts.
- Submit withdrawal requests through supported payment methods.

### 4. Buyer Dashboard

Buyers can manage their tasks, review submissions, and purchase coins.

- Buyer dashboard with task and payment statistics.
- Create new tasks using a dedicated task form.
- Upload task images using ImgBB integration.
- View and manage previously created tasks.
- Update task titles, descriptions, and submission instructions.
- Delete tasks through the task management interface.
- Review Worker submissions.
- View submission details through a modal interface.
- Approve or reject submitted work.
- Purchase additional coins through Stripe payment integration.
- View previous transactions through the payment history page.

### 5. Admin Dashboard

The Admin interface provides dedicated controls for managing platform activities.

- Admin dashboard with platform statistics.
- View Worker and Buyer information.
- Manage registered users.
- View user profiles, roles, and coin balances.
- Remove users through the user management interface.
- Update user roles (Worker, Buyer, and Admin).
- View and manage platform tasks.
- Review pending withdrawal requests.
- Process withdrawal requests through the administrative interface.

### 6. Coin and Payment Features

The application includes a coin-based reward and payment interface.

**Coin Purchase Packages**

| Coins | Price |
|---:|---:|
| 10 Coins | $1 |
| 150 Coins | $10 |
| 500 Coins | $20 |
| 1000 Coins | $35 |

**Worker Withdrawal Rules**

- 20 coins = $1.
- Minimum withdrawal: 200 coins ($10).
- Withdrawal amount is calculated automatically based on the entered coin quantity.
- Available payment methods include bKash, Rocket, and Nagad.
- Workers can submit withdrawal requests and track their status.

### 7. Payment Integration

- Stripe integration for coin purchases.
- Stripe Test Mode payment flow.
- Multiple coin purchasing packages.
- Payment-related user interface and transaction history.


### 8. Image Upload Integration

- ImgBB integration for image hosting.
- Profile picture upload functionality.
- Task image upload functionality.

### 9. User Interface and Experience

- Fully responsive layouts for mobile, tablet, and desktop devices.
- Role-specific dashboard navigation.
- Reusable React components.
- Interactive forms and modals.
- Consistent styling with Tailwind CSS and DaisyUI.
- Loading states and user feedback.
- SweetAlert2 integration for alerts and confirmation dialogs.
- Icon-based navigation and interface elements.

---

## Technology Stack

### Core Frontend Technologies

- [React.js](https://react.dev/) – Component-based user interface development.
- [Vite](https://vite.dev/) – Frontend development and build tooling.
- [React Router](https://reactrouter.com/) – Client-side routing and navigation.
- [Axios](https://axios-http.com/) – HTTP requests and API communication.

### Styling and UI Frameworks

- [Tailwind CSS](https://tailwindcss.com/) – Utility-first CSS framework.
- [DaisyUI](https://daisyui.com/) – Tailwind CSS component library.

### Authentication and Payment Integration

- [Firebase](https://firebase.google.com/) – User authentication.
- [Stripe](https://stripe.com/) – Payment integration.
- [ImgBB](https://imgbb.com/) – Image hosting integration.

### UI Interaction and Animation

- [Swiper](https://swiperjs.com/) – Responsive sliders and carousels.
- [AOS](https://michalsnik.github.io/aos/) – Scroll-based animations.
- [SweetAlert2](https://sweetalert2.github.io/) – Alerts and confirmation dialogs.

### Charts and Icons

- [Chart.js](https://www.chartjs.org/) – Data visualization.
- [Recharts](https://recharts.org/) – React chart components.
- [Lucide React](https://lucide.dev/) – Interface icons.
- [React Icons](https://react-icons.github.io/react-icons/) – Icon library.

---

## User Roles and Interface

| Role | Frontend Capabilities |
|---|---|
| Worker | Browse tasks, submit work, view submissions, track earnings, and request withdrawals. |
| Buyer | Create and manage tasks, review submissions, purchase coins, and view payment history. |
| Admin | Manage users, update roles, manage tasks, and process withdrawal requests. |

---

## Getting Started

Follow these steps to run the frontend application locally.

### Prerequisites

- Node.js
- npm
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/mdyasin0/coincrafter-cilent-side.git
```

### 2. Navigate to the Project Directory

```bash
cd YOUR_PROJECT_DIRECTORY
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the project root directory and configure the frontend environment variables required by the application.

#  firebase key

 VITE_apiKey =
 VITE_authDomain=
 VITE_projectId=
 VITE_storageBucket=
 VITE_messagingSenderId=
 VITE_appId=

# imgbb key

VITE_IMGBB_API_KEY=

# stripe

VITE_stripe=

**Security Note:** Frontend environment variables used by Vite are exposed in the browser bundle. Never store Stripe secret keys, MongoDB credentials, Firebase service-account private keys, or other server-side secrets in the client-side environment.

### 5. Run the Development Server

```bash
npm run dev
```

The Vite development server will provide a local URL in the terminal.

### 6. Build for Production

```bash
npm run build
```

---

## Project Highlights

- Multi-role frontend application with dedicated dashboard experiences.
- Interactive task browsing and submission interfaces.
- Responsive design across different screen sizes.
- Google and email-based authentication interfaces.
- Stripe Test Mode payment integration.
- Dynamic coin purchasing and withdrawal interfaces.
- ImgBB-based image upload functionality.
- Interactive charts, sliders, and animations.
- Reusable and component-based React architecture.
- Consistent UI design using Tailwind CSS and DaisyUI.

---

## Author

**MD Yasin**

- **Email:** mdyasin48902@gmail.com
- **GitHub:** [github.com/mdyasin0](https://github.com/mdyasin0)

---

*Developed as a MERN Stack Junior Developer assessment project.*
