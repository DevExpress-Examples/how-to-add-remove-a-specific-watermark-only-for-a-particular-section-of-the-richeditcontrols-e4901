<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/WindowsFormsApplication1/Form1.cs) (VB: [Form1.vb](./VB/WindowsFormsApplication1/Form1.vb))
* [Program.cs](./CS/WindowsFormsApplication1/Program.cs) (VB: [Program.vb](./VB/WindowsFormsApplication1/Program.vb))
* [StringSample.cs](./CS/WindowsFormsApplication1/StringSample.cs) (VB: [StringSample.vb](./VB/WindowsFormsApplication1/StringSample.vb))
<!-- default file list end -->
# How to add (remove) a specific watermark only for a particular section of the RichEditControl's document


<p>This example extends the approach demonstrated in the following example: <a href="https://www.devexpress.com/Support/Center/p/E4184">How to add a watermark with a text or image to the document</a></p><p>The main idea of the approach demonstrated in this sample is to add/remove a watermark only for a currently selected section.</p><p>For this purpose, two items were added to the RichEditControl's context menu:</p><p>- "Add watermark". This item click results in opening a file dialog to select an image. This image will be inserted as a watermark for a currently selected section.</p><p>- "Remove watermark". This item click results in deleting the watermark only from the currently selected section.</p>

<br/>


