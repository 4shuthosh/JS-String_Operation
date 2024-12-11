# String Operations

This `string operation` performing random string operations on up to three user-input strings. The app generates random operations such as slicing, replacing, or concatenating the input strings and displays the results interactively.

- **HTML**: Contains the app layout and user input form.
- **CSS**: Styles the buttons, inputs, and results section for an engaging UI.
- **JavaScript**: Handles random operation selection and execution.
 
## Features

- Accepts up to three input strings.
- Performs a random operation from the following list:
  - **Length**: Calculates the length of each string.
  - **Slice**: Extracts a part of each string.
  - **Substring**: Extracts a substring from each string.
  - **Substr**: Extracts a substring with a given length from each string.
  - **Replace**: Replaces the first occurrence of "a" with "b" in each string.
  - **Replace All**: Replaces all occurrences of "a" with "b" in each string.
  - **To Upper Case**: Converts each string to uppercase.
  - **To Lower Case**: Converts each string to lowercase.
  - **Concatenate**: Combines all strings into one.
- Displays results with an enhanced UI and a dynamic background color for the results section.

## Example Inputs and Outputs

### Input
- **String 1**: `apple`
- **String 2**: `banana`
- **String 3**: `cherry`

### Random Operation Examples
1. **Operation**: Length
   - **Result**:
     ```
     Length of "apple": 5
     Length of "banana": 6
     Length of "cherry": 6
     ```

2. **Operation**: Slice (1, 3)
   - **Result**:
     ```
     Slice of "apple": pp
     Slice of "banana": an
     Slice of "cherry": he
     ```

3. **Operation**: Replace "a" with "b"
   - **Result**:
     ```
     Replace "a" with "b" in "apple": bpple
     Replace "a" with "b" in "banana": bbnbnb
     Replace "a" with "b" in "cherry": cherry
     ```

4. **Operation**: Concatenate
   - **Result**: `apple banana cherry`

### Dynamic Results Section
The background color of the results section changes randomly after every calculation, enhancing the visual experience.


## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License

This project is open-source and available under the [MIT License](LICENSE).

