<h1 id="publications"></h1>

<h2 style="margin: 60px 0px -15px;">Publications <temp style="font-size:15px;">[</temp><a href="https://scholar.google.com/citations?user=HGhm8g0AAAAJ&hl=en" target="_blank" style="font-size:15px;">Google Scholar</a><temp style="font-size:15px;">]</temp><temp style="font-size:15px;">[</temp><a href="https://dblp.org/pid/155/8045-6.html" target="_blank" style="font-size:15px;">DBLP</a><temp style="font-size:15px;">]</temp></h2>


<div class="publications" style="margin-left: 20px;">
<ol class="bibliography">

<h3 style="margin: 20px 0px 15px; font-size: 18px; color: #333;">Fluid Simulation</h3>

{% for link in site.data.publications.Fluid_Simulation %}

<li>
<div class="pub-row">
  <div class="col-sm-12" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em>
      </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.data %} 
      <a href="{{ link.data }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Dataset</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c; font-weight:600">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<br>

{% endfor %}

<h3 style="margin: 20px 0px 15px; font-size: 18px; color: #333;">High-fieldity Reconstruction</h3>

{% for link in site.data.publications.High-fieldity_Reconstruction %}

<li>
<div class="pub-row">
  <div class="col-sm-12" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em>
      </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.talk %} 
      <a href="{{ link.talk }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Talk</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c; font-weight:600">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<br>

{% endfor %}



<h3 style="margin: 20px 0px 15px; font-size: 18px; color: #333;">Stochastic Process and Privacy</h3>

{% for link in site.data.publications.Stochastic_Process_and_Privacy %}

<li>
<div class="pub-row">
  <div class="col-sm-12" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em>
      </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.talk %} 
      <a href="{{ link.talk }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Talk</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c; font-weight:600">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<br>

{% endfor %}


<h3 style="margin: 20px 0px 15px; font-size: 18px; color: #333;">Data Analysis and Machine Learning</h3>

{% for link in site.data.publications.Data_Analysis_and_Machine_Learning %}

<li>
<div class="pub-row">
  <div class="col-sm-12" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em>
      </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.talk %} 
      <a href="{{ link.talk }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Talk</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c; font-weight:600">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<br>

{% endfor %}


<h3 style="margin: 20px 0px 15px; font-size: 18px; color: #333;">Other Projects</h3>


<table style="width:100%; border: none;">
   <tr>
    <th style="border-bottom: 0;color: #595959;font: 16.0px/1.5 Crimson Pro, serif;"><p align="center"><img src="../assets/img/T.gif" width="400" alt="Plasma Ignition Simulation"></p></th>
    <th style="border-bottom: 0;color: #595959;font: 16.0px/1.5 Crimson Pro, serif;"><p><strong>Physical simluation for plasma ignition</strong><br>Use OpenFOAM to conduct the simluation for plasma ignition. Constrcut a simple framework to simulation this phenomenon and try to find the insights for engineering. [<a href="https://github.com/qingxu-thu/plasma_ignite">code</a>]</p></th>
  </tr>
  <tr>
    <th style="border-bottom: 0;color: #595959;font: 16.0px/1.5 Crimson Pro, serif;"><p align="center"><img src="../assets/img/gs.gif" width="400" alt="Plasma Ignition Simulation"></p></th>
    <th style="border-bottom: 0;color: #595959;font: 16.0px/1.5 Crimson Pro, serif;"><p><strong>High-fidelity Gaussian Blendshapes </strong><br>Use multiple high resolution cameras to construct the blendshapes for human head with 3D Gaussian splatting. [<a href="https://drive.google.com/file/d/1vYyign7oV-nO6pZeOcSlaxuZsqFYHxk_/view?usp=drive_link">code</a>]</p></th>
  </tr>
</table>

</ol>
</div>


