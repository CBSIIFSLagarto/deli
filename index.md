---
layout: default
---
      {% include header_fast.html %}
      {% comment %} the generateion of navPanel (the mobile hamburger menu) ran faster than
                    the actual nav generation in header; so we are using header_fast.html

              EDIT: Should just get header.html to also write the navPanel instead of using JS!
        {% include header.html %}
      {% endcomment %}

      {% comment %}{% include _banner.html %}{% endcomment %}
      {% include _banner_basic.html %}

 			{% include _sec_intro.html %}

			{% include _sec_aboutus.html %}
			{% include _pic1.html %}

      {% include _sec_menu.html %}
      {% include _pic2.html %}

      {% comment %}{% include _4.html %}{% endcomment %}
      {% include _sec_space.html %}

			{% include _5.html %}

			{% include footer.html %}
