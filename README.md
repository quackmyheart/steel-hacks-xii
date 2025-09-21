# 5D LeetCode with Multiverse Time Travel
<img width="926" height="619" alt="steelhacksxii_logo" src="https://github.com/user-attachments/assets/486b5f40-19b1-47e7-a73a-b6b78f359648" />

Two players take turns editing one line of code at a time, creating a branching multiverse where the Solver tries to build working solutions while the Saboteur introduces bugs and errors.

##Turn Structure
1. Click a node to select it and open the code editor
2. Edit exactly one line of code in the textarea
3. Click "COMMIT MOVE" to save your changes and create a new timeline node
4. Turn switches to the other player automatically
##Key Rules
* One line per turn: You can only modify one line of code per move
* Must make a change: Empty commits are not allowed
* Node selection: Click any existing node to branch from that point
* Timeline creation: Each move creates a new node connected to the parent
