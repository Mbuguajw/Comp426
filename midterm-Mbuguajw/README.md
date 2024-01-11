[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=7276759&assignment_repo_type=AssignmentRepo)
# COMP 426 Midterm Exam

*Spring 2022*

**This exam will be open from 2022-03-01 to 2022-03-11 (beginning of UNC Spring break).**

## Instructions

Please read through these instructions fully before beginning.

1. Clone this starter repository.
2. Initialize this repository as an NPM package. Your `package.json` file *MUST* contain the following information:
  1. `package name` field must be set to `midterm`.
  2. `version` field set to `22.2.2`.
  3. `description` field set to `COMP 426 midterm exam`.
  4. `entry point` field set to `index.js`.
  5. `test command` field set to `node index.js`.
  6. `author` field set to your GitHub username.
  7. `license` field set to `GPL-3.0-or-later`.
3. Create a file `index.js` in the root of your repository.
4. Run `npm install md5`. Look at its documentation for usage: https://www.npmjs.com/package/md5
5. Follow this link and fill out the survey: https://unc.az1.qualtrics.com/jfe/form/SV_0koT7MDXpATYfcO (password: ThisIsNotATest)
6. At the end of the survey you will be given a REFERENCECODE. Copy this reference code down precisely.
7. In your `index.js` file, define a const named `examcode` with your reference code as the value.
8. Require the `md5` package in your `index.js` file.
9. Use the `md5()` function to hash the reference code you stored as `examcode` (per package documentation listed above) and then echo the result back out onto STDOUT using `console.log()`.
10. Make sure that your script works by running your test.
11. Make sure that all of your changes are committed and push the repository to submit the exam.
12. If something doesn't quite work, you can edit and resubmit your code.

The steps above are all things that you should be familiar with from the first part of this course.
You may not be familiar with the `md5` package, but you should be able to figure out how to use it from its linked documentation. 
If you follow the intstructions precisely, then everything should work just fine.

This work should be done alone.
The TAs have been instructed not to help with the steps of the exam.
These are all things that you should be well able to do by this point in the class.

Good skill!
