---
title: "Add new questions"
section: "clients"
permalink: /clients/new-survey/2.html
category: new-survey
tags: [design, add, question]
icon: pencil-square
question: "How do I add new questions to my newly created survey? Will there be different types of questions for me to use (e.g. close vs. open-ended)?"
language: th
reference: CA2
---

### The answer

Enter the text of your question (i.e. What is your favorite color?) in the question box.

Optionally enter a field name for this question, if you leave it blank one will be generated for you.

If you would like to require the user to respond to this question, select `Yes` in the required field.

Choose the type of response for this question.[Click here to see Examples.]

{% include 1/alert.html type = "danger" close = "yes" icon = "exclamation-triangle" intro = "Note" msg = "To insert the survey into an existing page you must place a PHP tag in the HTML for the page." %}

Different types may have parameters to change how they behave, consult the chart below for the use of the length and precision fields.


<table class="table table-hover">
  <thead>
    <tr class="bg-primary">
      <th>Type</th>
      <th>Length</th>
      <th>Precision</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Yes/No</td>
      <td>n/a</td>
      <td>n/a</td>
    </tr>
    <tr>
      <td>Textbox</td>
      <td>length of the box</td>
      <td>max length of the text</td>
    </tr>
    <tr>
      <td>Essay</td>
      <td>columns</td>
      <td>rows</td>
    </tr>
    <tr>
      <td>Radio</td>
      <td>n/a</td>
      <td>n/a</td>
    </tr>
    <tr>
      <td>Checkboxes</td>
      <td>min #</td>
      <td>max # (not implemented yet)</td>
    </tr>
    <tr>
      <td>Dropdown</td>
      <td>n/a</td>
      <td>n/a</td>
    </tr>
    <tr>
      <td>Rate</td>
      <td>1..N</td>
      <td>Use “N/A”</td>
    </tr>
    <tr>
      <td>Date</td>
      <td>n/a</td>
      <td>n/a</td>
    </tr>
    <tr>
      <td>Numeric</td>
      <td>length</td>
      <td>precision</td>
    </tr>
  </tbody>
</table>


* If you chose a response type that has answer options, fill in one answer per line on the bottom half of the form.
* If you need more lines, click `Add another answer line`.


***Question types with answer options are: Check Boxes, Dropdown Box, Radio Buttons, Rate.***

For check boxes and radio buttons, you may enter `!other` on a line to create a fill in the blank option. An other box defaults to using the prompt Other: but is configurable by using the format: `!other=prompt text`

Add more questions by clicking the `New Question` button.

Edit/View existing questions by clicking the question numbers at the top of the form.

Click continue, or click the Questions tab at the top to proceed to the questions section.