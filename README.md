projects = [
    {"name": "Django Portfolio", "status": "Completed", "version": 3.2},
    {"name": "DBMS Connector", "status": "In Progress", "version": 1.0},
    {"name": "GitHub Tracker", "status": "Started Today", "version": 0.1}
]

def check_progress(project_list):
    print("--- Gaurav's Project Dashboard ---")
    for project in project_list:
        print(f"Project: {project['name']} | Status: {project['status']}")
check_progress(projects) 
