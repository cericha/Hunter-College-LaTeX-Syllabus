# LaTeX Syllabus Template for CUNY Hunter College

This is a LaTeX template for a CUNY Hunter College Syllabus. It adheres to the best practices as outlined in the CUNY Hunter College Syllabus guidelines. Every course is unique and has different specific syllabus requirements. With that in mind, this template is designed to be highly modular and easily customizable.

Each section of the syllabus is maintained in a separate `.tex` file, allowing for easy modifications and additions for different syllabus structures. 

Please refer to the most up to date information on CUNY, Hunter College, and departmental policies regarding syllabus structure when using this template. See [License for Use](#license-for-use) information at bottom of README.

## Structure

- **`syllabus.tex`**: This is the main LaTeX file. It sets up the document style, defines the document title, and imports each syllabus section from the `sections/` directory. It uses information from `config.tex` to specify dynamic content in the document.
- **`config.tex`**: Contains definitions for global parameters such as course number, section, semester, and instructor information. Adjusting the values in `config.tex` will automatically update them throughout the document.
- **`sections/`**: This directory contains separate `.tex` files for each syllabus section:
  - `course_details.tex` – Course information and instructor details.
  - `course_description.tex` – Detailed course description.
  - `prerequisites.tex` – Course prerequisites.
  - `textbooks.tex` – Lists of required and optional textbooks.
  - `grading_statement.tex` – Grading criteria and policies.
  - `learning_outcomes.tex` – Required section on expected learning outcomes.
  - `attendance.tex` – Optional attendance policy.
  - `academic_integrity.tex` – Required academic integrity guidelines.
  - `adastatement.tex` – Recommended ADA compliance statement.
  - `policy_sexual_misconduct.tex` – Required policy on sexual misconduct.
  - `syllabus_change_policy.tex` – Policy on changes to the syllabus.

## Usage

To use this template:
1. Clone or download the repository as a .zip file.
2. Edit the `config.tex` and section files in the `sections/` directory to customize the syllabus for your course.
3. Compile `syllabus.tex` using your preferred LaTeX compiler. Alternatively, Overleaf.com provides an online platform for using LaTeX without the need to install software locally.

### Additional Resources

- [Hunter College Syllabus Checklist (August 2020)](https://www.hunter.cuny.edu/provost/repository/files/Hunter%20College%20Syllabus%20Checklist_Aug2020%20-1.pdf)
- [Overleaf Documentation and Tutorials](https://www.overleaf.com/learn)

## License for Use

This syllabus template is provided as a guideline to assist instructors and professors at CUNY Hunter College in developing their course syllabi. While this template aims to reflect best practices and conform to institutional guidelines, CUNY and Hunter College are the final authorities on what constitutes a valid and conforming syllabus.

Users of this template are responsible for ensuring that their syllabus meets all relevant CUNY, Hunter College, and departmental policies. The creators of this template make no warranties regarding the compliance of this template with current or future institutional policies.
