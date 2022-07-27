#### The Power BI Interface 
**Three core views:**
- Report
- Data
- Model (formerly Relationships )


**The PowerBI Workflow**
- Connect , shape and transform raw **data**
- Build table relationships to create a data **model**
- Design interactive **reports** to explore and visualize data

**Report View Tabs**
- **Home** --> Clipboard(paste,cut,copy,format painter), Data connectors(get data, excel workbook,data hub,sql server,enter data, dataverse,recent sources), Queries(transform data(Edit Queries, refresh), Insert(New Visual, Text box, More visuals), Calculations(new measure, quick measure),Sensitivity(sensitivity),Share(Publish)
- **Insert** --> Pages(new page), Visuals(new visual, more visuals), AI Visuals(Q&A, key influencers, decomposition tree, smart narrative), Power platform(Paginated report, power apps, power automate(preview)), Elements(Text box, buttons, shapes, image),Sparklines(add a sparkline)
- **Modeling** -->Relationships(Manage relationships), Calculations(New measure, quick measure, new column, new table), Page refresh(change detection), What if(new parameter),Security(manage roles, view as), Q&A(Q&A setup, language, linguistic schema)
- **View** --> Themes, Scale to fit(page view, fit to width, actual screen), Mobile(mobile layout), Page options(gridlines, snap to grid, lock objects), Show panes( filters, Bookmarks, Selection, Performance analyzer, Sync slicers)
- **Help** --> Info(about), Help(guided learning, training videos,documentatiion,support), community(powerbi blog, community, power bi for developers, submit an idea, external tools), Resources(examples, consulting services)

**Report View Tabs (contextual)**
- **Format** --> Interactions(Edit interactions, apply drill down filters to), Arrange(bring forward,bring backward,selection,align,group)
- **Data/ Drill** -->Show(visual table, data point table), Interactions(Edit interactions, apply drill down filters to), Drill actions(switch to next level, expand next level, drill up, drill down, drill through), Data groups(groups)

**Data view tabs(contextual)**

 - **Table tools** --> Access table attributes,manage relationships, and new calculations etc.
 - **Column tools** --> Access column attributes, set data types and formats, use sorting and grouping tools, etc.
 - **Measure tools** --> Access measure attributes, determine home table, set formats and categories, etc.

####  Types of data connectors

 1. **Flat files and folders**(csv,text,xls,etc)
 2. **Databases**(SQL,Access,Oracle,IBM,Azure, etc)
 3. **Online Services**(Sharepoint, Github, Dynamics 365, Google Analytics, Salesforece, PowerBI Services etc)
 4. **Others**(web feeds, R scripts, Spark, Hadoop, etc)

#### The query editor
**Home-> Transform data**

- **Query editing tools** ( table transformations, calculated columns, etc)
- **Formula Bar** ( that is M code)
- **Query pane**
- **Table Name and Properties**
- **Applied Steps** (like a macro)

#### The Query editing tools

 - The **Home** tab includes general settings and common table transformation tools
 - The **Transform** tab includes tools to modify existing columns (splitting/ grouping, transposing, extracting text, etc)
 - The **Add Column** tools create new columns(based on conditional rules, text operations, calculstions, dates etc)

#### Basic table transformations

 - **Sort values** (A-Z, Low-High , etc)
 - **Change data type** (date, $, %, text, etc.)
 - **Promote header row**
 - **Choose or remove columns** (Tip : Use the "Remove other columns" option if you always want a specific set)
 - **Keep or remove rows** (Tip : Use the "Remove Duplicates" option to create a new lookup table from scratch)
 - **Duplicate, move & rename columns** (Tip : Right-click the column header to access common tools)

#### Text-Specific tools

 - **Split a text column** based on either a specific delimiter or a number of characters
 - **Format a text column** to upper , lower or proper case, or add a prefix or suffix (Tip : Use "Trim" to eliminate leading & trailing spaces, or "clean" to remove non-printable characters)
 - **Extract characters** from a text column based on fixed lengths, first/last, ranges or delimiters (Tip : Select two or more columns to merge/ concatenate fields)
Note : You can access many of these tools in both the “**Transform**” and “**Add Column**” menus -- the difference is whether you want to add a new column or modify an existing one

#### Number Specific tools

 - **Statistics functions** allow you to evaluate basic stats for the selected column (sum, min/max, average, count, countdistinct, etc) (Note: These tools return a SINGLE value, and are commonly used to explore a table rather than prepare it for loading)
 - **Standard, Scientific and Trigonometry** tools allow you to apply standard operations (addition, multiplication, division, etc.) or more advanced calculations (power, logarithm, sine, tangent, etc) to each value in a column (Note: Unlike the Statistics options, these tools are applied to each individual row in the table)
 - **Information** tools allow you to define binary flags (TRUE/FALSE or 1/0) to mark each row in a column as even, odd, positive or negative

#### Date Specific tools

 - **Date & Time tools** are relatively straight-forward, and include the following options: 
  • **Age**: Difference between the current time and the date in each row 
  • **Date Only**: Removes the time component of a date/time field 
  • **Year/Month/Quarter/Week/Day**: Extracts individual components from a date field (Time-specific options include Hour, Minute, Second, etc.) 
  • **Earliest/Latest**: Evaluates the earliest or latest date from a column as a single value (can only be accessed from the “Transform” menu) 

**Note**: You will almost always want to perform these operations from the “Add Column” menu to build out new fields, rather than transforming an individual date/time column

**Tip** : Load up a table containing a single date column and use Date tools to build out an entire calendar table



