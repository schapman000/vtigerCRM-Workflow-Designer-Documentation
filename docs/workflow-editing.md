Workflow editing
===================================================

This part covers the main improvement of the workflow designer.
You could "design" your workflow like your company could benefit most.

- **general info about tasks:**  
	Every task contains several configurations, you open with an double click or a click on the small icon top left. Also you have on almost all tasks green and red dots. The green are input and the red output points.  
	**You can only connect **
	Some tasks, like conditions have multiple output dots, because these are true/false outputs.  
	At this time, every task could have up to 3 outputs. Every output contains a tooltip, with information about the meaning.

Every workflow starts with an `[start]` task. These task is the point all executions start to process.

<img src='../images/edit_1.png'>

Inside this `[start]` block you can configure the run conditions, which I describe later.

On the right border, you see the task chooser. All tasks are sorted in several categories and could insert into the workflow with a mouse click.

If you add a task, you have to connect the correct output of the previous task with the green input of this new task.
For example it could look like this:

<img src='../images/edit_2.png'>

In this example you could see, that the task block has multiple follower. This is no problem and you could control the order, this paths are executed.
The successors will be executed from top to bottom in the graphical view.
In the image, the single condition will be executed, before the task �name contain vtiger�.
If you move the tasks, you can sort the execution sequence.