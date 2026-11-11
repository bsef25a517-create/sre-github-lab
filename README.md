# sre-github-lab
Requirements documentation for a Student Task Tracker.
## Overview
Pharmacies need an efficient way to manage medicine inventory, track medicine expiry dates, and maintain supplier information. Manual inventory management can lead to expired medicines, stock shortages, and difficulty managing suppliers.

PharmaTrack is a proposed system that will help pharmacy staff manage medicine records, monitor available stock, track expiry dates, and maintain supplier details. It will improve inventory accuracy, reduce medicine wastage, and help ensure medicine availability.

## Scope
- In scope: Track medicine batches and their expiry dates.
- In scope: Display available medicine stock.
- In scope: Prevent the sale of expired medicines.
- Out of scope: Online medicine ordering by customers.
- Out of scope: Home delivery services.

## Stakeholders
- Pharmacist: Checks medicine availability, expiry dates, and ensures expired medicines are not sold.
- Pharmacy Owner/Manager: Monitors overall inventory, supplier information, and pharmacy performance.
- Inventory Staff: Adds medicine records, updates stock quantities, and manages medicine batches.
- Supplier: Provides medicines to the pharmacy and shares medicine availability and supply information. 

## Functional requirements
- FR-01: The system shall allow authorized pharmacy staff to add and update medicine records. 
- FR-02: The system shall display available medicine quantities and inventory records.
- FR-03: The system shall generate alerts for medicines approaching their expiry dates.

## Nonfunctional requirements
- NFR-01 (Performance): With up to 10,000 medicine and batch records, the system shall display inventory search results within 3 seconds in at least 95 out of 100 trials on the agreed test device.
- NFR-02 (Security): The system shall require authorized user authentication before allowing access to inventory and supplier management functions.

## Acceptance criteria
- FR-01: Given the title "Read Chapter 1", saving a new task
  makes that title appear in the task list.
- FR-02: Given two saved tasks, opening the list shows both titles.
- FR-03: Marking an incomplete task complete changes its
  displayed status to Complete.

## Assumptions and open questions
- Assumption A-01:  Pharmacy staff will have basic computer knowledge and will be trained to use the system.
- Question Q-01: What expiry alert period should be used: 30 days, 60 days, or 90 days before expiry?
- Question Q-02:  Which devices will be used to access the system: desktop computers, laptops, or tablets?

## Project status and viewing
This is a documentation-only project. No application has been built.
Clone the repository and open README.md in Notepad, or read it on GitHub.

## Author
Name: Saira Arooj
Instructor: Mam Mudasira Arshad
Project Name: "PharmaTrack: Medicine Inventory and Supplier Management System"


## Contributing
Create a documentation branch, edit and review README.md,
commit and push the change, then open a pull request for review.

