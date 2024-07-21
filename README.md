# TestGit Repository

This repository contains files for testing Git functionalities.

## Files

- **example.txt**: A simple text file.
- **README.md**: This README file.
- **file1.txt**: A simple text file for testing.
- **file2.txt**: A simple text file for testing.
- **file3.txt**: A simple text file for testing.
- **file4.txt**: A simple text file for testing.
- **file5.txt**: A simple text file for testing.

## Purpose

The purpose of this repository is to practice Git commands and workflows.

## Process

1. Create the initial files:

   ```bash
   echo "This is a text file for testing Git functionalities." > example.txt
   echo "# TestGit Repository

   This repository contains files for testing Git functionalities.

   ## Files
   - **example.txt**: A simple text file.
   - **README.md**: This README file.

   ## Purpose
   The purpose of this repository is to practice Git commands and workflows." > README.md
   ```

2. Verify the files have been created:

   ```bash
   ls
   ```

3. Add and commit the initial files:

   ```bash
   git add example.txt README.md
   git commit -m "Add example.txt and README.md for testing"
   ```

4. Create five additional text files:

   ```bash
   echo "This is the content of file1.txt" > file1.txt
   echo "This is the content of file2.txt" > file2.txt
   echo "This is the content of file3.txt" > file3.txt
   echo "This is the content of file4.txt" > file4.txt
   echo "This is the content of file5.txt" > file5.txt
   ```

5. Add and push each file individually:

   ```bash
   git add file1.txt
   git commit -m "Add file1.txt"
   git push origin main

   git add file2.txt
   git commit -m "Add file2.txt"
   git push origin main

   git add file3.txt
   git commit -m "Add file3.txt"
   git push origin main

   git add file4.txt
   git commit -m "Add file4.txt"
   git push origin main

   git add file5.txt
   git commit -m "Add file5.txt"
   git push origin main
   ```
