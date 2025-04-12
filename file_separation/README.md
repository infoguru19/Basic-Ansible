# include_tasks

In Ansible, include_tasks is a module used to include a list of tasks from another file dynamically during playbook execution. It's different from import_tasks in that include_tasks is evaluated at runtime, which allows for more dynamic behavior (e.g., using variables to determine the file to include).

```
   - name: Include a task file
     include_tasks: my_tasks.yml
```


Use include_tasks when:
-------------------------
1. You need to include tasks based on a variable or condition.
2. You want the inclusion to happen during execution, not parsing.


