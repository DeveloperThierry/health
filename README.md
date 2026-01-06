
![View 1](/public/view/view1.png)
![View 2](/public/view/view2.png)
![View 3](/public/view/view3.png)
![View 4](/public/view/view4.png)
![View 5](/public/view/view5.png)
![View 6](/public/view/view6.png)
![View 7](/public/view/view7.png)
![View 8](/public/view/view8.png)
# 🏥 Patient Management System

A healthcare administration platform designed to streamline patient registration, appointment scheduling, and medical records management through a centralized digital dashboard.

---

## ✨ Features

* 📝 **Patient Onboarding:** Secure and intuitive registration flow for new patients with file upload capabilities.
* 📅 **Appointment Management:** Real-time scheduling, canceling, and rescheduling of medical appointments via the web interface.
* 🧑‍⚕️ **Admin Dashboard:** Comprehensive overview for healthcare providers to manage patient lists and pending requests.
* 🔒 **Data Security:** Robust handling of patient information and medical records using Appwrite's backend services.
* 📱 **Responsive Design:** Fully optimized interface for mobile, tablet, and desktop views using TailwindCSS and ShadCN.

---

## 💻 Tech Stack

* **Framework:** Next.js (App Router)
* **Backend as a Service:** Appwrite
* **Language:** TypeScript
* **Styling:** TailwindCSS & ShadCN

---

## 🚀 Installation

Follow these steps to set up the project locally.

### 🛠️ Setup Steps

1. **Clone the repository:**
```bash
git clone https://github.com/DeveloperThierry/health.git
```

2. **Install dependencies:**
```bash
npm install
```

3. **Environment Configuration:**
Create a `.env.local` file in the root directory and add your Appwrite credentials:
```env
#APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
DOCTOR_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=
NEXT_PUBLIC_ADMIN_PASSKEY=111111
```

4. **Run the development server:**
```bash
npm run dev
```

---

### 📅 Booking an Appointment

Patients can select their preferred doctor and date through the booking portal. Upon submission, the status is set to "Pending" and appears on the admin dashboard.

### 🧑‍⚕️ Admin Access

Access the dashboard at `/admin` to view all scheduled appointments, update appointment statuses, and manage the patient database in real-time.

---

## 🤝 Contributing

We welcome contributions to improve CarePulse! Please review our [CONTRIBUTING.md](https://github.com/DeveloperThierry/health/blob/main/CONTRIBUTING.md) for guidelines on how to submit pull requests and report issues.

---

## 📄 License

This project is licensed under the **MIT License**. For more details, please see the [LICENSE](https://github.com/DeveloperThierry/health/blob/main/LICENSE) file.

---

## 🙏 Contributions

Special thanks to JSMastery for project guidance and assets
