
# Staff Management 

This C++ program is designed for basic staff management. It allows you to input information about persons, such as their ID, name, age, date of birth, position, and gender. You can also perform various operations on this data, like printing all records, categorizing persons by age, and counting the number of males and females.

## How to Use

1. **Input Records (Option 1)**: Enter information for persons. There is a limit of 50 persons (defined by PERSONS_LIMIT).

2. **Print All Records (Option 2)**: View all the entered records.

3. **Print by Age (Option 3)**: Categorize persons by age into three groups: those over 50, those between 40 and 50, and those under 40.

4. **Print by Sex Count (Option 4)**: Count the number of males and females in the records.

5. **Exit (Option 0)**: Terminate the program.

## Program Menu

- To navigate through the program, you'll use a menu that displays options as follows:

    ```
    ============ Program Menu ===========
    1 Input Records
    2 Print All Records
    3 Print by Age
    4 Print by Sex Count
    0 to exit
    ```

- Select an option by entering the corresponding number. 

## Program Limitations

- The program has a maximum limit of 50 persons, defined by PERSONS_LIMIT.

- When the limit is reached, you cannot add more persons.

## Building and Running the Program

1. Compile the program using a C++ compiler, e.g., g++:

    ```shell
    g++ staff_management.cpp -o staff_management
    ```

2. Run the program:

    ```shell
    ./staff_management
    ```

## Contributing

This program is open for contributions. If you have any suggestions or improvements, please feel free to make pull requests.

1. **Fork the Repository**: Click the "Fork" button at the top of the [GitHub repository page](https://github.com/swetamishra123/Staff-Management-cpp) to create your copy of the repository.

2. **Clone the Repository**: Clone your forked repository to your local machine:

   ```bash
   git clone https://github.com/your-username/Staff-Management-cpp.git
   ```

3. **Create a New Branch**: Create a new branch for your contributions:

   ```bash
   git checkout -b feature/your-feature-name
   ```

   Choose a descriptive name for your branch.

4. **Make Changes**: Make your desired changes or improvements to the codebase.

5. **Commit Your Changes**: Commit your changes with a clear and concise commit message:

   ```bash
   git commit -m "Add feature: your-feature-name"
   ```

6. **Push to Your Fork**: Push your changes to your forked repository:

   ```bash
   git push origin feature/your-feature-name
   ```

7. **Create a Pull Request**: On the GitHub repository page, click the "New Pull Request" button, and submit your pull request.

   - Describe your changes in the pull request.
   - Reference any issues or discussions related to the pull request.

8. **Review and Collaborate**: We will review your pull request, provide feedback, and collaborate with you on any necessary improvements.

9. **Merge**: Once the pull request is approved, it will be merged into the main project.

Thank you for contributing to this project!


### License

By contributing to this project, you agree to license your contributions under the [MIT License](LICENSE).
