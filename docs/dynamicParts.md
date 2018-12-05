Dynamic parts of the user interface and possible problems:

    - The counter next to "Things to do:"
        - Cannot predict how many a user will add
        - Cannot ensure user will remove ('done' or 'delete') when task is done     to ensure counter is accurate
        - Must ensure counter increases when task is added and decreases when       task is marked as 'done' or 'deleted'

    - The 'add' box
        - Cannot predict length of entry by user
        - Cannot predict characters/format used by user
        - Cannot ensure user will enter task correctly first time (spelling         errors etc.)
        - Cannot ensure user will only press 'add' once
        - Cannot ensure user will press 'add' at all (may try hitting 'enter'       etc.)
        
    - Task rows
        - Cannot know that there will always be at least one task
        - Cannot ensure user will intentially hit 'done' or 'delete' (ie. may       accidentally delete an active task)
        - Cannot predict how long the list of tasks will be
        - Cannot predict the length of the text of each task