Linux Assignment: Archiving & Compression

Task 1 --- TAR Commands
1. Create a directory named Linux_Lab.
2. Inside it, create three directories: src, docs, and logs.
3. Create at least two text files inside each directory and add some
   content to them.
4. Create an archive named lab.tar containing the entire Linux_Lab
   directory.
5. Create a compressed archive named lab.tar.gz.
6. Create another compressed archive named lab.tar.bz2.
7. List the contents of each archive without extracting it.
8. Compare the sizes of the three archives.
Task 2 --- Selective Backup
1. Create backup.tar.gz from the Linux_Lab directory.
2. Create another archive named backup_no_logs.tar.gz, excluding all
   .log files.
3. Display the contents of both archives.
4. Compare their sizes.
5. Explain the purpose of the --exclude option.
Task 3 --- GZIP & BZIP2
1. Create a text file named data.txt containing at least 20 lines.
2. Compress it using gzip while keeping the original file.
3. Compress the same file using bzip2 while keeping the original
   file.
4. Display the sizes of the original and compressed files.
5. Decompress both compressed files.
6. Verify that the original content is preserved.
Task 4 --- ZIP Commands
1. Create a ZIP archive named lab.zip containing the src and docs
   directories only.
2. Display the archive contents without extracting them.
3. Extract the archive into a directory named extracted_zip.
4. Verify the extracted directory structure.
Task 5 --- Extracting and Restoring
1. Extract lab.tar.gz into a directory named restore_all.
2. Extract only one specific text file from lab.tar.gz into a
   directory named restore_file.
3. Display the contents of the extracted file.
4. List the contents of the archive without extracting it.
5. Display the content of a file inside the archive directly in the
   terminal without creating an extracted copy.
Task 6 --- Comparison Questions
Answer the following questions:
1. What is the difference between Archiving and Compression?
2. What is the difference between TAR and ZIP?
3. What is the difference between GZIP and BZIP2?
4. Which TAR option is used to create an archive?
5. Which TAR option is used to extract an archive?
6. Which TAR option is used to list archive contents?
7. What is the purpose of -z and -j?
8. What is the difference between -t and -x?
9. Why do we use -k with gzip or bzip2?
10. What is the purpose of the -C option in TAR?
Bonus Question ⭐
You have a compressed archive named large_backup.tar.gz containing
many files and directories.

Without extracting the archive:
1. Display all file names inside it.
2. Display the content of docs/README.txt directly in the terminal.
3. Save the content of docs/config.txt into a new file named
   config_copy.txt.
4. Explain the difference between using -t and -O in TAR.
Submission Requirements
- Submit all commands used.
- Attach screenshots showing the commands and their outputs.
- Include answers to all questions.
- Make sure the original files and restored files are verified.
