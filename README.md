# Reversi Game Project

### How to run our codes
 Using the version v7.0, and our agent is in the Stupid_Agent.py.
 To test out agent with Randomagent, please type the following in the terminal:
 ```shell
 $ python3 arena.py --agent1 Stupid_Agent.StupidAgent --agent2 base_agent.RandomAgent
 ```
 
### Team members
- Team leader:
    - name: Sin-Han Yang
    - student_id: b08202029
    - github: [SINHANYANG](https://github.com/SINHANYANG)
- member:
    - name: Chun-Neng Chu
    - student_id: b09902073
    - github: [heartylearner](https://github.com/heartylearner)
### Report
- basic idea:
 By defining the "score" for getting the certain positons such as corner,edges, we can come up with a greedy choice to select the location where we put the chess on.
- Detail:
 Before each step, we checkout the whole board searching for valid places, and grading each point by their position.If it's on corners,the score is c1;else if it's on edges,the score is c2.Then we store the valid places into list 3, scores into list2.Finally,we output the place in list3 with highest score.
 Notice that if we are the white chess,we output the specific place to put the chess on in order to get higher winning chance. 

