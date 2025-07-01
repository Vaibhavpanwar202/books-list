 📚 My Favorite Books List

A simple Git-based project that maintains a list of favorite books in a text file. This project is designed for practicing Git version control operations including commits, branching, merging, and conflict resolution.

---

📝 Project Structure

books-list/
└── favorite_books.txt

yaml
🚀 Features

- Maintains a list of favorite books in `favorite_books.txt`
- Demonstrates Git operations:
  - Initializing a repository
  - Adding and committing files
  - Branching and merging
  - Resolving merge conflicts
  - Pushing to a remote GitHub repository

🧪 How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Vaibhavpanwar202/books-list.git
   cd books-list
Add or Modify Books in the File:


echo "4. Deep Work by Cal Newport" >> favorite_books.txt
Commit and Push Changes:


git add .
git commit -m "Added another favorite book"
git push origin main
View Commit History:

git log
⚔️ Conflict Resolution (Documentation)
During development, a merge conflict occurred when two branches (main and new-books) modified favorite_books.txt at the same line.

🛠️ Conflict Example:
Git showed conflict markers like:

<<<<<<< HEAD
2. The Alchemist by Paulo Coelho
=======
2. The Power of Habit by Charles Duhigg
>>>>>>> new-books
✅ Steps Taken to Resolve:
Manually edited the file to keep both entries:

2. The Alchemist by Paulo Coelho
3. The Power of Habit by Charles Duhigg
Staged and committed the resolved file:

git add favorite_books.txt
git commit -m "Resolved merge conflict in favorite_books.txt"
📌 Example Output (favorite_books.txt)


1. Atomic Habits by James Clear
2. The Alchemist by Paulo Coelho
3. The Power of Now by Eckhart Tolle
4. Deep Work by Cal Newport

✅ Deliverable
✔️ A Git repository: books-list

✔️ Clear commit history showing Git usage

✔️ Documentation of merge conflict resolution steps

✔️ Demonstration of Git push, pull, branch, and merge
https://github.com/Vaibhavpanwar202

