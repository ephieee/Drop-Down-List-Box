# Drop-Down-List-Box

<select>
A drop down list box (also known as a select box) allows users to select one option from a drop down list. 
The <select> element is used to create a drop down list box. It contains two or more <option> elements. 
name
The name attribute indicates the name of the form control being sent to the server, along with the value the user selected.
<option>
The <option> element is used to specify the options that the user can select from. The words between the opening <option> and closing </option> tags will be shown to the user in the drop down box.
value
The <option> element uses the value attribute to indicate the value that is sent to the server along with the name of the control if this option is selected.
selected
The selected attribute can be used to indicate the option that should be selected when the page loads. The value of this attribute should be selected. If this attribute is not used, the first option will be shown when the page loads. If the user does not select an option, then the first item will be sent to the server as the value for this control.
The function of the drop down list box is similar to that of the radio buttons (in that only one option can be selected). There are two key factors in choosing which to use:
1. If users need to see all options at a glance, radio buttons are better suited.
2. If there is a very long list of options (such as a list of countries), drop down list boxes work better.

<form action="http://www.example.com/profile.php">
 <p>What device do you listen to music on?</p>
 <select name="devices">
   <option value="ipod">iPod</option>
   <option value="radio">Radio</option>
   <option value="computer">Computer</option>
 </select>
</form>
