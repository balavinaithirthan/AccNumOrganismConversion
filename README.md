# Accession Number Organism Converter

The **Accession Number Organism Converter** is a C++ project that utilizes the Uniprot API to convert Accession Numbers of proteins from one species to the Accession Numbers of proteins from another species by cross-referencing their protein names. This tool is particularly useful for researchers and bioinformaticians working with protein data across different organisms.

## Features

- Cross-reference Accession Numbers: Convert Accession Numbers of proteins from one species to another based on protein names.
- Utilize Uniprot API: Fetch and retrieve protein information using the Uniprot API.
- User-friendly Interface: Command-line interface for easy interaction.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/accession-organism-converter.git
   cd accession-organism-converter
   ```

2. Build the project:

   ```bash
   g++ -o converter converter.cpp
   ```

## Usage

Run the compiled executable `converter` in your terminal:

```bash
./converter
```

Follow the prompts to input the Accession Number, source organism, and target organism for conversion.

## Examples

### Example 1

Convert Accession Number from *Homo sapiens* (human) to *Mus musculus* (mouse):

```plaintext
Enter the Accession Number: P12345
Enter the source organism (e.g., Homo sapiens): Homo sapiens
Enter the target organism (e.g., Mus musculus): Mus musculus

Converting Accession Number P12345 from Homo sapiens to Mus musculus...
Conversion successful!
Accession Number in Mus musculus: P67890
```

### Example 2

Convert Accession Number from *Escherichia coli* to *Saccharomyces cerevisiae* (yeast):

```plaintext
Enter the Accession Number: Q45678
Enter the source organism (e.g., Escherichia coli): Escherichia coli
Enter the target organism (e.g., Saccharomyces cerevisiae): Saccharomyces cerevisiae

Converting Accession Number Q45678 from Escherichia coli to Saccharomyces cerevisiae...
Conversion failed. Protein not found in the target organism.
```

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m "Add feature"`.
4. Push to the branch: `git push origin feature-name`.
5. Create a pull request explaining your changes.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to contact [your name/email here] for any questions or suggestions. Happy coding!
