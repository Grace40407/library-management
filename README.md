Project Description: Library Management System Database

This database system is designed to manage core operations of a library, enabling efficient tracking of books, authors, publishers, members, and loans. It serves as a foundational backend for a library management application, ensuring data integrity and minimizing redundancy through normalized relational design.

Key Features
Book Management

Stores book details (ISBN, title, publication year) and links them to their publishers.

Supports multiple authors per book via a many-to-many relationship.

Publisher Tracking

Maintains publisher information (name, address) to avoid data duplication across books.

Member Management

Registers library members with unique email addresses and tracks their registration dates.

Loan Tracking

Records book loans, including loan dates, due dates, and return dates.

Enforces rules (e.g., due_date must be after loan_date) to ensure valid loan periods.

Data Integrity

Constraints: Primary keys, foreign keys, NOT NULL, UNIQUE (e.g., ISBN, member emails), and CHECK constraints.

Auto-generated IDs: Streamline record creation (e.g., book_id, member_id).

Use Cases
Track which books are currently borrowed and by whom.

Manage author and publisher relationships for cataloging.

Monitor member activity and registration history.

Ensure accurate inventory and loan period compliance.
