# Team Roles & Responsibilities (with Deliverables)

Deliverables = Proof of work/output that must be submitted to GitHub.

---

## Team Lead — Souvik Ghosh (Architecture + Core Developer + Integrator)
Responsibilities:
- Complete system design (modules, structs, file storage format)
- Main menu + role-based routing (Admin/User)
- File handling structure & common helper functions
- Integration of all modules into final working build
- GitHub management (repo, branches, merges)
- Final testing + bug fixing + demo preparation

Deliverables:
- `src/main.c` (final integrated program)
- Final folder structure maintained
- Final working project (all modules connected)
- Working demo ready code

---

## Snehasish — Service Record Module (Owner)
Responsibilities:
- Service Record CRUD:
  - Add service record
  - View service records
  - Search service (by vehicle no.)
  - Update service status (Pending/Completed)
  - Delete service record (if required)

Deliverables:
- `src/service.c`
- `include/service.h`
- Minimum 5 test cases for service module

---

## Sansuddhi — Customer + Vehicle Module + Console UI (Owner)
Responsibilities:
1) Customer Management:
- Add customer
- View all customers
- Search customer (phone/name)
- Update customer
- Delete customer (optional)

2) Vehicle Management:
- Add vehicle (linked with customer ID)
- View all vehicles
- Search vehicle (vehicle number)
- Update vehicle
- Delete vehicle (optional)

3) Console UI Task (IMPORTANT):
- Design console menus and formatting
- Display lists in table format (neat printing)
- Improve readability of the program output

Deliverables:
- `src/customer.c` + `include/customer.h`
- `src/vehicle.c` + `include/vehicle.h`
- `docs/ui_output_samples.md` (screenshots or sample output text)

---

## Sneha — Billing + Documentation + Viva Support (Owner)
Responsibilities:
- Billing module:
  - Generate bill/invoice for service record
  - Payment status update (Paid/Unpaid)
  - Invoice printing format (console output)
- Documentation:
  - Report writing (based on final code)
  - Add screenshots and module descriptions
- Viva support:
  - Viva questions list (short answers)

Deliverables:
- `src/billing.c`
- `include/billing.h`
- `docs/testcases.md`
- `docs/viva_qna.md`
- Final report file in `docs/` (if required by teacher)
