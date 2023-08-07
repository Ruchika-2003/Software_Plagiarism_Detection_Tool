# Software_Plagiarism_Detection_Tool

## Overview
  The Software Plagiarism Detection Tool (SPDT) is a sophisticated utility designed to aid in the detection of plagiarism within C++ programming language code. SPDT    employs advanced techniques to analyze the structural similarity of code snippets and provides insightful results, including a percentage similarity score and a      conclusion regarding the presence of plagiarism. Additionally, SPDT offers a visual representation of the code differences using the Gumtree Diff Tool, enhancing     the comprehensibility of the analysis.

## Features
- Accurate Plagiarism Detection:
 SPDT leverages the concept of abstract syntax trees (ASTs) to assess the structural resemblance between code samples. It employs the Zhang-Shasha algorithm to 
 compute the minimum number of edit operations required to transform one AST into another. This value is then utilized to calculate the percentage similarity between 
 the input code snippets.

- User-Friendly Input:
  Users can input either the names of individual files or directories containing multiple files for analysis. SPDT processes these inputs and generates comprehensive 
  reports.

- Detailed Output:
 SPDT generates an output report for each analyzed code pair, consisting of the percentage similarity score and a conclusive statement regarding the presence of 
 plagiarism. This provides users with clear insights into the authenticity of the code.

- Visual Comparison: 
 SPDT enhances its analysis by visually presenting the differences between code snippets. The Gumtree Diff Tool highlights the exact modifications made to the code, 
 making it easier for users to identify potential instances of plagiarism.
