input  
```
srun -N 1 -n 1 -c 24 python crash_mock.py --first 1 --last 2
```

output  
```
DEBUG:templates.py:1246:make_star_templates: Simulating STAR template 325/635 in chunk 0/1
DEBUG:templates.py:1246:make_star_templates: Simulating STAR template 290/697 in chunk 0/1
DEBUG:templates.py:1246:make_star_templates: Simulating STAR template 540/768 in chunk 0/1
DEBUG:templates.py:1246:make_star_templates: Simulating STAR template 610/799 in chunk 0/1
DEBUG:templates.py:1246:make_star_templates: Simulating STAR template 543/659 in chunk 0/1
DEBUG:templates.py:1246:make_star_templates: Simulating STAR template 597/764 in chunk 0/1
DEBUG:templates.py:1246:make_star_templates: Simulating STAR template 425/697 in chunk 0/1
DEBUG:templates.py:1246:make_star_templates: Simulating STAR template 709/793 in chunk 0/1
DEBUG:templates.py:1246:make_star_templates: Simulating STAR template 678/725 in chunk 0/1
srun: error: nid00205: task 0: Killed
srun: Terminating job step 4718398.1
srun: Force Terminated job step 4718398.1
```
