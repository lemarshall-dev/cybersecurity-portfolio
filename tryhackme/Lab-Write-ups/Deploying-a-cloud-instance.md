# Deploying a cloud instance - Lab 1

## Main Objective

Create three virtual computers (EC2 Instances) to host a cyber security training app. 

## Tools Used
- TryHackMe Cloud Console (VM Instance)

## Methodology
I should give each of the three VM machines a name so they can be identified easily and managed on a seperate basis. 
I should also give them an instance type in accordance to how much power each VM will need to operate effectivley, I'll need to consider carefully as more powerful types will also cost more per month to run. 
I'll use the less powerful t3.micro type for the user interface machine and m5.large instance types for the two testing machines as these two will require more oomph.

Now that I've set them up on the cloud console, I should look into costs to make sure I'm not running anything unecessarily whilst in the testing phase.

After analysing the cost of running this 3 VM set up, I've noticed it's costing me 170 credits per month, seeing as we're testing and don't have any users, it doesn't make sense to keep all three running at the same time so I should at least stop the two testing machines.
After stopping the two test machines, I've reduced the ruunning cost down to 30 credits a month. 
I'll re-activate them as and when I need them until the application launches to public.

## Key findings

## What I learned

