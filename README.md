
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

This program is open for contributions. If you have any suggestions or improvements, please feel free to make pull requests or open issues on the [GitHub repository](https://github.com/swetamishra123/Staff-Management-cpp).

## License

This program is released under the [MIT License](LICENSE).
