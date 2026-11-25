# Linux CLI – Practical Task

### 1. Create the Directory Structure

Create a main directory named `Case_Files` containing three subdirectories:

- `Personal`
- `Media`
- `Storage`

### 2. Create Files

Inside the directories, create the following files:

**Personal**

- `profile.txt`
- `records.txt`
- `details.txt`

**Media**

- `capture.png`
- `audio.mp3`

**Case_Files**

- Create one hidden file named `.classified`.

**File Content Operations**

1. Write the following sentence inside `profile.txt`:

   ```text
   This is the original case profile.
   ```

2. Overwrite the existing content of `profile.txt` with:

   ```text
   The investigation has been updated.
   ```

3. Display the file content to verify the changes.

### 3. Find Files and Directories

- Locate `profile.txt`.
- Find all `.txt` files inside `Case_Files` (case-insensitive).
- Display directories only.
- Find all hidden files inside `Case_Files`.

### 4. Create File Links

- Create a **Symbolic Link** to `profile.txt` inside `Storage`, named `profile_shortcut`.
- Create a **Hard Link** to `profile.txt` inside `Media`, named `profile_copy`.

### 5. Investigate Inodes

Display and compare the Inode numbers of:

- The original `profile.txt`.
- The Hard Link `profile_copy`.
- The Symbolic Link `profile_shortcut`.

### 6. Create a File Inventory

Use `ls -a` with a redirection to save the contents of `Case_Files` into:

`Storage/file_index.txt`

### 7. Update the Inventory

- Append the following message to `file_index.txt` without deleting its existing content:

  ```text
  Investigation completed successfully
  ```

- Display the updated file using `cat`.

### 8. Test Your Links

- Delete the original `profile.txt` from `Personal`.
- Try accessing the Hard Link (`profile_copy`) and the Symbolic Link (`profile_shortcut`).
- Observe what happens to each link.
- Explain why the Hard Link still works while the Symbolic Link becomes broken.

---

## Submission

Submit the commands you used and include your observations and explanations for **Tasks 5 and 8**.

## Notes

1. In `solution.txt`, write the commands used to solve each step. **Do not include command outputs.**

2. Paste only the commands. Do not include the terminal prompt.

   **Incorrect:**

   ```bash
   [osc@osc ~]$ touch newFile
   ```

   **Correct:**

   ```bash
   touch newFile
   ```

3. Do not paste command outputs.

4. Write your observations and explanations for Tasks 5 and 8 in your own words.
