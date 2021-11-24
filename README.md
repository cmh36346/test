
          

# Github Test Page 
(Using Github page formatting features)

**Purpose** : determine ease of use for end user contribution across users and projects 

**Considerations** 
  - inline images
  - SQL syntax and highlighting 
  - images stored in another folder within the repo 

**Inclusion of SQL**

```sql
-- Return table 
SELECT * FROM database.table LIMIT 10;
```
```sql
-- Create sample data
SELECT * FROM (
  VALUES
  -- case 1: 
  (1, date('2020-01-01'), 'diabetes'),
  -- case 2:
  (2, date('2020-01-01'), 'prostate cancer'),
  (2, date('2020-02-01'), 'diabetes'),
  -- case 3: 
  (3, date('2020-01-01'), 'prostate cancer'),
  (3, date('2020-01-01'), 'obesity')
)
  testcases (pid, dt, diag);
```

![Sample code output]<img width="772" alt="Screen Shot 2021-11-24 at 8 21 47 AM" src="https://user-images.githubusercontent.com/84478214/143246507-a5e2a15b-c33f-4e38-8fef-756cab997f58.png">


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
