# Employee Management System (EMS)
**Frontend End-Semester Lab Project**

A modern, clean, and responsive **Employee Management System** built using **HTML5**, **CSS3**, and **React.js**.

---

## 🚀 Key Features

1. **Dashboard Analytics & Metric Cards**:
   - Total Workforce count
   - Active employee tracker
   - Unique departments count
   - Average monthly salary estimation (formatted in INR `₹`)

2. **Complete CRUD Operations**:
   - **Create**: Add new employees with detailed fields (Name, Email, Phone, Role, Department, Salary, Status, Joining Date) with auto-generated ID (`EMP-XXX`).
   - **Read**: View employee details in a dedicated profile card modal.
   - **Update**: Edit existing employee information with pre-populated form values.
   - **Delete**: Remove employee record with confirmation protection.

3. **Multi-Criteria Search & Filtering**:
   - Live search by Name, Job Role, Email, or Employee ID.
   - Dropdown filter by Department (Engineering, Design, HR, Finance, Marketing, Sales).
   - Dropdown filter by Employment Status (Active, On Leave, Inactive).

4. **Dual Layout Display (Table & Grid Views)**:
   - **Table View**: Compact, data-dense overview with quick action buttons.
   - **Grid / Card View**: Card layout highlighting avatar initials, key contact info, and status badges.

5. **Data Persistence**:
   - Uses browser `localStorage` to retain all changes across page refreshes.
   - Pre-populated with realistic initial employee data.

6. **Export Feature**:
   - One-click CSV export (`.csv`) for downloading workforce records.

7. **Toast Notifications**:
   - Non-intrusive alerts for add, update, and delete actions.

---

## 🛠️ Technology Stack

- **HTML5**: Semantic document layout & structure.
- **CSS3**: Custom design system with CSS variables, Flexbox, CSS Grid, animations, and responsive layout.
- **React.js 18 (CDN)**: Functional components, Hooks (`useState`, `useEffect`, `useMemo`).
- **Babel Standalone**: In-browser JSX compilation (runs instantly without needing Node.js or `npm install`).
- **Font Awesome 6**: Clean vector icons for intuitive user experience.

---

## 🖥️ How to Run

1. Open this folder: `Frontend_end_sem_lab`
2. **Double-click `index.html`** in any web browser (Google Chrome, Microsoft Edge, Firefox, Brave).
   - Alternatively, right-click `index.html` and choose **"Open with Live Server"** if using VS Code.
3. No build tools or package managers (`npm`/`yarn`) required!

