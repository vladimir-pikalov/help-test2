---
layout: default
---
# Root welcome page

# Everest™ Overview

Everest Software, Inc. welcomes you to **Everest**, the next generation business automation software. We, at Everest Software, understand that software does not run businesses; people do. Unlike some other business software, **Everest** does not require you to change the way you do your business; it follows real-life business processes. 

**Everest** is a fully-integrated, award-winning business management software solution that is quick-to-implement, and easy-to-use. It is designed to automate all departments of a small business, including accounting, inventory control, service, e-commerce, sales force automation, CRM, point of sale, wireless connectivity, and more, in real-time. Everest empowers the people who run your business. It automates routine business functions, giving managers more time to concentrate on strategic areas. It enhances the quality of decision-making by providing pertinent, time-critical information at your fingertips.

Owners and managers looking for the robustness and scalability of a SQL Server database; multi-currency; and integrated e-mail capabilities can now get all the help they will ever need in terms of automation, from these and other features in this edition. 

With **Everest Advanced Edition**, you get a powerful yet affordable solution, right out-of-the-box.




{% comment %}
{% assign pgs = site.pages | where:"toc-root", "true" %}

{% for p in pgs %}
  <ul>
    <li>Page:</li>
    <li>{{p}}</li>
  </ul>
{% endfor %}

    {% assign tocPage = site.pages | where:"path", "topics/index.md" | first %}

    <p>tocPage:</p>
    <p>{{tocPage}}</p>

{% endcomment %}