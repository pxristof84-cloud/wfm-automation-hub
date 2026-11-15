# WFM Automation & Intelligence Hub

A standalone, interactive workforce management portfolio prototype. Built with AI assistance to demonstrate business process modeling, operational reporting concepts, and a scheduling approval workflow.

## Try the demo
Open the GitHub Pages link (after Pages is enabled), or download and open `index.html` in a browser.

## Implemented
- Synthetic staffing KPI cards and interval coverage chart
- Scheduling request submission
- Approve/reject actions with state transitions
- Simulated audit log
- Browser-local persistence

## Proposed Microsoft architecture — NOT implemented
- Power Apps Canvas: request and approval interface
- Power Automate: notifications and approval workflows
- SharePoint Lists / Dataverse: controlled data storage
- Power Query and Power BI: data preparation and analytics

This demo is **not a Power Apps application** and does not have live Power Automate, SharePoint, Dataverse, or Power BI connections. It uses no real workforce or employer data.

## Interview talking points
Explain the business process, submit and approve a request, show the log, and discuss how you would implement authentication, permissions, integration, exception handling, and deployment in Microsoft Power Platform.

## Publish
In GitHub repository **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
