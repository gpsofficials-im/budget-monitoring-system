# AI-Based Budget Utilization Monitoring System

A comprehensive MEAN stack web application designed for government departments and large enterprises to monitor budget allocation, expenditure, utilization, financial irregularities, and fund leakage risks.

## 🎯 Core Objective

Monitor and analyze:
- Annual and quarterly budgets
- Budget allocation to departments/projects
- Real-time expenditure tracking
- Budget utilization percentages
- Under-utilization detection
- Overspending alerts
- Abnormal spending spikes
- Financial irregularities
- Department-wise analytics
- Audit trails

## 🏗️ Technology Stack

### Frontend
- **Framework**: Angular 16+
- **Language**: TypeScript
- **Styling**: CSS3, Bootstrap 5
- **Charts**: Chart.js with ng2-charts
- **Forms**: Reactive Forms
- **HTTP Client**: Angular HttpClient

### Backend
- **Runtime**: Node.js 18+
- **Framework**: Express.js
- **Authentication**: JWT + bcryptjs
- **Database**: MongoDB with Mongoose
- **Validation**: Joi

### Database
- **Primary**: MongoDB (Cloud: MongoDB Atlas)
- **ODM**: Mongoose 7+

### Deployment
- Render, AWS, Azure, or DigitalOcean

## 📋 User Roles

### 1. ADMIN
- Manage users and departments
- Create/update budgets
- Configure anomaly thresholds
- View all financial data
- Access audit logs
- Generate reports

### 2. FINANCE OFFICER
- View assigned department budgets
- Record expenditures
- Upload supporting documents
- View utilization metrics
- Generate department reports

### 3. DEPARTMENT HEAD
- View department dashboard
- View allocated budget
- Monitor expenditures
- Track utilization
- View financial reports

## 📑 Functional Pages

1. **Login** - JWT authentication with role-based redirection
2. **Dashboard** - Real-time financial overview with charts
3. **Budget Management** - Create, view, edit budgets
4. **Expenditure Management** - Record and track expenditures
5. **Budget Monitoring & Analytics** - Utilization tracking
6. **Anomaly Detection & Alerts** - Financial irregularity detection
7. **Reports** - PDF/CSV export with filters
8. **Admin Panel** - User, department, and configuration management

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- MongoDB 5.0+
- Angular CLI 16+
- npm or yarn

### Backend Setup

```bash
cd backend
npm install
cp .env.example .env
# Edit .env with your configuration
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
ng serve
```

### Access Application
- Frontend: `http://localhost:4200`
- Backend API: `http://localhost:5000/api`

## 📦 Project Structure

```
budget-monitoring-system/
├── frontend/                    # Angular application
│   ├── src/
│   │   ├── app/
│   │   │   ├── auth/           # Authentication module
│   │   │   ├── dashboard/      # Dashboard pages
│   │   │   ├── budget/         # Budget management
│   │   │   ├── expenditure/    # Expenditure tracking
│   │   │   ├── monitoring/     # Analytics & monitoring
│   │   │   ├── alerts/         # Alert management
│   │   │   ├── reports/        # Report generation
│   │   │   ├── admin/          # Admin panel
│   │   │   ├── shared/         # Shared services/components
│   │   │   └── interceptors/   # HTTP interceptors
│   │   ├── assets/
│   │   └── environments/
│   └── angular.json
│
├── backend/                     # Node.js/Express application
│   ├── controllers/            # Business logic
│   ├── models/                 # Mongoose schemas
│   ├── routes/                 # API endpoints
│   ├── middleware/             # Custom middleware
│   ├── services/               # Business services
│   ├── utils/                  # Utility functions
│   ├── validators/             # Input validation
│   ├── config/                 # Configuration files
│   ├── seeds/                  # Sample data
│   ├── server.js               # Entry point
│   ├── .env.example
│   └── package.json
│
├── docs/                       # Documentation
├── .gitignore
└── README.md
```

## 🔐 Security Features

- JWT token-based authentication
- bcryptjs password hashing
- Role-based access control (RBAC)
- Department-level authorization
- Input validation and sanitization
- MongoDB injection protection
- CORS configuration
- Environment variable management
- Audit logging for all operations

## 📊 Key Features

### Budget Management
- Create annual and quarterly budgets
- Track approved vs allocated amounts
- Real-time budget status monitoring
- Budget history and timeline

### Expenditure Tracking
- Record expenses with vendor details
- Upload supporting documents
- Automatic budget validation
- Transaction audit trail

### Monitoring & Analytics
- Real-time utilization calculation
- Time-elapsed vs utilization comparison
- Department-wise breakdown
- Trend analysis

### Anomaly Detection
- Under-utilization alerts
- Overspending detection
- Spending spike identification
- Threshold deviation warnings
- Configurable alert severity

### Reporting
- Budget allocation reports
- Expenditure analysis
- Utilization reports
- Department-wise summaries
- Anomaly reports
- PDF/CSV export
- Print functionality

### Audit Logging
- User action tracking
- Change history
- IP logging
- Timestamp recording
- Role-based access audit

## 🧪 Testing

Authentication, authorization, budget operations, expenditure tracking, anomaly detection, and report generation are fully testable.

## 📈 Performance Optimization

- MongoDB indexes for fast queries
- API pagination for large datasets
- Lazy-loaded Angular modules
- Efficient aggregation pipelines
- Chart caching
- Request debouncing

## 🌍 Responsive Design

Optimized for:
- Desktop (1920px+)
- Laptop (1366px)
- Tablet (768px)
- Mobile (320px)

## 📚 API Documentation

Complete REST API with endpoints for:
- Authentication (`/api/auth`)
- Users (`/api/users`)
- Departments (`/api/departments`)
- Budgets (`/api/budgets`)
- Expenditures (`/api/expenditures`)
- Monitoring (`/api/monitoring`)
- Alerts (`/api/alerts`)
- Reports (`/api/reports`)
- Audit logs (`/api/audit-logs`)
- Configuration (`/api/config`)

## 🚀 Deployment

Production-ready configuration for:
- Render
- AWS (EC2, RDS, S3)
- Azure (App Service, Cosmos DB)
- DigitalOcean

## 📝 License

Academic Project

## 👥 Author

GPS Officials - Budget Monitoring System Team

---

**Status**: Under Development (Phase 1-15)

**Last Updated**: 2026-09-05
