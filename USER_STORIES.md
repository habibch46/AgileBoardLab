# User Stories: Library Book Search

Copy each story into its GitHub issue. Keep all checkboxes empty until the work is done and tested.

---

## US-01: Search books by title

**User story:** As a student, I want to search for books by title so that I can quickly find the book I need.

**Acceptance criteria**
- [ ] The system shows all books whose title contains the search text, ignoring capital letters.
- [ ] Each result shows the title, author, subject and availability.
- [ ] A blank search is rejected with the message "Please enter a title".
- [ ] If no book matches, the message "No books found" is shown.

**Technical tasks** (Owner: Mian Habib Ullah)
- [ ] Design the search screen
- [ ] Implement the `searchByTitle` method
- [ ] Validate blank input
- [ ] Test blank, matching and no-match searches

**Definition of Done**
- [ ] All criteria are met and tested
- [ ] Work is reviewed and committed

---

## US-02: Search books by author

**User story:** As a student, I want to search for books by author so that I can find all books written by one person.

**Acceptance criteria**
- [ ] The system shows all books written by the author entered.
- [ ] A part of the author's name is enough to find a match.
- [ ] If no author matches, the message "No books found" is shown.

**Definition of Done**
- [ ] All criteria are met and tested
- [ ] Work is reviewed and committed

---

## US-03: Search books by subject

**User story:** As a student, I want to choose a subject so that I can see all books on that topic.

**Acceptance criteria**
- [ ] The student can select a subject from a list.
- [ ] The system shows all books in the selected subject.
- [ ] If a subject has no books, the message "No books in this subject" is shown.

**Definition of Done**
- [ ] All criteria are met and tested
- [ ] Work is reviewed and committed

---

## US-04: View book details

**User story:** As a student, I want to see the details of a book so that I know where to find it in the library.

**Acceptance criteria**
- [ ] The details screen shows the title, author, subject and shelf number.
- [ ] The screen shows how many copies are available.
- [ ] An invalid book ID shows the message "Book not found".
- [ ] A book with zero copies is shown as "Not available".

**Definition of Done**
- [ ] All criteria are met and tested
- [ ] Work is reviewed and committed

---

## US-05: Add a new book

**User story:** As a librarian, I want to add a new book so that students can find it in the search.

**Acceptance criteria**
- [ ] A book must have a title, author and subject.
- [ ] A blank title is rejected with a clear message.
- [ ] A saved book appears in the search results.

**Technical tasks** (Owner: Mian Habib Ullah)
- [ ] Design the `Book` class
- [ ] Implement the `addBook` method
- [ ] Test a blank title
- [ ] Update the README

**Definition of Done**
- [ ] All criteria are met and tested
- [ ] Work is reviewed and committed
