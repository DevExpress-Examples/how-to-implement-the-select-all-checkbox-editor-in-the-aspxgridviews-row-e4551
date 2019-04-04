<!-- default file list -->
*Files to look at*:

* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
<!-- default file list end -->
# How to implement the "Select All" CheckBox editor in the ASPxGridView's row


<p>This example shows how to implement the "Select All" CheckBox editor in the ASPxGridView's row.</p><p>If an end-user checks the ASPxCheckBox in the ASPxGridView's "All" column, other ASPxCheckBoxes in this row will set checked. If an end-user unchecks the ASPxCheckBox in the ASPxGridView's "All" column, other ASPxCheckBoxes in this row will set unchecked. If all CheckBoxes in the ASPxGridView's row are checked the ASPxCheckBox  in the ASPxGridView's "All" columns will set checked. If at least one of CheckBoxes in the ASPxGridView's row is unchecked, the ASPxCheckBox in the ASPxGridView's "All" columns will set unchecked.</p><p>To implement this scenario you can handle the <a href="ms-help://MS.MSDNQTR.v90.en/fxref_system.web.ui/html/658e894b-5faa-036a-e26c-a50f8eec5176.htm"><u>ASPxCheckBox.Init</u></a> and <a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxEditorsScriptsASPxClientCheckBox_CheckedChangedtopic"><u>ASPxClientCheckBox.CheckedChanged</u></a> events for all CheckBoxs.</p>

<br/>


