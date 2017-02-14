* v0.0.15
  * Fix force new line for yield.
  * Fix force new line for default(T).
* v0.0.14
  * Fix for escaped strings formatting (double quotes and @ prefix).
  * /\* fixformat ignore:start \*/ and /\* fixformat ignore:end \*/ directives added
  for ignore formatting between them.
  * Refactoring.
* v0.0.13
  * Fix for string interpolators formatting.
  * Code cleanup.
* v0.0.12
  * "csharpfixformat.style.spaces.beforeBracket" default value changed to false.
  * Fix for #region / endregion formatting.
  * "csharpfixformat.style.indent.regionIgnored" option was added.
    > Should #region / #endregion directives ignore indentation or use it.
* v0.0.11
  * All style reformatting respect single line / multiline comments and strings.
  * Fix for preprocessor directives started from "!".
  * Fix for "braces.allowInlines"=true for multiple expressions in line.
  * Fix closing brace indentation for enums.
  * Improve internal error processing.
* v0.0.10
  * Keybinding "ctrl+alt+i" was added for formatting activation.
  * "csharpfixformat.style.activateDefaultFormatterAfter" option was added.
    > Should default code formatter be activated as post process.
  * "csharpfixformat.style.braces.onSameLine" option was added.
    > Should open braces be kept on expression line (K&R style) or on new line.
  * "csharpfixformat.style.braces.allowInlines" option was added.
    > Allow expressions inside braces at one line.
  * "csharpfixformat.style.spaces.beforeParenthesis" option was added.
    > Space before '(' - opening parenthesis.
  * "csharpfixformat.style.spaces.afterParenthesis" option was added.
    > Space after ')' - closing parenthesis.
  * "csharpfixformat.style.spaces.beforeBracket" option was added.
    > Space before '[' - opening bracket.
  * "csharpfixformat.style.spaces.afterBracket" option was added.
    > Space after ']' - closing bracket.
  * "csharpfixformat.style.spaces.insideEmptyParenthis" option was added.
    > Space inside '()' - empty parenthis.
  * "csharpfixformat.style.spaces.insideEmptyBraces" option was added.
    > Space inside '{}' - empty braces.
  * "csharpfixformat.style.spaces.insideEmptyBrackets" option was added.
    > Space inside '[]' - empty brackets.
  * Fix colons / generics formatting.
  * Fix usings sorting as one block after splitting.
* v0.0.9
  * Code style code was removed, js-beautify uses instead.
  * Sort using can be disabled.
  * Code style formatting can be disabled.
  * Config options were refactored.
  * "csharpfixformat.sort.usings.enabled" option was added.
    > Should usings be sorted or not.
  * "csharpfixformat.sort.usings.systemFirst" option was added.
    > Put System.xxx namespaces first at usings list on sorting.
  * "csharpfixformat.sort.usings.splitGroups" option was added.
    > Insert blank line between using blocks grouped by first part of namespace.
  * "csharpfixformat.style.enabled" option was added.
    > Enable code reformat with style options.
  * "csharpfixformat.style.newline.maxAmount" option was added.
    > Amount of new line (\n) symbols allowed in row. 1 means no blank lines. Use 0 for disable.
  * "csharpfixformat.style.indent.preprocessorIgnored" option was added.
    > Should preprocessor directives ignore indentation or use it.
* v0.0.8
  * Sort usings logic fixes, doubles in usings will be removed automatically.
  * Warning notification was added.
  * Indentation fixes for multiline assign expressions.
  * Performance fix for indentEnabled = false.
  * tslint fixes.
* v0.0.7
  * Indentation fix for content after single line comments with "{", "(", etc.
* v0.0.6
  * Correct sorting of using lines with chars in different cases (like "S" and "s").
  * "csharpfixformat.indentPreprocessor" option was added.
    > Indent preprocessor defines or put them without indentation. Disable by default.
* v0.0.5
  * Switch-case indentation fixed.
* v0.0.4
  * Comment skipping. Dont use tail comments at using line - they will be removed!
  No limits for other places for tail comments.
  * Indent of wrapped lines with not finished assign expression should be fixed.
* v0.0.3
  * "Sort usings" command renamed to "Fix format".
  * "csharpfixformat.indentEnabled" option was added.
    > Indent all lines with respect of parentheses / braces and use "editor.tabSize" parameter. Enabled by default.
  * "csharpfixformat.emptyLinesInRowLimit" option was added.
    > Amount of empty lines in row, negative value for disable. By default 1 empty line allowed between expressions.
  * Sort usings should works correctly for multiple using expressions in line.
  * Sort usings should ignore commented expressions (if usings put at begining of each line inside multiline comment - they will be sorted).
  * Refactoring.
* v0.0.2
  * Debug logging removed.
  * Refactoring.
* v0.0.1
  * Init release.