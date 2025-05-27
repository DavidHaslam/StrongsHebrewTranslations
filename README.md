# StrongsHebrewTranslations
Using **Excel™** to facilitate translating the definitions for **StrongsHebrew** to languages other than **English**

The worksheet **StrongsHebrew** was derived as follows:
1. Used Sword utility **mod2imp** to export module **StrongsHebrew** to a text file with raw IMP format
2. Copied the tab delimited text into the worksheet
3. Inserted a header row and applied **View** | **Freeze Panes** | **Freeze Top Row**
4. Selected whole sheet & applied **Conditional Formating** for empty cells to have grey fill
5. Selected Columns L through P (3 entries have misplaced data) & applied **Conditional Formating** for empty cells to have light orange fill
6. Set vertical alignment = top
7. Set all cells to wrap text
8. Adjusted row height to automatic, thus fitting every definition within its cell, without hiding any part thereof.
9. Hide all intermediate empty columns {B, D, F, H} caused by the second tab between text fields.
10. Selected Column A & applied **Conditional Formating** for cells containing **$$$** to display Bold.
11. Hide all rows that are blank (except for column A which contains the $$$nnnnn = numerical entry identifiers)
12. Adjusted column widths for columns still visible: {A, C, E, G, I}
13. Hidden columns {C, E, G} leaving only columns {A, I} visible. Column I contains the **Definitions**.
14. Made column K narrower than the default (although this column is empty, it makes the next step easier)
15. Adjusted **View** | **Zoom** to fit columns A though K.
16. Set **Data** | **Filter** (facilitating displaying selected entries as & when required)

## Derived file[s]
The file <code>Definitions.English.txt</code> was made by pasting the filtered **Column I** labeled **Definition** to a Text Editor.<br/>
This is the only portion of the IMP file that requires translating.
