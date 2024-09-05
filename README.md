# Password Generator App

This is a simple **Password Generator** built using **React**. It allows users to generate secure passwords with customizable length and options to include numbers and special characters. The generated password can be easily copied to the clipboard.

## Features
- Adjustable password length (between 8 and 100 characters).
- Option to include numbers.
- Option to include special characters.
- Generated password is displayed in a text field and can be copied with a single click.
- Responsive and clean UI.

## Demo
![Password Generator Screenshot](C:\Users\LENOVO\Desktop\CODE\React dev\Password-Generator-React\src\assets\example.png)

## Getting Started

Follow these steps to set up the project on your local machine.

### Prerequisites

- **Node.js** and **npm** installed on your machine.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Rahulray12/password-generator.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd password-generator
   ```

3. **Install the required dependencies:**

   ```bash
   npm install
   ```

4. **Start the development server:**

   ```bash
   npm run dev
   ```

   This will launch the app at `http://localhost:3000`.

## Usage

1. **Adjust Password Length:**
   - Use the range slider to adjust the desired password length (from 8 to 100 characters).

2. **Toggle Number and Character Inclusion:**
   - Check or uncheck the options to include numbers and special characters in your password.

3. **Copy Password to Clipboard:**
   - Once the password is generated, click the **Copy** button to copy the password to the clipboard for easy use.

## Code Overview

### Key Components

- **State Management:** `useState` is used to manage password length, number inclusion, character inclusion, and the generated password.
  
- **Password Generation Logic:** The `passwordGenerator` function dynamically constructs the password string based on the selected options.

- **Clipboard Copy:** The `copyPasswordtoClipBoard` function allows users to quickly copy the generated password to their clipboard.

### Hooks Used

- **useState:** Manages component state (e.g., password length, number and character toggles).
- **useCallback:** Optimizes performance by memoizing functions.
- **useEffect:** Automatically regenerates the password when the options or length change.
- **useRef:** Used to reference the password input field for clipboard copying.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm run build`

Builds the app for production, minifying and optimizing for better performance.

## Technologies Used

- **React** - Frontend framework.
- **TailwindCSS** - For styling the components and layout.
- **JavaScript** - Core language for logic and component management.

## Customization

Feel free to modify the project to suit your needs:
- You can change the default password length, or the characters used in the generation.
- Adjust the styles by editing the `className` attributes or modifying the TailwindCSS configuration.

## Contributions

If you wish to contribute, feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.

---

Enjoy secure password generation with customizable options!
