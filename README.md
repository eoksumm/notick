
---

# Notick

**Notick** is a streamlined clone of the popular productivity tool, Notion, offering an intuitive platform for creating, organizing, and managing your notes. Whether for personal or professional use, Notick enables users to seamlessly structure their thoughts, tasks, and documents in a flexible workspace designed for productivity.

This project leverages **Pocketbase** as the real-time backend, ensuring fast data synchronization and efficient file management. The frontend is built with **Shadcn/UI** and **Tailwind CSS**, providing a sleek, modern design. For data fetching and management, **@tanstack/query 5** is used to ensure smooth, optimized data handling. Secure user authentication is integrated to protect your notes, while maintaining a user-friendly experience.

## Live Demo

Explore **Notick** in action: [https://notick-mu.vercel.app/](https://notick-mu.vercel.app/)

## Key Features

**Efficient Note Management**

- 📝 Powerful note editor, inspired by Notion, for rich-text formatting and note-taking
- 📂 Nestable, unlimited document hierarchy for superior organization
- ↔️ Fully responsive, expandable sidebar for streamlined navigation
- 🎨 Custom document icons that refresh dynamically with changes
- 🗑️ Soft delete with a trash bin, allowing note recovery at any time

**Enhanced User Experience**

- 🌓 Supports Light and Dark modes, catering to user preferences
- 📱 Fully responsive design for optimal usage across mobile, tablet, and desktop devices
- 🖼️ Customizable document cover images for a personalized touch
- 🛬 An engaging landing page offering easy access to key features

**Data Management**

- 🔄 Real-time database to keep your data instantly updated
- 📤📥 Comprehensive file management with upload, deletion, and replacement options

**Security and Collaboration**

- 🔐 Secure user authentication to safeguard your data
- 🌍 Shareable notes: easily publish notes to the web for broader access or collaboration

## Technology Stack

Notick is powered by cutting-edge technologies to deliver a seamless experience:

- ![NextJS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) **Next.js** for server-side rendering and fast performance
- ![Shadcn-ui](https://img.shields.io/badge/shadcn/ui-000000.svg?style=for-the-badge&logo=shadcn/ui&logoColor=white) **Shadcn/UI** for a customizable and responsive user interface
- ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6.svg?style=for-the-badge&logo=TypeScript&logoColor=white) **TypeScript** for type-safe development
- ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC.svg?style=for-the-badge&logo=Tailwind-CSS&logoColor=white) **Tailwind CSS** for a highly flexible and responsive design
- ![Pocketbase](https://img.shields.io/badge/Pocketbase-ff6347.svg?style=for-the-badge&logo=Pocketbase&logoColor=white) **Pocketbase** as the real-time backend for data management
- ![Blocknote](https://img.shields.io/badge/Blocknote-ff8c00.svg?style=for-the-badge&logo=Blocknote&logoColor=white) **Blocknote** for the rich text editor experience

## Installation & Setup

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```
   git clone https://github.com/eoksumm/notick
   ```

2. **Install dependencies**:
   ```
   npm install
   ```

3. **Configure environment variables**:
   Set up your `.env` file with the following keys:

   ```
   NEXT_PUBLIC_POCKETBASE_URL=
   NEXT_PUBLIC_TANSTACK_QUERY_KEY=
   NEXT_PUBLIC_API_KEY=
   ```

4. **Run Pocketbase**:
   ```
   ./pocketbase serve
   ```

5. **Start the development server**:
   ```
   npm run dev
   ```

## Acknowledgements

A special thanks to [CodewithAntonio](https://www.youtube.com/@codewithantonio) for the inspiration and tutorials that helped shape this project.

---
