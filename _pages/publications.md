---
layout: archive
permalink: /publications/
title: "Publications"
author_profile: true
---


Manuscripts in Review
======
- Starr, L. D., **He, Y.,** Mason, R. P., Hammerschmidt, C. R., Newell, S. E. & Lamborg, C. H. Mercury distribution and speciation along the U.S. GEOTRACES GP15 Pacific Meridional Transect. _(In Review: Journal of Geophysical Research – Oceans)_
- **He, Y.,** Inman, H., Kadko, D., Stephens, M., Hammond, D., Landing, W., & Mason, R. P. Elevated methylmercury in Arctic rain and aerosol linked to air-sea exchange of dimethylmercury. _(In Review: Science Advances)_
- **He, Y.,** Kadko, D., Stephens, M., Sheridan, M., Buck, C. S., Marsay, C. M., Landing, W., Zheng, M., & Liu, P. Constraining aerosol deposition over the global ocean using radioisotope beryllium-7. _(In Review: Nature Geoscience)_
- **He, Y.,** & Mason, R. P. Improving a continuous mercury analyzer with circulated carrier gas: economic and operational advancements. _(In Review: Atmospheric Environment)_

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">1my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-new.html %}
{% endfor %}
