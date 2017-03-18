READ ME 

#v1.0
This is a project implemented by Vue.js -- A new javascript framework.
Its functions are as follows : 

1.input a task to to in input element, and it will be added to task list below, and input will be cleared.
在输入框中输入一条任务，该任务会被添加到下面的任务列表中，且输入框中刚刚输入的文字会被自动清空。

2.double click any one task in task list, an input element will appear in place of the task, original text
of the task will be put in the input element, and at the end of the text will obtain the mouse focus.
双击任务列表中的任意一条任务,会出现一个输入框,任务框中是之前任务的文字，文字末尾会获取鼠标的输入光标。

3.Any one task in the task list can be deleted by clicking cross sign.
每一条任务都可以通过点击叉号被删除。

4.Any one task can be marked as completed by clicking checkbox.
每一条任务都可以用过勾选来表示已经完成。

5.Above the task list, there will be " Still n tasks to go ". n will be unfullfilled task in list.
任务列表上方，会显示“还有n条任务未完成”。

6.When there is no task in list, there will be a sign saying "Please input some task to do ".
在任务列表中还没有任务时，会显示“还没有输入任何任务”。

7.Currently we will use localStorage to fetch and save task list data.
暂时用本地存储，存取任务列表的数据的变化。

8.There will be a tab component, saying "All, Completed, Not completed".
会有一套控件，可以分别显示所有任务，已完成任务，和未完成任务。

