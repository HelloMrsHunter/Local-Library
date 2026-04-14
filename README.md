# local-library-project
This project focuses on building helper functions that analyze and transform library data.
Implementation plan
-Start with simple lookup functions (findAccountById, findAuthorById) to establish data familiarity.
-Build sorting and counting functions using .sort() and .reduce().
-Implement mid‑level logic such as getTotalNumberOfBorrows and getBooksBorrowedCount.
-Complete advanced functions like getMostCommonGenres, getMostPopularBooks, and getMostPopularAuthors.
-Test each function in isolation using sample data.
-Debug edge cases (empty arrays, missing IDs, repeated borrowers).
-Finalize code formatting and ensure all functions return the exact structure required by the tests.

Structure Example
A clean navigation structure for the Local Library dashboard might include:
-Home – Overview of library activity
-Books – List of all books, availability status, and borrow history
-Accounts – Patron directory with search and filter options
-Authors – Author profiles and associated books
-Statistics – Most popular books, genres, and authors
-This structure supports intuitive movement through the system and aligns with typical admin dashboards.

Coding Trade‑Offs:
-I chose built‑in array methods over manual loops for readability, even though loops can be slightly faster.
-Some functions could be combined, but I kept them separate to maintain clarity and match the project rubric.
-I used intermediate variables in complex .reduce() operations to improve clarity rather than compressing everything into one line.
-I prioritized clean, understandable logic over micro‑optimizations

Justification, Challenges, and Debugging Moments:
-I justified using .find() for ID lookups because it returns the first match and stops early, improving efficiency.
-I encountered challenges with nested data structures, especially when accessing book.borrows[0]. Debugging required logging intermediate values.
-Sorting functions initially returned incorrect results due to mutating the original array; I resolved this by spreading into a new array.
-I used console testing and Replit to verify each function before moving on to the next

AI Tools Used (With Justification)
-AI Assistant (Copilot) — Used to clarify JavaScript concepts, confirm correct array method usage, and help rewrite explanations more professionally.
-AI was NOT used to write full solutions, only to support debugging, improve readability, and validate logic.
-All final code was written, tested, and verified manually.

Project Summary
This project strengthened my ability to work with data structures and apply JavaScript array methods effectively. I built a series of helper functions that search, sort, filter, and aggregate library data. Throughout the process, I learned how to break down large problems into smaller, testable steps and how to structure functions for clarity and reusability. Debugging taught me the importance of checking intermediate values and understanding how nested objects behave. I also practiced writing clean, readable code that meets strict output requirements. Overall, this project improved my confidence in JavaScript logic, problem‑solving, and functional programming techniques.
