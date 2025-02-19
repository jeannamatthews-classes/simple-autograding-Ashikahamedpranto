# Difference Between a Text File and a Markdown File

A **text file** (.txt) and a **markdown file** (.md) may seem similar at first, but they serve different purposes and have distinct features:

## 1. **Content**
- **Text File**: Contains plain text with no formatting options. It’s just raw text, and there is no support for things like headings, bold or italic text, or hyperlinks.
- **Markdown File**: Contains plain text as well, but it allows you to format the text using special syntax. You can add headings, bold or italic text, lists, links, images, and more.

## 2. **Use Cases**
- **Text File**: Best for storing raw data, notes, or any other form of unformatted text.
- **Markdown File**: Used primarily for creating documents with rich formatting that can be easily converted to HTML for web publishing. Markdown is commonly used for README files, documentation, and writing blogs.

## 3. **Syntax and Structure**
- **Text File**: No special syntax. Every character is just plain text.
- **Markdown File**: Includes formatting syntax such as:
    - `#` for headers
    - `**bold**` for bold text
    - `*italic*` for italic text
    - `-` or `*` for lists
 
#### In a Markdown file:
```markdown
# My Header
Here is **bold** text and *italic* text.

#### Adding the additional information about the repository name to the markdown file

additional_info = """
## 4. Repository Created
I created a repository called **Second_Assignment** using my user dashboard. This repository is designed to hold the files and documentation related to my second assignment. 
"""

# Opening the existing markdown file and appending the additional information
with open(file_path_markdown, 'a') as file:
    file.write(additional_info)

file_path_markdown


my repository name is Second_Assignment

