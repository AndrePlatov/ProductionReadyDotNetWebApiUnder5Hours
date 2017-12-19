# ProductionReadyDotNetWebApiUnder5Hours
Creating ASP.NET Web API 2 based app under 5 hours

Functional Requirements:
A Todo app
* Add/Complete/Edit/Delete/View Task(s)

Tech Requirements:
* Solution must be split into Front and Back ends
* Store data in memory
* Use ASP.NET Web API 2 runing on .Net 4.6 for back end


Assumptions
* I am developping a FinTech app, meaning it must be secure, performant and scalable.

Data modeling
* ToDoList object containing 0 or more tasks.
* ToDoTask object containing task name, description and status.

UI:
* List View containing To Do tasks (Name) and actions
  List Actions:
  * Add
  Task Actions:
  * View Details
  * Edit
  * Complete (hides task from the list)
  * Delete
* Task View showing Task details (Name + description)

API:
* Task Controller
  * Get Tasks (all incomplete)
  * New Task
  * Get Task Details
  * Update Task Details
  * Complete Task (set status to complete)
  * Delete Task


Solution Quality Requirments:
* Secure
* performant
* scalable
* remember state (nice to have)

