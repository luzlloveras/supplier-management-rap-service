Supplier Management RAP service (backend)
This service focuses on supplier onboarding and lifecycle control.
Suppliers are the primary entity; material data is secondary context.
Status is enforced through explicit actions and guarded transitions.
New suppliers default to DRAFT to reflect review steps.
Business rules remain small and concrete for interview-ready clarity.
The service is intentionally scoped to highlight RAP behaviors.

Supplier lifecycle
Suppliers start in DRAFT and can be submitted for review without changing status.
Approval moves a supplier to ACTIVE, blocking moves to BLOCKED, and unblocking returns to ACTIVE.

## What this service demonstrates
- Supplier lifecycle (status)
- Custom actions (submit/approve/block/unblock)
- Minimal business validations
- Supplier-first domain focus

## How to run
```
npm install
npm start
```

## Related repository
UI extension: https://github.com/luzlloveras/material-supplier-ui-extension  
This repo provides the UI extension; this repo is the backend RAP service.
