# Workflow & Milestones
Vehicle Service Management System (C Project)

---

## Project Overview
This is a menu-driven console project in C using:
- Structures (`struct`)
- Functions
- File handling for permanent storage (`.dat`)
- Role based authentication (Admin/User)

CRUD Pattern:
1. Add
2. View
3. Search
4. Update
5. Delete
6. Exit

---

## Final System Flow
Start
 → Login/Register
 → Role Based Menu (Admin/User)
 → Select module
 → Perform operations (CRUD)
 → Logout / Exit

---

## Data Storage (File Handling)
Records will be stored in `.dat` files inside `data/` folder:
- `users.dat`
- `customers.dat`
- `vehicles.dat`
- `services.dat`
- `bills.dat`

---

## Folder Structure
Root:
- README.md
- .gitignore

Folders:
- `src/`      -> all `.c` files
- `include/`  -> all `.h` files
- `data/`     -> `.dat` files (created during runtime)
- `docs/`     -> workflow, roles, docs, screenshots

---

## Timeline / Milestones

### Phase 1 — Setup & Planning (Day 1)
- Create GitHub repository
- Create folder structure
- Add documentation (README + roles + workflow)

Deliverable:
✅ repo ready with clear task distribution

---

### Phase 2 — Authentication (Day 2)
- Implement register/login system
- Implement role based routing (Admin/User)

Deliverable:
✅ login works and menu opens correctly by role

---

### Phase 3 — Core Development (Day 3–5)
- Customer module (CRUD)
- Vehicle module (CRUD)
- Service module (CRUD + status)
- Billing module (invoice + payment status)

Deliverable:
✅ all modules working with file handling

---

### Phase 4 — Integration & Testing (Day 6)
- Integrate all modules in `main.c`
- Fix bugs in file update/delete/search
- Verify output formatting

Deliverable:
✅ stable working program

---

### Phase 5 — Demo + Submission Preparation (Day 7)
- Screenshot outputs
- Report writing (if required)
- Viva preparation

Deliverable:
✅ submission ready project
