---
title: Author[s]
layout: default
---

 <h2 class="display-3" style="color:white!important">{{ site.author.name }}</h2>
  <p class="lead" style="color:blue!important">{{ site.author.description }}</p>
  <hr class="my-4">
  <h5 class="display-3">Skills</h5>
<div class="row">  
  {% for skill in site.skills %}
	<h6 style="color:white!important">{{ skill.title }} | {{skill.level}}%</h6>
		<div class="col-lg-12">
			<div class="progress progress-striped active">
				<div class="progress-bar progress-bar-{{skill.color}}" style="width: {{skill.level}}%"></div>
			</div>
		</div>	
{% endfor %}		
</div>	
