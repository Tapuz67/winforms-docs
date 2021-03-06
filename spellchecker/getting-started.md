---
title: Getting Started
page_title: Getting Started | UI for WinForms Documentation
description: Getting Started
slug: winforms/spellchecker/getting-started
tags: getting,started
published: True
position: 1
previous_url: spellchecker-getting-started
---

# Getting Started



The following tutorial demonstrates how you can make RadSpellChecker check a simple text-editing control - RadTextBox.
      

>note Before executing the following steps, please make sure that the target framework of the project in which you are going to use RadSpellChecker is .NET Framework 4.0. This will allow you to see RadSpellChecker in your Toolbox and work with it.
>


1. Drag and drop RadTextBox from your Toolbox to your form.

1. Drag and drop RadSpellChecker from your Toolbox to your form.

1. Drag and drop RadButton from your Toolbox to your form. When clicked this button will invoke the spell-checking capabilities of RadSpellChecker.
          

1. Set the text of RadTextBox so that it contains some typos, for example:

{{source=..\SamplesCS\SpellChecker\SpChGettingStarted.cs region=settingText}} 
{{source=..\SamplesVB\SpellChecker\SpChGettingStarted.vb region=settingText}} 

````C#
this.radTextBox1.Text = "The quik broun foxx jumpd ovur lasy dog";

````
````VB.NET
Me.RadTextBox1.Text = "The quik broun foxx jumpd ovur lasy dog"

````

{{endregion}} 


5\. Subscribe to the Click event of the button. In the event handler call the Check method of RadSpellChecker and pass the RadTextBox instance as a parameter:

{{source=..\SamplesCS\SpellChecker\SpChGettingStarted.cs region=callingCheck}} 
{{source=..\SamplesVB\SpellChecker\SpChGettingStarted.vb region=callingCheck}} 

````C#
private void radButton1_Click(object sender, EventArgs e)
{
    this.radSpellChecker1.Check(this.radTextBox1);
}

````
````VB.NET
Private Sub RadButton1_Click(ByVal sender As Object, ByVal e As System.EventArgs) Handles RadButton1.Click
    Me.RadSpellChecker1.Check(Me.RadTextBox1)
End Sub

````

{{endregion}} 

Now when you press the button, RadSpellChecker form will appear with the appropriate suggestions for the mistaken words:

![spellchecker-overview 001](images/spellchecker-overview001.png)
