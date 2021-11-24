
          

# Github Test Page 
(Using Github page formatting features)

**Purpose** : determine ease of use for end user contribution across users and projects 

**Considerations** 
  - inline images
  - SQL syntax and highlighting 
  - images stored in another folder within the repo 
  - Ability to collaborate with other users 

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

<img width="772" alt="Screen Shot 2021-11-24 at 8 21 47 AM" src="https://user-images.githubusercontent.com/84478214/143246507-a5e2a15b-c33f-4e38-8fef-756cab997f58.png">


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

**Including Images**
   - Instructions: create new issue in repository 
     - Drag and drop (or select) image file 
     - Github will create an image code that can be copy and pasted into your page editor to populate an image 
   - Pros: fairly easy to use and navigate 
   - Cons: unable to reformat size or position, will issues become cluttered? 
<img width="849" alt="Screen Shot 2021-11-24 at 8 54 22 AM" src="https://user-images.githubusercontent.com/84478214/143251361-3f813ae3-0dcb-414e-bc1f-758ffdbeed79.png">


![alt text](./Images/Screen Shot 2021-11-24 at 9.32.48 AM.png)
![](https://github.com/cmh36346/test/blob/2ef0cb49d2919feeaf16453760dceb8c3ccf5393/Images/Screen%20Shot%202021-11-24%20at%209.32.48%20AM.png)



**Collaboration**
   - Determine ability to work with other users and not sacrifice document integrity
   - Ensure that all users have access to the repository (shouldn't be an issue for an organization-based repo. (Add specific users by navigating to repository home page > settings > manage access > add people > add user 
   - Once users have access to repositories, they are able to make changes to the page seamlessly and without limitation 
   - Important to distinguish use of commits directly to main branch versus creation of pull requests, pull requests serve as a stop gate to prevent erroneous contribution and require approval 
   - Use of commit changes and optional extended description allows for direct tagging of users and notification 
   - (This section was built by camille-huy, not cmh36346)
   


    
  <body>
    <h1>Github Test Page 2.0 </h1> <h4>Using html language</h4>
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
