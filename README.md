Clear Pull Request
=====================
> For JIRA users

## Why?
As we developers will create pull request(PR) everyday, we want to make sure our code reviewers know your PR very well, so they can give you some good suggestion. And also it's easy for you to manage your PR.
> We should create the readable PR same as our code

## Background
Each time before we start a new tickets in JIRA, we should make sure that we set it correctly. Check your tickets, does it has correct below items:
* Title
* Components
* Labels
* Type
* Fix Version
* Story Point
* Sprint
* Code Reviewer
* QA

Someone should say this will be managed by project manager, but if you want to do the ticket correct, you should at least make sure these information is filled. This is the presupposition before you implement it.

## PR
How to make a readable PR? How to let your code reviewers understand your PRs easily through very first glance.

Title is the thing that your reviewers will read. So reduce their effort to find those tickets that they needs to review. So your PR title should have:
1. PR type. Example: feature/bugfix/hotfix and others
2. Ticket Number.
3. Release Date. This is very important, cause it will save more time for your code reviewers to prioritize your PRs.
4. Component. (Optional)
5. Summary of PR. It's same as your git commit message, you should describe what do you do in this PR.
6. Description. (Optional) If your title can not explain the whole features you did, you can add description for it.



No.|Project Name | Currently Status | Planned Release | Estimate Time | Note
---|---|---|---|---|---
01|NBCU Order Sync by NBCU API | QA/UAT | 02/08 | 2 days | 
02|Addressable Placement Editor(Missing Part: https://jira.tubemogul.info/browse/PTV-11172)| In Progress | 02/22(or later) | 4 days | 
3|Update ptv-integrations-nbcu module after separating ptv-orders/ptv-inventories into microservice| Plan | 02/22 | 5 days | It needs to be finished after ptv-prders/ptv-inventories migration
4|Agency/Advertiser/Brand selection integrate with NBCU APIs when NBCU order submit  | Plan | 02/22(or later) | 3-4 days | Backend APIs are ready, it needs UI integrate with these APIs
5|Clypd Order Sync by Clypd API | Plan | after 02/22 | 10 days
6|Admin Tools Update | Plan | after 02/22 | 3 days | add some new features/optimize some existing function
7|Separate ptv-integration-nbcu as a microservice | after Clypd Release | N/A | 5 days 

