# Using CloudLab

In this course, You can use CloudLab resources for your project.
CloudLab is a research facility which provides bare-metal access and control over a substantial set of computing, storage, and networking resources. 
If you haven't worked in CloudLab before, you need to [register a CloudLab account](https://cloudlab.us/signup.php).

This document walks you through the CloudLab registration process and shows you how to start an experiment in CloudLab. 

*Most importantly, it introduces our policies on using CloudLab that will be enforced throughout the semester.*

## Register A CloudLab Account

To register an account, please use your UIUC email account and NetID. 
Upload your SSH public Key file as you will be using SSH to access the nodes CloudLab assigns to you. 
Click on `Join Existing Project` and enter `uiuc-ssail-mlsys` as the project name. 
Then click on `Submit Request`. 
The project leader (TA Wangjia) will approve your request. If you have not been approved for more than 1 day, email wangjia2@illinois.edu.
See the screenshot below. 
<img width="1892" height="320" alt="image" src="https://github.com/user-attachments/assets/c5455e5e-4af3-410c-9223-c9e18e9d8751" />


If you already have a CloudLab account, simply request to join the `uiuc-ssail-mlsys` project.

## Policies on Using CloudLab Resources
1. The nodes you receive from CloudLab are real hardware machines sitting in different clusters. Therefore, we ask you not to hold the nodes for too long. CloudLab gives users 16 hours to start with, and users can extend it for a longer time. Manage your time efficiently and only hold onto those nodes when you are working on the assignment. You should use a private git repository to manage your code, and you must terminate the nodes when you are not using them. If you do have a need to extend the nodes, do not extend them by more than 1 day. **We will terminate any cluster running for more than 48 hours.**
2. As a member of the `uiuc-ssail-mlsys` project, you have permissions to access another member's private user space. **Stick to your own space and do not access others' to peek at/copy/use their code, or intentionally/unintentionally overwriting files in others' workspaces.** For more information related to this, please refer to the [UIUC Sieber School Honor Code](https://siebelschool.illinois.edu/academics/honor-code). 

