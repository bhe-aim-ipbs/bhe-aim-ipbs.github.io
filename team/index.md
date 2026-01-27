---
title: Team
nav:
  order: 1
  tooltip: About our team
---



{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'professor'" %}

{% include section.html %}


{% include list.html data="members" component="portrait" filter="role == 'phd' and description == 'PhD Student, 2022'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd' and description == 'PhD Student, 2024'" %}
{% include list.html data="members" component="portrait" filter="role =='master' and description == 'Master Student, 2024'" %}
{% include list.html data="members" component="portrait" filter="role =='master' and description == 'Master Student, 2025, Ma'" %}
{% include list.html data="members" component="portrait" filter="role =='master' and description == 'Master Student, 2026, Qin'" %}
{% include list.html data="members" component="portrait" filter="role =='master' and description == 'Master Student, 2026, Hou'" %}
{% include list.html data="members" component="portrait" filter="role =='master' and description == 'Master Student, 2026, He'" %}

{% include section.html %}

<h2 style="text-align: center;">Graduate</h2>
{% include list.html data="members" component="portrait" filter="role == 'phd' and description == 'PhD Student, 2021'" %}
{% include list.html data="members" component="portrait" filter="name == 'Zhihao Bao'" %}
{% include list.html data="members" component="portrait" filter="name == 'Yang Tan'" %}
{% include list.html data="members" component="portrait" filter="name == 'Zhonghao Zhao'" %}
{% include list.html data="members" component="portrait" filter="role =='master' and description == 'Master Student, 2023'" %}
