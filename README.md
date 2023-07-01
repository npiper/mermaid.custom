# Mermaid Styling

## Gantt Charts

The CSS classes used in the Mermaid Gantt chart can be found in the mermaid.scss file on the official Mermaid GitHub repository. Here are the main CSS classes used for styling the Gantt chart:

.mermaid - The main container for the Mermaid chart.
.node - The container for each chart node (task or milestone).
.node rect - The rectangular shape representing a task or milestone.
.node text - The text label associated with a task or milestone.
.node text.label - The label text specifically for tasks and milestones.
.node rect.task - The specific CSS class for styling tasks.
.node rect.milestone - The specific CSS class for styling milestones.
.section - The container for a section of the Gantt chart.
.section rect - The background rectangle for a section.
.section text - The text label for a section.
.section text.title - The title text for a section.
.section rect.section-line - The line separating sections.


### Forest Theme



https://github.com/mermaid-js/mermaid/blob/b34f7bcdd5ccca50e30efef90de7f2be301000ba/src/themes/theme-forest.js

```

    /* Base vales */
    this.background = '#f4f4f4';
    this.primaryColor = '#cde498';
    this.secondaryColor = '#cdffb2';
    this.background = 'white';
    this.mainBkg = '#cde498';
    this.secondBkg = '#cdffb2';
    this.lineColor = 'green';
    this.border1 = '#13540c';
    this.border2 = '#6eaa49';
    this.arrowheadColor = 'green';
    this.fontFamily = '"trebuchet ms", verdana, arial, sans-serif';
    this.fontSize = '16px';

    this.tertiaryColor = lighten('#cde498', 10);
    this.primaryBorderColor = mkBorder(this.primaryColor, this.darkMode);
    this.secondaryBorderColor = mkBorder(this.secondaryColor, this.darkMode);
    this.tertiaryBorderColor = mkBorder(this.tertiaryColor, this.darkMode);
    this.primaryTextColor = invert(this.primaryColor);
    this.secondaryTextColor = invert(this.secondaryColor);
    this.tertiaryTextColor = invert(this.primaryColor);
    this.lineColor = invert(this.background);
    this.textColor = invert(this.background);


    /* Gantt chart variables */

    this.sectionBkgColor = '#6eaa49';
    this.altSectionBkgColor = 'white';
    this.sectionBkgColor2 = '#6eaa49';
    this.taskBorderColor = 'calculated';
    this.taskBkgColor = '#487e3a';
    this.taskTextLightColor = 'white';
    this.taskTextColor = 'calculated';
    this.taskTextDarkColor = 'black';
    this.taskTextOutsideColor = 'calculated';
    this.taskTextClickableColor = '#003163';
    this.activeTaskBorderColor = 'calculated';
    this.activeTaskBkgColor = 'calculated';
    this.gridColor = 'lightgrey';
    this.doneTaskBkgColor = 'lightgrey';
    this.doneTaskBorderColor = 'grey';
    this.critBorderColor = '#ff8888';
    this.critBkgColor = 'red';
    this.todayLineColor = 'red';
```


## Examples

## Refs

https://mermaid.js.org/syntax/gantt.html

https://github.com/mermaid-js/mermaid/blob/b34f7bcdd5ccca50e30efef90de7f2be301000ba/src/themes/mermaid.scss

## Themes

Closest want to customise is 
https://github.com/mermaid-js/mermaid/blob/b34f7bcdd5ccca50e30efef90de7f2be301000ba/src/themes/theme-forest.js

