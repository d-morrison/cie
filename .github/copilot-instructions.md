# GitHub Copilot Instructions

## Citation Requirements

**Always cite sources explicitly** when adding content to the book:

- Use proper academic citations (e.g., `@author2024title`) for all information drawn from external sources
- Add citation references to `references/references.bib` with complete bibliographic information
- Cite web resources using `@misc` entries with title, author, year, URL, and note fields
- Include citations inline at the point where information is used, not just at the end of sections
- When summarizing content from websites, cite the specific page, not just the general domain

### Examples

**Good:**
```markdown
A **collider** is a variable that is caused by two or more other variables 
in a causal diagram [@catalogofbias_collider].
```

**Bad:**
```markdown
A **collider** is a variable that is caused by two or more other variables 
in a causal diagram.
(Missing citation even though content is from catalogofbias.org)
```

### Citation Placement

- Definitions: Cite immediately after the definition
- Examples: Cite the original source AND any secondary source discussing it
- Concepts: Cite at first introduction
- Methods: Cite where the method is described

## General Guidelines

- Maintain consistency with existing book style and formatting
- Use Quarto markdown syntax
- Include proper cross-references within the book
- Test that citations render correctly in the bibliography
