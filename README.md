# Streamlining IT Procurement: Automating Standard Laptop Requests in ServiceNow

## Project Overview
This project automates the IT procurement process for Standard Laptops using ServiceNow Flow Designer. It eliminates manual email approvals and task creation.

## Process Flow
1. Employee requests Standard Laptop via Service Portal (Service Catalog)
2. RITM (Requested Item) is created
3. Flow `Standard laptop task 1` triggers automatically - Trigger: Service Catalog Item Requested
4. Data Pills fetch requester details (Requested For, Location)
5. `Create Catalog Task` action creates sc_task and assigns to IT Procurement group with IF condition logic
6. Procurement team fulfills and closes the task, which auto-closes the RITM

## Key Features Implemented
- Flow Designer Automation
- Automatic Assignment Group routing
- Dynamic Task Description using Data Pills
- Conditional Logic for Laptop Types
- SLA tracking via sc_task table

## Tools Used
- ServiceNow Flow Designer
- Service Catalog
- sc_task, sc_req_item tables

## Video Demo
[Add your YouTube video link here - upload your screen recording to YouTube as Unlisted and paste link]

## Project Submission - TN Skills VTBP
This project is submitted as part of TNSDC VTBP program.

Created by: harisharajkumar344-beep
