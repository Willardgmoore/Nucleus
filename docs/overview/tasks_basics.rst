.. _tasks_basics:

Tasks
===========================

Once a project has gone Live and a team has been formed, tasks may be created. These can then be accepted and completed by members of the project earning users :ref:`contribution_basics`.

Accepting tasks
----------------

A task can only be accepted by members in the same position as the task. For instance, a Graphic Designer can only complete Graphic Designer tasks while a Node.Js developer can only complete Node.Js tasks. Makes sense right? For more information on positions, see: :ref:`positions_basics`.

There is a limit to how many tasks you can accept at any one time. The method for setting a limit on tasks will be set by the project creator via the project settings. The first way is contribution scaled which means you can accept 1 more task every multiple of the setting. For instance, if the project creator sets the limit to scale every 5 pts, then at 0-4 pts you can accept one task, at 5-9 pts you can accept two tasks and so on and so forth. The second method is to set a flat limit which is as simple as it sounds; the maximum tasks you may undertake at any one time will be this limit.

You can see what positions you are in from the Mission Control Dashboard, and you can see how many more tasks you may accept on the Mission Control Tasks page - it's the little badge that says 'Spaces'.

Completing tasks
----------------

When you've finished everything that was required for the task you can mark it as complete and fill in the completion notes. It's definitely best to be descriptive here even if you're using other services or task management tools for your project, as this is what people will see when they're reviewing your task. Linking to pull-requests, commits, uploaded documents or just writing about what you did will go a long way. Once you've submitted it, it will either be marked as complete - in which case you receive those sweet, sweet contribution points - or it'll go to review.

.. _when_task_review:

When completed tasks enter review
----------------------------------------

Once completed a task will either be marked as complete or it will automagically get sent to review if one of two conditions are met.

1. The contributor has 0 contribution points in the project

2. The contributor has had a task that failed review in the last 3 completed tasks

A third situation may occur, however: 

3. A completed task gets downvoted by other contributors. 

In this instance, the completed task will be sent back to review once the threshold is reached (~40% of voters) where it will under go the normal review process. As per the above conditions, after this, the user will require their next three tasks to be approved by the review process before they no longer automatically enter review, and instead get marked as complete straight away.

Creating tasks
----------------

Project creators and contributors who have built up the required contribution, can create tasks for team members. Tasks are created within positions - see: :ref:`positions_basics` - and can only be accepted by contributors in that position (or by the project creator). The different elements of a task are:

Title
    The name of the task, pretty self explanatory. Keep this short and concise.

Description
    Make this as detailed as possible, especially if you're not using other task management tools. There should be enough information input to tell team members exactly what needs to be done. Link to documents or to other task managers to increase the chances of a high quality completion.

Contribution points
    See: :ref:`contribution_basics`. You should set the number of points available for a task based off of the effort required to complete it. Harder tasks = more points and vice versa. A good rule of thumb is that 1 CP should pertain to roughly an 1 hour of contribution - but you can use any scale you like provided its consistent with other task creators throughout the lifetime of the project.

Priority
    Use this to indicate to contributors the urgency with which this task should be completed. You could even use this to recreate agile sprints, with high priority tasks being in the current sprint and so on.


Editing tasks
----------------

Those who have permission to create tasks can also edit a task provided the task has not been undertaken yet. All aspects of a task can be edited. There is no method for editing a task after it has been accepted by a team member.

Removing tasks
----------------

Like editing tasks, those who have permission to create a task may delete it. Again, it can only be deleted if the task is yet to be accepted.

Reviewing tasks
----------------

Once you've gained enough contribution points to 'vote' (this will be set by the project creator) you can do two things with this new found power.

1. Review tasks currently in Review

2. Downvote Completed tasks

Reviewing tasks is relatively straight forward. Simply give it a thumbs up if the task was done well and thumbs down if it wasn't. If the task gets more than 50% approval it is completed, and if it gets less than 50% approval it is sent back to the contributor to be sorted out. Think of it like a pull request coming in and either being accepted or rejected. It's not necessarily the case that the task was a complete disaster, but it might just need some refinement.

Downvoting a task can be done when a task was completed within a week and has either passed review or skipped it entirely - see: :ref:`when_task_review`. You should only really downvote a task if it genuinely has not been done to the standard required, and should others think the same (~40% of eligible voters) then it'll be sent back to review to be reviewed properly.