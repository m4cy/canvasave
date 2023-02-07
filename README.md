# canvasave
assignment submission reminder system

# things to do:
- oauth thing
- script needs to be run every day. if <time-interval> before assignment due date there is no submission still, it should text you.
    - options:
        - mac cronjob, linux whatever whatever, etc.
        - run when open calendar?
- can change time interval in command line
    - accept multiple time intervals
- needs to get your phone number or email and send notifications
- omg graphql https://canvas.instructure.com/doc/api/file.graphql.html
- look into canvas graphql, copy setup from NASA projects

# exploration:
-IF USING REST API
- https://canvas.instructure.com/doc/api/assignments.html 
    - Assignment object due_at, submission
    - list assignments GET bucket unsubmitted, order_by due_at
- https://canvas.instructure.com/doc/api/users.html
    - User List the TODO items type submitting
- could use random canvas API https://canvasapi.readthedocs.io/en/stable/getting-started.html
