# Task Management Application

A feature-rich task management tool enabling users to create, update, and manage tasks visually. Designed for a streamlined experience with drag-and-drop functionality, dynamic alerts, and persistent data handling.

## 🌟 Features

- **Task CRUD Operations**:
  - **Create Tasks**: Add tasks with essential details:
    - Task Name
    - Priority: Low, Medium, High
    - Status: Todo, In Progress, Completed
    - Due Date
    - Assignee (dropdown selection)
  - **Edit Tasks**: Modify task details directly via a drawer modal.
  - **View Tasks**: Group tasks by their status, with dynamic counts displayed.
  - **Delete Tasks**: Remove tasks with a confirmation prompt.

- **Drag-and-Drop Functionality**:
  - Move tasks between status columns (`Todo`, `In Progress`, `Completed`) to update their status dynamically.

- **Dynamic Due Date Alerts**:
  - Alerts display the time remaining or overdue status, such as:
    - "Should complete within {X} days"
    - "Should've completed {X} days ago"

- **Persistent Storage**:
  - Task data is stored in the browser’s local storage to ensure it persists across sessions.

- **Real-Time Updates**:
  - Automatically save updates to task details without requiring a save button.

- **Responsive Design**:
  - A fully responsive layout that works across all devices.

- **Enhanced UI with Animations**:
  - Smooth transitions and interactions powered by Framer Motion.

---

## 🛠️ Tech Stack

### Frontend
- **React** with Next.js (or Vite for fast build times)
- **TypeScript** for robust type safety
- **Tailwind CSS** for modern and responsive styling
- **Formik** for form management
- **React DnD** for drag-and-drop implementation
- **Framer Motion** for animations

### State Management
- Zustand or Redux Toolkit for centralized, persistent state handling.

### Data Storage
- Browser's Local Storage to persist task data.

---

## 📦 Setup Guide

### Manual Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/task-management-app.git
    cd task-management-app
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up the environment variables**:
    Create a `.env` file in the project root:
    ```env
    REACT_APP_LOCAL_STORAGE_KEY=taskManagementApp
    ```

4. **Run the application**:
    ```bash
    npm run dev
    ```

5. **Access the application**:
    Open your browser and visit `http://localhost:3000`.

---

### Docker Setup (Optional)

1. **Navigate to the project directory**.

2. **Build and run the container**:
    ```bash
    docker-compose up --build
    ```

3. **Access the application**:
    The application will be available at `http://localhost:3000`.

---

## 🧪 Testing

- **Unit Tests**:
  Use Jest and React Testing Library to validate components and state logic.
- **Manual Testing**:
  Ensure that features like drag-and-drop, CRUD operations, and dynamic alerts function as expected.

---

## 📝 Deployment

- Deployed application to **[https://crework-assign.vercel.app/]** for a live demo.
- Ensure environment variables are properly configured during deployment.

---


## 💡 Future Enhancements

- Add user authentication for personalized task management.
- Implement server-side storage with a backend (e.g., Node.js + MongoDB).
- Integrate notifications for overdue tasks.

---

Thank you for reviewing the project! 🎉
Fathima Shahana Rifkhan 
