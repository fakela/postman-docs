---
title: Running Postman monitors using static IPs
order: 93
page_id: "using_static_IPs_to_monitor"
warning: false
contextual_links:
  - type: section
    name: "Prerequisites"
  - type: link
    name: "Intro to Monitoring"
    url: "/docs/designing-and-developing-your-api/monitoring-your-api/intro-monitors/"
---

> __[Static IP address monitoring is available on Postman Business and Enterprise plans.](https://www.postman.com/pricing)__

Postman Monitors access APIs from dynamic IP addresses and does not provide the option to use static IP addresses by default. For users who want to test APIs behind a whitelist restricted firewall you must request this from the [support team](https://www.postman.com/support/).

By whitelisting a single static IP address, customers can monitor their APIs using Postman’s monitoring service, while conforming to company security policies.

Note that monitoring APIs using a static IP address is available for all Postman Business and Enterprise customers. However, the static IP is a US address.

When the static IP option is enabled, users can create a new monitor or change an existing monitor to run using a static IP address.

## Creating a new monitor to run from a static IP address

In the Postman app, click the "Build" dropdown menu and select "Browse".

Choose the collection you want to monitor, click the ellipsis **(...)** icon, and select "Monitor Collection".

[![ellipsis menu](https://assets.postman.com/postman-docs/ENT-mock-collection2.png)](https://assets.postman.com/postman-docs/ENT-mock-collection2.png)

In the **MONITOR COLLECTION** modal, [enter the name and select the environment of the monitor](/docs/designing-and-developing-your-api/monitoring-your-api/setting-up-monitor/).  

In "Regions", select "US (Static IP)" to monitor the collection from a static IP address. You can also [specify a monitor to run in one or more regions](/docs/designing-and-developing-your-api/monitoring-your-api/setting-up-monitor/).

Click the **Monitor this collection** button to complete the process.

### Changing an existing monitor to run from a static IP address

In the Postman app, click the "Build" dropdown menu and select "Browse".

[![build menu](https://assets.postman.com/postman-docs/WS-build-menu1.png)](https://assets.postman.com/postman-docs/WS-build-menu1.png)

At the top of the page, select "Monitors".

Choose the monitor and click the **Edit** button.

In the **EDIT MONITOR** modal, select "US (Static IP)" in "Regions" and click the **Save Changes** button to complete the process.

[![static IP monitor](https://assets.postman.com/postman-docs/ENT-select-staticIP2.png)](https://assets.postman.com/postman-docs/ENT-select-staticIP2.png)  
