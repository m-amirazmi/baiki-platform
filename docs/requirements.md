# Baiki RMS | Platform Requirements

This is the requirements documentation on what features or modules should have on Baiki RMS platform app.
The platform app is for the Baiki RMS owner/admin mainly to oversee and manage the tenants that registered with Baiki RMS.

## Features

📊 Dashboard

- Overview (tenants, users, usage, alerts)

🏢 Tenant Management

- Tenant list
- Tenant details
- Approve/reject signups
- Suspend/terminate tenants
- Subscription/plan info

👥 User Management

- User Directory
- User Profile
- Roles & Permissions
- Analytics
- Audit & Security

💳 Billing & Subscription

- Plans & pricing
- Tenant subscriptions
- Payment history
- Invoices

🛡️ Audit & Security

- Admin activity logs
- System-wide login history
- Security alerts

⚙️ Platform Settings

- Integrations (WhatsApp, email, SSO, payments)
- Feature flags
- Platform config

### 👥 User Management

- User Directory

  - View all users (platform + tenants)
  - Search users by name, email, phone
  - Filter users by:
    - Platform / Tenant
    - Tenant Code
    - Role
    - Status (Active / Suspended)
  - Bulk actions (suspend / delete / invite)

- User Profile

  - Basic Info
    - Name
    - Email
    - Phone number
    - Status (Active / Suspended)
    - Created at / Updated at
  - Authentication
    - Last login timestamp
    - Last login device/browser info
  - Sessions (Enterprise)
    - Active sessions list
    - Force logout session(s)

- Roles & Permissions

  - Platform Roles
    - Default roles:
      - Super Admin → full access
      - Support → read/write access, no billing
      - Finance → billing + reporting only
      - Read-only → view data only
    - Custom role builder (Enterprise)
    - Permission matrix (Enterprise)
  - Tenant Roles (from platform view)
    - View tenant-defined roles (Admin, Manager, Technician, etc.)
    - Assign / revoke tenant roles (support override)
    - Reset tenant admin if locked out

- Analytics
- Audit & Security
