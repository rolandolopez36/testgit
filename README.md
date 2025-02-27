# TestGit Repository

This repository contains files for testing Git functionalities.

## Files

- **example.txt**: A simple text file.
- **example2.txt**: This is a text file for a Test.
- **example3.txt**: This is a text file for a Test.
- **README.md**: This README file.
- **file1.txt**: A simple text file for testing.
- **file2.txt**: A simple text file for testing.
- **file3.txt**: A simple text file for testing.
- **file4.txt**: A simple text file for testing.
- **file5.txt**: A simple text file for testing.
- **folder1/file1.txt**: A text file inside folder1.
- **folder2/file2.txt**: A text file inside folder2.
- **folder3/file3.txt**: A text file inside folder3.
- **folder4/file4.txt**: A text file inside folder4.
- **folder5/file5.txt**: A text file inside folder5.
- **folder6/.gitkeep**: An empty folder with a .gitkeep file.

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

6. Create five additional folders, each with a text file inside:

   ```bash
   mkdir folder1, folder2, folder3, folder4, folder5
   echo "This is the content of file1.txt inside folder1" > folder1\file1.txt
   echo "This is the content of file2.txt inside folder2" > folder2\file2.txt
   echo "This is the content of file3.txt inside folder3" > folder3\file3.txt
   echo "This is the content of file4.txt inside folder4" > folder4\file4.txt
   echo "This is the content of file5.txt inside folder5" > folder5\file5.txt
   ```

7. Add and push each folder individually:

   ```bash
   git add folder1\file1.txt
   git commit -m "Add folder1 with file1.txt"
   git push origin main

   git add folder2\file2.txt
   git commit -m "Add folder2 with file2.txt"
   git push origin main

   git add folder3\file3.txt
   git commit -m "Add folder3 with file3.txt"
   git push origin main

   git add folder4\file4.txt
   git commit -m "Add folder4 with file4.txt"
   git push origin main

   git add folder5\file5.txt
   git commit -m "Add folder5 with file5.txt"
   git push origin main
   ```

8. Create a sixth empty folder and add a .gitkeep file:

   ```bash
   mkdir folder6
   New-Item -Path "folder6\.gitkeep" -ItemType "file"
   ```

9. Add and push the empty folder:

   ```bash
   git add folder6/.gitkeep
   git commit -m "Add empty folder6 with .gitkeep"
   git push origin main
   ```

   ```

   ```

10. Añade el archivo README.md actualizado a tu repositorio:
    ```bash
    git add README.md
    git commit -m "Update README.md with the folder process documentation"
    git push origin main
    ```
