# Periodic Table Element Information - Bash Script

![Periodic Table Element Information](screenshot.png)

## Introduction

The Periodic Table Element Information Bash Script is a command-line tool that provides information about chemical elements from the periodic table. By providing an element's name, symbol, or atomic number as an argument, the script retrieves essential properties and displays them in a user-friendly manner.

## Features

- Retrieve element information based on element name, symbol, or atomic number.
- Display element type, atomic mass, melting point, and boiling point.

## Prerequisites

Before using the Periodic Table Element Information Bash Script, ensure you have the following:

- A PostgreSQL database with the necessary tables: `elements`, `properties`, and `types`.
- Required database credentials and connection details properly configured in the script (`PSQL` variable).
- Bash shell environment to execute the script.

## Usage

1. **Clone the Repository**: Start by cloning this repository to your local machine.

   ```bash
   git clone https://github.com/your-username/periodic-table-element-info.git
    ```

2. **Database Setup**: Ensure your PostgreSQL database is set up with the required tables (elements, properties, and types). The script interacts with these tables to retrieve element information.

3. **Configuration**:  Open the script (periodic_element_info.sh) in a text editor and verify the PSQL variable configuration to match your database connection details.

4. **Run the Script**: In the terminal, navigate to the project directory and execute the script.

    ```bash
        cd periodic-table-element-info
        ./periodic_element_info.sh [element_name/symbol/atomic_number]
    ```
5. **Provide Argument**: Replace [element_name/symbol/atomic_number] with the desired element name, symbol, or atomic number.

## Important Notes
- This script assumes specific table structures in the PostgreSQL database (elements, properties, and types). Ensure your database matches the expected schema.
- The script doesn't handle all possible edge cases. You can enhance the script's error handling and validation based on your requirements.
- Customize the script as needed to suit your usage and data.

## Author
- Alish Bista
