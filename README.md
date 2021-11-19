
          

# Github Test Page 
(Using Github page formatting features)

**Purpose** : determine ease of use for end user contribution across users and projects 

**Considerations** 
  - inline images
  - SQL syntax and highlighting 
  - images stored in another folder within the repo 

**Cons**
  - A lot of unique formatting nuances that vary (spacing, indenting, bolding)

**Benefits** 
  - Somewhat understandable/intuitive formatting nuances 
  - Ability to call out users or teams within the organization which triggers a notification (@cmh36346) 
  - Ability to reference specific issues and pages

**Formatting Nuances**
   - Headers: precede titles using #, ##, or ######
   - Spacing: pressing enter key once will push text to the next line in the editor field but requires being hit twice to produce a correctly spaced final github page 
   - Fenced Code Block: Using triple back-ticks to create a fence code block, and further specifying that code block with language type

**Inclusion of SQL**

```sql

SELECT * FROM database.table LIMIT 10;
```
```sql
SELECT * FROM (
  VALUES
  -- case 1: should not be returned
  (1, date('2020-01-01')),
  -- case 2: should be returned
  (2, date('2020-01-01')),
  (2, date('2020-02-01')),
  -- case 3: should not be returned (edge case)
  (3, date('2020-01-01')),
  (3, date('2020-01-01'))
)
  testcases (pid, dt);
```




    
  <body>
    <h1>Github Test Page</h1> <h4>Using html language</h4>
    <h4>Similar purpose as above</h4>
    <h4>Considerations</h4>
      <ul>
        <li>inline images</li>
        <li>SQL syntax and highlighting </li>
        <li>images stored in another folder within the repoRestricted by lack of previous HTML experience</li>
          </ul>      
    <h4>Cons</h4>
      <ul>
        <li>Restricted by lack of previous HTML experience</li>
        <li>Github-specific formatting nuances, e.g. line breaks in H1-H3 headers</li>
          </ul>
  </body>
</html>
