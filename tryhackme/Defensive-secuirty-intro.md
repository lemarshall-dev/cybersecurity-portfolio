# TryHackMe Defensive Security Intro Write-up

## Objective

Introducing defensive security, where I will protect FakeBank from an ongoing attack.

## Tools Used

-TryHackMe platform
-Virtual lab machine

## What I did
-Used the virtual lab machine to use an SOC operators security dashboard to spot any suspicious traffic. Pulled the source IP address from the suspicious traffic alert.
-Added a firewall rule using the virtual dashboard to block all actions from the attackers source IP address.


## What I learned
-Defensive security is focused on detecting and investigating attacks, and responding before any damage is done. The opposite of Offensive Security.
-In defensive security, containment is always the immediate priority when attacks are attempted. Finer details can be investigated and any vulnerabilities fixed after the issue is contained.
-Blocking the IP address: Prevents the attacker's device from accessing our systems entirely. A good immediate step.
-Applying Rate Limiting: Limits the number of connections possible in a given time for everyone. Effective if attacker is rapidly accessing many pages at once, potentially overwhelming the targets systems.
-Updating Security Rules: Tightens access controls to sensitive pages that the attacker is able to slip through.
