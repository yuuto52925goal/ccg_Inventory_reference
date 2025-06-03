# 📊 Inventory & Invoice Management System


### ✨ Project Purpose & Goals

This system is designed to help small-to-medium medical businesses track medical inventory, manage invoices, and monitor item stock levels efficiently:
- 💼 Customer and vendor profiles
- 🧾 Invoices and purchase orders
- 📦 Inventory tracking
- 📁 File exports (PDF, Excel)
- 🔐 Role-based access for employees and admins

It will streamline daily operations, centralize data, and make financial reporting easier and more accurate.

---

## 🚀 Tech Stack

- **Frontend**: [Next.js](https://nextjs.org/) (deployed on [Vercel](https://vercel.com))
- **Backend**: [Supabase](https://supabase.com/)
  - PostgreSQL (Database)
  - Auth (JWT-based, with Row-Level Security)
  - Storage (for PDFs, Excel exports)
  - Edge Functions (for business logic)
- **CI/CD**: [GitHub Actions](https://github.com/features/actions)
- **Infrastructure as Code (optional)**: [Terraform](https://www.terraform.io/)


### 📅 Daily Goals (Project Timeline)

| Date       | Goal                                                                 |
|------------|----------------------------------------------------------------------|
| Day 1      | ✅ Set up Supabase project, schema, auth, and storage                |
| Day 2      | ✅ Build basic UI (Next.js/Vercel), connect to Supabase DB & Auth    |
| Day 3      | ✅ Implement invoice & purchase order creation forms                 |
| Day 4      | ✅ Add role-based access (admin vs employee) via RLS                 |
| Day 5      | ✅ Enable file exports (PDF/Excel), store to Supabase Storage        |
| Day 6      | ✅ Deploy everything via GitHub Actions CI/CD                        |
| Final Day  | 🎉 Final polish, bug fixes, write-up, and presentation prep          |

---