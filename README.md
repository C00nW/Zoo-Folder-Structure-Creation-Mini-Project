# Zoo Folder Structure Creation Project

## Introduction

In this project, I created a well-organized folder structure representing a zoo using basic Linux commands on Ubuntu Desktop. The goal was to demonstrate my skills in using the command-line interface to create a hierarchical directory structure and showcase my ability to work with Linux-based systems.

## Project Overview

The zoo folder structure consists of different animal categories, such as mammals, reptiles, and fish, each containing subfolders for herbivores and carnivores. I used a combination of Linux commands to create folders, subfolders, and files within the structure.

## Tools and Technologies Used

- Ubuntu Desktop
- Linux command-line interface (terminal)
- Basic Linux commands: `mkdir`, `cd`, `touch`, `echo`, `ls`

## Project Steps

1. Open the Ubuntu terminal:
   - Press `Ctrl + Alt + T` to open the terminal directly, or
   - Click on the Ubuntu Dash (usually located at the top-left corner of the screen) and search for "Terminal" in the search bar. Click on the Terminal icon to open it.

2. Navigate to the desired directory for creating the zoo folder structure:
   - Use the `cd` command followed by the directory path to navigate to the desired location.
   - For example, if you want to create the structure in your home directory, you can simply type `cd ~` to navigate there.

3. Create the main animal category folders:
   - Type `mkdir mammals` and press Enter to create the "mammals" folder.
   - Type `mkdir reptiles` and press Enter to create the "reptiles" folder.
   - Type `mkdir fish` and press Enter to create the "fish" folder.

4. Navigate into each animal category folder and create the "herbivores" and "carnivores" subfolders:
   - Type `cd mammals` to navigate into the "mammals" folder.
   - Type `mkdir herbivores` to create the "herbivores" subfolder.
   - Type `mkdir carnivores` to create the "carnivores" subfolder.
   - Repeat the process for the "reptiles" and "fish" folders by navigating into each folder using `cd reptiles` and `cd fish` respectively, and then creating the "herbivores" and "carnivores" subfolders using `mkdir`.

5. Create files representing different animals within each subfolder:
   - Navigate into the desired subfolder using the `cd` command.
   - Use the `touch` command followed by the file name to create empty files.
   - For example, to create files in the "mammals/herbivores" folder, type:
     - `cd mammals/herbivores`
     - `touch zebra.txt`
     - `touch zoro.txt`
     - `touch zebroni.txt`
   - Repeat the process for the other subfolders, creating files named `animal1`, `animal2`, and `animal3` in each subfolder.

6. Add content to specific files:
   - For the files in the "mammals/herbivores" folder, use the `echo` command to add content to the files.
   - Type `echo "lanny_the_zebra" > zebra.txt` to add the text "lanny_the_zebra" to the "zebra.txt" file.
   - Type `echo "zoro" > zoro.txt` to add the text "zoro" to the "zoro.txt" file.
   - Type `echo "zebroni" > zebroni.txt` to add the text "zebroni" to the "zebroni.txt" file.

7. Navigate between folders:
   - Use the `cd` command followed by the folder name to navigate into a subfolder.
   - Use `cd ..` to move back to the parent directory.
   - Use `cd ../..` to move back two levels in the directory structure.

8. Verify the folder structure:
   - Use the `ls -R` command to recursively list all files and folders within the current directory and its subdirectories.
   - This command will display the entire directory tree, showing the hierarchy of folders and files created.

9. Exit the terminal:
   - Once you have completed creating the folder structure and verifying it, you can close the terminal by typing `exit` or clicking on the close button.

## Project Outcome

Upon completing the project, I successfully created the following zoo folder structure:

```bash
.
├── fish
│   ├── carnivores
│   │   ├── animal1
│   │   ├── animal2
│   │   └── animal3
│   └── herbivores
│       ├── animal1
│       ├── animal2
│       └── animal3
├── mammals
│   ├── carnivores
│   │   ├── animal1
│   │   ├── animal2
│   │   └── animal3
│   └── herbivores
│       ├── zebra.txt
│       ├── zebroni.txt
│       └── zoro.txt
└── reptiles
├── carnivores
│   ├── animal1
│   ├── animal2
│   └── animal3
└── herbivores
├── animal1
├── animal2
└── animal3
```

## Skills Demonstrated

Through this project, I showcased the following skills:

- Proficiency in using Linux commands on Ubuntu Desktop.
- Ability to navigate through directories using the `cd` command.
- Creating folders and subfolders using the `mkdir` command.
- Creating files using the `touch` command.
- Adding content to files using the `echo` command.
- Verifying the folder structure using the `ls -R` command.
- Organizing data in a logical and hierarchical manner.
- Attention to detail in following specific naming conventions and structure requirements.

## Conclusion

This project demonstrates my proficiency in working with Linux-based systems, utilizing the command-line interface effectively, and creating well-organized directory structures. It showcases my ability to navigate through directories, create folders and files, and structure data in a logical manner.

By completing this project, I have strengthened my skills in using Linux commands and have gained practical experience in creating and managing folder structures. This project serves as a testament to my ability to work with file systems and my attention to detail in organizing data.

Feel free to explore the created folder structure and provide any feedback or suggestions for improvement. Thank you for considering my project!
