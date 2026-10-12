# Sentinel Hostel Management System — Frontend

A modern, responsive, and enterprise-grade hostel management web application built with **React 19** and **Vite**.

## Features

- **Role-Based Portals**: Personalized dashboards for Students, Wardens, and Administrators.
- **Room Booking & Allocations**: Interactive wing-wise room roster with vacancy indicators and allocation dialogs.
- **Hostel Fee & Payment Gateway**:
  - **UPI & QR Mode**: Interactive SVG QR code with dynamic scanning beam, 5-minute countdown timer, one-click VPA copy, quick-switch presets (Google Pay, PhonePe, Paytm, BHIM, CRED), and simulated phone approval.
  - **Net Banking Mode**: Top 6 scheduled Indian banks (SBI, HDFC, ICICI, Axis, Kotak, PNB) + 20+ additional scheduled banks with simulated secure 2FA SMS OTP netbanking portal.
  - **Official Treasury E-Receipts**: Instant tax invoice generation with digital clearance seals and `@media print` optimized receipt printing.
- **Complaint & Maintenance Registry**: Student ticket submission with Warden real-time progress & resolution status tracking.
- **Outstation & Night Leave Management**: Apply for leaves with reason/destination and Warden approval decisions.
- **Hostel Circulars & Bulletins**: Real-time broadcasts for hostel residents.
- **Admin Live Radar Student Tracker**: Map-based radar visualization to monitor student status & location.

## Technologies Used

- **Framework**: React 19 + Vite
- **Routing**: React Router DOM (v6)
- **HTTP Client**: Axios with JWT Bearer Token interceptors
- **Styling**: Modern CSS3 with CSS variables, Glassmorphism, and responsive grid layouts

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation
```bash
# Clone the repository
git clone https://github.com/rohith57509/HostelManagementSystem-Frontend.git
cd HostelManagementSystem-Frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

The frontend will run at: `http://localhost:5173`

### Environment Configuration (Optional)
To point to a custom backend URL, create a `.env` file in the root folder:
```env
VITE_API_URL=http://localhost:8080/api
```

## Build for Production
```bash
npm run build
```
