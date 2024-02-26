### EX NO: 01 
### DATE:
# <p align="center">MDP REPRESENTATION</p>

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

1.Text representation

2.Graphical representation

3.Python - Dictonary representation

## PROBLEM STATEMENT:

### Problem Description

Enhancing the efficiency of a robotic vaccum cleaner in cleaning a household by using reinforcement learning to optimize its cleaning strategies.
### State Space:
1.Room A
2.Room B
3.Room C

### Sample State
Room A

### Action Space
1)Moving Right
2)Moving Left
3)Suck Dirt

### Sample Action

Moving Right

### Reward Function

- +1 - when the agent move to the right side and suck the dirt or when the room is cleaned
- 0 - Otherwise

### Graphical Representation

![WhatsApp Image 2024-02-26 at 11 41 50 PM](https://github.com/harini1006/mdp-representation/assets/113497405/766b4f38-bc05-427a-8f6a-c0ab6341b484)


## PYTHON REPRESENTATION:
```python
# Developed by: HARINI V
# Register Number: 212222230044

P = {
    0:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,0,0.0,True)]
    },
    1:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,2,1.0,True)]
    },
    2:{
        0: [(1.0,2,0.0,True)],
        1: [(1.0,2,0.0,True)]
    }
}
```
## OUTPUT:

![image](https://github.com/harini1006/mdp-representation/assets/113497405/48e83aef-866d-45b0-abcf-5a237d6ba2ac)


## RESULT:

Thus the given real world problem is successfully represented in a MDP form.



