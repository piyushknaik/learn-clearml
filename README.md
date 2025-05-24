# learn-clearml

## Getting started with Clear ML
- Install package :
  `pip install clearml`
- Connect to server :
  `clearml-init`
- Start tracking model training :
  `from clearml import Task
  task = Task.init(project_name='my_project', task_name='my_task')`

  ## Clear ML agent
