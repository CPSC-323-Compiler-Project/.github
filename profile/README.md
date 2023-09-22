# CPSC323 Projects - Fall 2023: Rat23F Language

Welcome to our group's repository for CPSC323 projects. This semester, we are delving into the intricacies of a specially designed language, Rat23F, to understand the foundational concepts of compilers and programming languages.

## 📚 Overview of Rat23F
Rat23F is a simplistic and intuitive language, designed with a short grammar and clear semantics, making it an ideal candidate for learning and experimenting. It is an imperative programming language, and every program in Rat23F consists of a sequence of functions followed by the "main body" where the program executes.

## 🛠 Projects Overview
### 1. **Lexical Analyzer (Lexer)**
   - Develop a lexer that can tokenize Rat23F source code.
   - Identify and categorize lexical units such as identifiers, keywords, integers, reals, operators, and other separators.

### 2. **Syntax Analyzer (Parser)**
   - Construct a parser that can analyze the syntactic structure of Rat23F source code.
   - Implement syntax rules to validate the source code's structure and organization.

### 3. **Semantic Analyzer**
   - Develop a semantic analyzer to interpret the meaning of syntactically correct Rat23F source code.
   - Ensure the source code adheres to the defined semantics of Rat23F.

## 🌟 Rat23F Highlights
- **Simplicity:** Easy-to-understand grammar and semantics.
- **Imperative Paradigm:** Consists of a sequence of functions followed by the main body of execution.
- **Strict Typing:** No type casting allowed, and variables and functions must be declared before use.
- **Clear Semantics:** Conventional meanings for arithmetic expressions, with specific rules and restrictions.

## 📄 Rat23F Sample Program
```plaintext
[* Sample Rat23F Program *]
function convert(fahr integer)
{
  ret 5 * (fahr -32) / 9;
}
#
integer low, high, step;
get (low, high, step);
while (low <= high)
{
  put (low);
  put (convert(low));
  low = low + step;
}
#
```

## 📢 Final Notes
- The projects are interconnected, building upon each other, emphasizing the importance of a solid understanding and implementation of the initial projects.
- Detailed specifications, rules, and guidelines for Rat23F and each project are provided in the respective project folders.

Feel free to explore the repository and delve into the fascinating world of Rat23F!
