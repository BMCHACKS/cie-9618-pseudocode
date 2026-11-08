<img width="1280" height="720" alt="banner" src="https://github.com/user-attachments/assets/3b674189-1071-4580-b495-5b35d452aeec" />

# CIE 9618 Pseudocode

Syntax highlighting for **Cambridge International AS & A Level Computer Science (9618)** pseudocode in Visual Studio Code.

Write your pseudocode in an editor that makes it look and feel like a real language: coloured keywords, snippets, auto-indentation and code folding.

> **This extension is for visuals only.** It does **not** run, interpret, compile or debug pseudocode. Files such as `.psc` or `.pseudo` can be highlighted and edited, but they cannot be executed.

## Features

- **Syntax highlighting** for the pseudocode conventions in the 9618 Pseudocode Guide for Teachers:
  - Selection and iteration: `IF`, `ELSE`, `CASE OF`, `FOR`, `WHILE`, `REPEAT`
  - Declarations: `DECLARE`, `CONSTANT`, `TYPE`, `DEFINE`, arrays, records, enumerated, pointer and set types
  - Procedures and functions: `PROCEDURE`, `FUNCTION`, `CALL`, `RETURN`, `BYVAL`, `BYREF`
  - File handling: `OPENFILE`, `READFILE`, `WRITEFILE`, `SEEK`, `GETRECORD`, `PUTRECORD`, `CLOSEFILE`
  - Object-oriented programming: `CLASS`, `INHERITS`, `PUBLIC`, `PRIVATE`, `NEW`, `SUPER`
  - Built-in functions: `LENGTH`, `MID`, `RIGHT`, `LCASE`, `UCASE`, `INT`, `RAND`, `EOF`
  - Data types, string, char, date and numeric literals, `//` comments
  - Operators including `←` (and `<-`), `DIV`, `MOD`, `&`, `AND`, `OR`, `NOT`
- **Snippets** for common structures. Type `for`, `while`, `repeat`, `case`, `procedure`, `function`, `array`, `record`, `class`, `readfile` and so on, then press Tab.
- **Auto-indent and folding** for blocks such as `IF ... ENDIF` and `FOR ... NEXT`.
- Tab size defaults to **3 spaces** for pseudocode files, matching the guide.

## Supported file extensions

`.psc`, `.pseudo`, `.pseudocode`

You can also select **CIE 9618 Pseudocode** from the language picker at the bottom right of VS Code for any file.

## Notes

- Keywords are highlighted in **UPPER CASE only**, as the guide specifies. A lower-case `if` will not be coloured, which helps catch mistakes.
- `<-` is highlighted the same as `←`, so you can type it quickly.
- Highlighting is based on patterns, so unusual or partial code may not always colour perfectly.

## Limitations

- No execution, interpreter, debugger or output panel.
- No error checking, type checking or auto-completion of your own variables and procedures.
- Colours depend on your VS Code colour theme.

## Disclaimer

This is an independent, community-made extension. It is **not affiliated with, endorsed by, or sponsored by Cambridge University Press & Assessment or Cambridge International Education**. "Cambridge" and "9618" are used only to describe the pseudocode style the extension supports. The pseudocode conventions follow the publicly available *Pseudocode Guide for Teachers* for exams in 2026; always check the official syllabus and guide for the latest rules.

## Feedback

Found a construct that isn't highlighted correctly? Please open an issue with a short code sample.

## Release notes

### 0.1.0
- Initial release: syntax highlighting, snippets, indentation and folding.
