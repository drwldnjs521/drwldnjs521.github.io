---
title: The stakeholder Requirements
layout: post
author: Jeewon
date: 2022-11-10 17:18:00 -0000
categories: [Mobile App Dev]
tags: [Flutter, Dart, Mobile App, stakeholder requirements]
---

This posting is about [**stakeholder requirements**][sr-medium] of the Perixx Outbound System, often referred to as user needs or user requirements, which describe what users do with the system, such as the activities that users must be able to perform. 
This program can be divided into 4 features.

# Stakeholder Requirements

## In general

- [ ] The perixx outbound App should run on Android and also on IOS. (It will be focused mainly on ios)
- [ ] The language of the **POA** (Perixx Outbound App) should be set as default according to the device setting. 
- [ ] The language of the **POA** can be changed if required.
- [ ] Languages to be selected are english and germany.
- [ ] The **POA** enable to work more effectively and faster than without the **POA**.
- [ ] With the **POA** papers can be saved for printing.

## 4 Features

### LOGIN

- [x] Only staff members who are allowed can use the **POA**.
- [x] Accounts should be set up by administrators and then provided to staff members.
- [x] Users can also log out.
- [x] If a user mistype his account, this should be noticed with details.

### ORDER LIST

- [ ] Orders can be filtered by date and status (not worked/scanned/shipped). 
- [ ] When an order has the status "shipped", it should be directly linked to the print page on the order list page.
- [ ] Orders which are not worked and orders in shipping should be distinguished.

### SCAN

- [ ] All products of **Perixx** should be scanned with the scan gun.
- [ ] If an item is scanned that belongs to multiple orders, the **POA** system will indicate which order should be processed first.
- [ ] If an wrong item is scanned, which does not belong to today's orders, this should be noticed. 
- [ ] When all items of an order have been scanned, the **POA** system displays the order for delivery processing.

### PRINT
- [ ] All documents of an order, needed to be delivered, can be printed.
- [ ] Documents which are already printed should be distinguished.


For better understanding, please have a look at the [**details**][details] sketch

[sr-medium]: https://medium.com/@nhan.tran/business-requirements-vs-stakeholder-requirements-8a5127c4fb12
[details]:https://drwldnjs521.github.io/posts/details/