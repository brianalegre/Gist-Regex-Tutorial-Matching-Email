# Regex Tutorial - Matching An Email

A regular expression is a sequence of characters that defines a search pattern. This is commonly used to find patterns within a string, find/replace characters within a string or validate input. This tutortial will go walk through the components of a regex and how it applies to matching an email.
  
## Summary

 - Below is the regex used for validating an email address. 
 - In this tutorial, we will breakdown each part of the express and describing what it does.
   ```
   /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/. 
   ```

## Table of Contents

- [Breakdown](#breakdown)
- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Breakdown

| Syntax            |    Description                             |    Regex Component      |
| :----:            |    :---                                      |          :----:         |
|         **/^**                                                                               |
| **/**             | Editor command for search                 |                           |
| **^**             | Starting position within the string       |                           |
|         **([a-z0-9_\.-]+)**                                                                    |
| **( )**  | Defines the scope | |
| **[ ]** | Matches a single character that is contained within the brackets | [Grouping Constructs](#grouping-constructs)
| **a-z** | Character range of lowercase 'a' to lowercase 'z' | 
| **0-9** | Number range of '0' to '9' | 




<table>
    <tr>
        <td>Syntax</td>
        <td>Description</td>
        <td>Regex Component</td>
    </tr>
     <tr>
         <td colspan="3">/^</td>
     </tr>
    <tr>
        <td>/</td>
        <td>Editor command for search  </td>
        <td>[Grouping Constructs](#grouping-constructs)</td>
    </tr>
    <tr>
        <td>^</td>
        <td>Starting position within the string  </td>
        <td>[Grouping Constructs](#grouping-constructs)</td>
    </tr>
        <tr>
         <td colspan="3">([a-z0-9_\.-]+)</td>
     </tr>
    <tr>
        <td>( ) </td>
        <td>Defines the scope </td>
        <td>[Grouping Constructs](#grouping-constructs)</td>
    </tr>
    
    
</table>











--------------------------------------------------------------------------------------------
```
/^
```
- **/**     Editor command for search
- **^**     Starting position within the string

```
([a-z0-9_\.-]+)
```
- **( )** Defines the scope
- **[ ]** Matches a single character that is contained within the brackets
- **a-z** Character range of lowercase 'a' to lowercase 'z'
- **0-9** Number range of '0' to '9'





    
    ```
    ( )
    ```
        - Define the scope
    
    ```
    [ ]
    ```
        - Matches a single character that is contained within the brackets
    
    ```
    a-z
    ```
        - Character range of lowercase 'a' to lowercase 'z'
    
    ```
    0-9
    ```
        - Number range of '0' to '9'
  
  
   @
   ([\da-z\.-]+)
   \.
   ([a-z\.]{2,6})
   $/. 
   ```

## Regex Components

### Anchors

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
