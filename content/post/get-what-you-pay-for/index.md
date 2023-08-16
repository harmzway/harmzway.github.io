---
title: Get What You Pay For
description: Get What You Pay For
slug: get-what-you-pay-for
date: 2023-08-16 00:00:00+0000
image: 1.png
categories:
    - Security
tags:
    - Cybersecurity
    - Penetration Testing
    - Red Team
    - Vulnerability Assessment
---

This article first appeared [here](https://medium.com/swlh/get-what-you-pay-for-120e391e5ea5) on Medium on July 7, 2019.

As a security consultant, I’ve seen a lot of confusion by clients about the different engagement types. I’m not sure if it’s because of the media, the vendors, or the consulting businesses themselves. It’s likely a combination of all three. I’ve spoken to many people that confuse the differences between a Vulnerability Assessment, a Penetration Test, and a Red Team Assessment. This is a problem that has been discussed in the industry for years. In fact, the great [John Strand](https://www.linkedin.com/in/john-strand-a1b4b62/) spoke about this problem during a [talk in 2014](https://youtu.be/Yo4oP2eyDtI?t=4m55s).

# Vulnerability Assessment  

A vulnerability assessment is the process of scanning, reviewing, and analyzing a network or web application for possible security weaknesses. The key objective is to find all vulnerabilities that can compromise the overall security, privacy and operations of a network or application against possible intrusions and threats. Of the three, this is the shortest assessment type and can be completed in a few minutes to a couple of days, depending on the scope.

As an example, think of a network or web application as a building. A vulnerability assessment searches for all open or unlocked doors, windows, and vents that can be entered without being blocked out. Each entry point that is discovered is identified as a vulnerability.

![](2.png)

# Penetration Test  

A penetration test goes one step further by safely attempting to exploit the vulnerabilities discovered during the vulnerability assessment. Penetration testing is an invaluable process in that it validates the efficacy of defensive mechanisms, as well as, end-user adherence to security policies. The key objective of a penetration test is to validate if all discovered vulnerabilities can be exploited. A penetration test is a longer engagement than a vulnerability assessment, and typically takes anywhere from a couple days to two weeks to complete.

Going back to the building analogy, a penetration test leverages all the identified entry points discovered the vulnerability assessment and enters the building.

![](3.png)

# Red Team Assessment  

A red team assessment is very different from the two previous engagement types, both in terms of key objective and methodology. In a red team assessment, a group of security professionals attempt to infiltrate an organization using physical pen testing, social engineering, and wireless pen testing strategies to get inside the environment. Once inside, attempts are made to gain unauthorized access to the network and exfiltrate sensitive data as quickly and quietly as possible. The key objective of a red team assessment is to test the target organization’s detection and response capabilities.

The most glaring difference between a red team assessment and a penetration test is in each engagement type’s objective. During a penetration test, the tester attempts to identify and validate all vulnerabilities by safely exploiting each one and reporting on it. In contrast, during a red team assessment a tester will focus on finding the best vulnerability to exploit. Once inside, the tester will shift focus creating persistent, long term access. From there, the tester will search for sensitive data and attempt to exfiltrate without being detected. Of the three engagement types, this is by far the most time consuming and typically takes 3–4 weeks or more to complete. Think of the movie Oceans 11 (but with written consent and no felonies being committed).

![](4.png)

# The Problem  

I’ve spoken to people about the “penetration tests” they’ve had performed in the past and what they got out of it. A common complaint I hear is that they have a hard time understanding what to do with their pen-test report because it’s several hundred pages long. When I asked if I can review it, I was handed an auto-generated report from a vulnerability scanner. This is unfortunate because for what they paid, they’re not getting a lot of value back in return. Examples like this do not serve paying customers or the industry.

It should be conveyed in the very beginning (during Pre-Engagement) that there are different engagement types for different situations and security objectives. Pretend that you’re a General with two options to choose from to solve a problem. One option is Seal Team 6, and the other option is the Marine Corps Infantry (OORAH). Both are extremely effective. One is quiet, stealthy, extremely targeted, and operates with high precision. The other isn’t as quiet, has a wide range of coverage, and uses brute strength. Both have their roles. So which one do you choose? The answer…it depends on the situation and your objective.

# The Solution 

Bring clarity to security assessments, security testing and security recommendations. The first question the tester should be asked is “Why are you having the penetration test performed?” This is important in scoping the engagement correctly. Explain the different engagement types to the customer and determine is the primary goal of the test in the very beginning. A penetration test is not about finding un-patched systems, it’s about identifying risk that will adversely impact the organization. Also, the primary goal of the test should not be about “checking boxes”. Compliance does not equal security.

Last, maybe it’s time we start calling out the security firms that pass off vulnerability assessments as penetration tests.
