# Standard-commit-message
:sunny: Generic standard of a commit message


## The seven rules of a greate git commit message

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
6. Wrap the body at 72 characters
7. Use the body to explain *what* and *why* vs. *how*

## Something else

Subject include three fields: `type(Y)`, `scope(N)`, `subject(Y)`

`tyepe` use to explain type of this commit, include seven Identifications:
    
    * Feature
    * Fix
    * Docs
    * Style
    * Refactor
    * Test
    * Chore

**Example**

    <type>(<scope>): <subject>
    // blank line
    <body>
    // blank line
    <footer>

**NOTE**

    footer part is only used in two cases:
        
      - Breaking change
        
        *Breaking change: Some explain*
          
      - Close issue

