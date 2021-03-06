---
title: Scrolling Programmatically
page_title: Scrolling Programmatically | UI for WinForms Documentation
description: Scrolling Programmatically
slug: winforms/gridview/scrolling/scrolling-programmatically
tags: scrolling,programmatically
published: True
position: 1
previous_url: gridview-scrolling-scrolling-programmatically
---

# Scrolling Programmatically

## Scrolling programmatically

You can scroll programmatically using the following functions:

#### ScrollTo

{{source=..\SamplesCS\GridView\Scrolling\Scrolling.cs region=ScrollTo}} 
{{source=..\SamplesVB\GridView\Scrolling\Scrolling.vb region=ScrollTo}} 

````C#
this.radGridView1.TableElement.ScrollTo(5, 4);

````
````VB.NET
Me.RadGridView1.TableElement.ScrollTo(5, 4)

````

{{endregion}} 


#### ScrollToColumn

{{source=..\SamplesCS\GridView\Scrolling\Scrolling.cs region=Column}} 
{{source=..\SamplesVB\GridView\Scrolling\Scrolling.vb region=Column}} 

````C#
radGridView1.TableElement.ScrollToColumn(3);

````
````VB.NET
RadGridView1.TableElement.ScrollToColumn(3)

````

{{endregion}} 


#### ScrollToRow

{{source=..\SamplesCS\GridView\Scrolling\Scrolling.cs region=Row}} 
{{source=..\SamplesVB\GridView\Scrolling\Scrolling.vb region=Row}} 

````C#
radGridView1.TableElement.ScrollToRow(100);

````
````VB.NET
RadGridView1.TableElement.ScrollToRow(100)

````

{{endregion}} 

## Properties

The following properties are useful when you need to control the scrolling functionality:

* __EnableFastScrolling__ - controls the fast scrolling mode.
            

* __EnableKineticScrolling__ - controls the kinetic scrolling function.
            

* __UseScrollbarsInHierarchy__ - enable or disable the dedicated vertical scrollbars in hierarchy.
            

# See Also

 * [Scrolling Support]({%slug winforms/gridview/end-user-capabilities/scrolling-support%})
