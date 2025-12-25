# Yash Kamra's Personal Portfolio

This is the repository for my personal portfolio website, designed to showcase my skills, professional experience, and the projects I have worked on. The site is built with modern web technologies, featuring a clean, responsive design and smooth animations.

## About Me

I'm a passionate B.Tech in Information Technology student at Manipal University Jaipur, with a strong foundation in computer science fundamentals like data structures, algorithms, and software engineering. My primary focus is on Python and SQL.

I am actively exploring the Generative AI space, data engineering, and automation, with a goal of building practical, domain-specific AI solutions in fields like legal-tech and education. My work involves creating intelligent search systems, AI-driven research tools, content generation pipelines, and large-scale data processing systems.

In 2019, I was a winner of the National RoboCup and had the honor of representing my country at the RoboCup World Finals in Sydney. When I'm not coding, you'll find me exploring new technologies, contributing to open-source projects, or sharing knowledge with the developer community.

## Live Demo

[Link to your live portfolio URL once deployed]

## Features

-   **Modern Design**: A clean and elegant UI built with Tailwind CSS.
-   **Responsive Layout**: Looks great on all devices, from mobile phones to desktops.
-   **Dynamic Sections**: Includes sections for About, Experience, Projects, Testimonials, and a functional Contact form.
-   **Interactive UI**: Smooth animations and hover effects to enhance user experience.
-   **EmailJS Integration**: The contact form is fully functional and sends inquiries directly to my email.
-   **Downloadable CV**: A dedicated button allows visitors to download my resume.

## Tech Stack

-   **Framework**: [React](https://reactjs.org/) via [Vite](https://vitejs.dev/)
-   **Styling**: [Tailwind CSS](https://tailwindcss.com/)
-   **Animations**: CSS animations and transitions
-   **Icons**: [Lucide React](https://lucide.dev/guide/packages/lucide-react)
-   **Email Service**: [EmailJS](https://www.emailjs.com/)

## Getting Started

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Set up environment variables:**
    Create a `.env` file in the root of the project and add your EmailJS credentials. You can find these keys in your EmailJS account settings.

    ```env
    VITE_EMAILJS_SERVICE_ID=your_service_id
    VITE_EMAILJS_TEMPLATE_ID=your_template_id
    VITE_EMAILJS_PUBLIC_KEY=your_public_key
    ```

4.  **Run the development server:**
    ```bash
    npm run dev
    ```
    The application will be available at `http://localhost:5173`.

## Customization

This portfolio is designed to be easily customizable. To personalize it for your own use, follow these steps:

1.  **Update Personal Information**:
    -   Go to `src/sections/` and edit the content within each component (`Hero.jsx`, `About.jsx`, `Experience.jsx`, `Projects.jsx`, `Testimonials.jsx`). The data is stored in arrays at the top of each file.

2.  **Replace Images & Assets**:
    -   **Profile Picture**: Replace `public/yash.png` with your own photo.
    -   **Resume**: Replace `public/yash_zs.pdf` with your own CV file. Make sure to update the link in `src/sections/Hero.jsx` if you change the filename.
    -   **Project Images**: Replace the placeholder images in `public/projects/` with screenshots of your projects.
    -   **Favicon**: Replace `public/vite.svg` with your own favicon.

3.  **Configure Contact Form**:
    -   Sign up for a free [EmailJS](https://www.emailjs.com/) account.
    -   Create a new email service and a new email template.
    -   Update the `.env` file with your new Service ID, Template ID, and Public Key.

## Deployment

This is a static React application that can be deployed to any modern hosting platform.

1.  **Build the project:**
    ```bash
    npm run build
    ```
    This command generates a `dist` folder with the optimized production build.

2.  **Deploy**:
    Upload the contents of the `dist` folder to a hosting provider like [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/), or [Firebase Hosting](https://firebase.google.com/docs/hosting).

## Contact

-   **LinkedIn**: [https://www.linkedin.com/in/yash-kamra-a9aa73259/](https://www.linkedin.com/in/yash-kamra-a9aa73259/)
-   **GitHub**: [https://github.com/smartyash11](https://github.com/smartyash11)
