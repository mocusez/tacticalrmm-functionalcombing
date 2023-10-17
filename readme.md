# TacticalRMM-functional combing

<div id="toc">

[TacticalRMM-functional combing](#tacticalrmm-functional-combing)  
 [Device operation](#device-operation)  
  [Summary](#summary)  
  [Checks](#checks)  
  [Tasks](#tasks)  
  [Patches](#patches)  
  [Software](#software)  
  [History](#history)  
  [Assets](#assets)  
  [Audit](#audit)  
 [Agents](#agents)  
  [Install Agent](#install-agent)  
  [Deploy managements](#deploy-managements)  
  [Update Agent](#update-agent)  
 [View](#view)  
  [Pending actions](#pending-actions)  
 [Logs](#logs)  
 [Tools](#tools)  
  [Bulk operation](#bulk-operation)  
  [Bulk Patch Management](#bulk-patch-management)  
  [Server Maintenance](#server-maintenance)  
 [Settings](#settings)  
  [Clients manager](#clients-manager)  
  [Script manager](#script-manager)  
  [Automation manager](#automation-manager)  
  [Alert manager](#alert-manager)  
  [Permissions manager](#permissions-manager)  
  [User Admission](#user-admission)  
  [Global settings](#global-settings)  
  [Code Signing](#code-signing)  
 [Account](#account)  
  [2FA and password](#2fa-and-password)  
 [Help](#help)

</div>

## Device operation

### Summary

Output hardware information, hardware check status and disks information

![](source.assets/image-20231017111841169.png)

### Checks

Output the result of maintenance script

![](source.assets/image-20231017112350315.png)

Show run history

![](source.assets/image-20231017152009559.png)

Show last output history

![](source.assets/image-20231017152042439.png)

### Tasks

Output situation of tasks working(Only support on Windows)

![](source.assets/image-20231017112432584.png)

### Patches

Output patches situation of Windows(Only support on Windows)

Support CSV output

![](source.assets/image-20231017112602901.png)

### Software

Software installed information of system(Only support on Windows)

Support CSV output

![](source.assets/image-20231017112621509.png)

### History

Output history of script work

Support CSV output

![](source.assets/image-20231017112711766.png)

### Assets

Output device assets

Include: CPU, Memory, USB, BIOS etc.

(Only support on windows)

![](source.assets/image-20231017113010806.png)

### Audit

Audit user's action on device

Support CSV output

![](source.assets/image-20231017113140127.png)

## Agents

Agents management

about agents install/update/manage

![](source.assets/image-20231017113458558.png)

### Install Agent

At first, we must choose site and client

Then choose Server or Workstation

If we choose windows, we can open RDP and enable ping

There are three installation method: exe, PowerShell, Manual

![](source.assets/image-20231017171409689.png)

The install on Linux and MacOS are simple

![](source.assets/image-20231017171846154.png)

The admin should download the application/script to make it work

### Deploy managements

I do not make sure how it work, it seems to provide a link to download
the agents

it can be add/delete operation

![](source.assets/image-20231017172233420.png)

### Update Agent

update the agent which has been installed

![](source.assets/image-20231017172526854.png)

## View

### Pending actions

Recent tasks or checks

![](source.assets/image-20231017172840042.png)

## Logs

Output admin operations log

Allow to output on CSV format

![](source.assets/image-20231017113613773.png)

support search on type or log message

![](source.assets/image-20231017173448423.png)

## Tools

Support Bulk operation(script or command) and essential operation and
maintenance platform

![](source.assets/image-20231017113704720.png)

### Bulk operation

![](source.assets/image-20231017153034078.png)

### Bulk Patch Management

Support patches scan of bulk of Windows machine

![](source.assets/image-20231017154129424.png)

### Server Maintenance

![](source.assets/image-20231017150646726.png)

## Settings

The settings of system

![](source.assets/image-20231017113954359.png)

### Clients manager

add/delete/change the site

![](source.assets/image-20231017162019843.png)

### Script manager

Public script management

support Folder View/Table view

add/upload new script

![](source.assets/image-20231017114231661.png)

change script property and content

![](source.assets/image-20231017162506282.png)

### Automation manager

Automate tasks and check scripts

**support policy management**

![](source.assets/image-20231017163447325.png)

### Alert manager

Support to send information to SMS/Email

![](source.assets/image-20231017163846368.png)

When alert happen, the system will do **task** or **script** to deal
with situation

![](source.assets/image-20231017164424202.png)

Supports customized risk levels

![](source.assets/image-20231017164349671.png)

### Permissions manager

Regulate platform managers based on RBAC rules

![](source.assets/image-20231017164559498.png)

![](source.assets/image-20231017164908873.png)

### User Admission

Add/Edit User

![](source.assets/image-20231017165838277.png)

![](source.assets/image-20231017170057428.png)

### Global settings

platform basic settings:

time zone, date format, Email/SMS settings, mash center

![](source.assets/image-20231017170233745.png)

Log info store

![](source.assets/image-20231017170711349.png)

API keys management: add/delete/find/change

![](source.assets/image-20231017170828432.png)

### Code Signing

Add certificate to the agents to avoid antivirus trouble

![](source.assets/image-20231017170907215.png)

## Account

### 2FA and password

Support 2FA (TOTP) and password reset

## Help

Support information

![](source.assets/image-20231017113825280.png)
