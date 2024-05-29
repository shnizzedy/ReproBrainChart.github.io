---
layout: home
title: "Reproducible Brain Charts"
author_profile: false
---

<div style="text-align: center;">
     <img src="{{ site.baseurl}}/assets/images/logos/rbc_primary_logo.png" width="700" height="300" />
</div>

<br/>
<hr>
<br/>

<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
     <ol class="carousel-indicators">
          <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
     </ol>
     <div class="carousel-inner">
          <div class="carousel-item active">
               <img class="d-block w-100" src="{{ site.baseurl}}/assets/images/banners/rbc_corticalthickness_v2.png" alt="First slide">
               <!-- No text on carousel for now
               <div class="carousel-caption d-none d-md-block">
               <h5>{{ page.title }}</h5>
               </div>
               -->
          </div>
          <!--The arrows seem to fail
          <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
          </a>
          -->
     </div>
</div>

<br/>
<hr>
<br/>

<p style="text-align:center;">
     <p style="display:flex; align-items:left;">
          <b>
               RBC: An open resource for studies of the developing brain and mental health
          </b>
     </p>
     <p>
          Major mental illnesses are increasingly understood as disorders of brain development.
          Progress requires defining both typical brain development in healthy kids and variation associated with diverse symptoms of mental illness.
          To accelerate this effort, RBC aggregates several of the largest studies of brain development in youth as publicly available data resource for the scientific community.
     </p>
     <br>
     <p style="display:flex; align-items:left;">
          <b>
               A harmonized data resource
          </b>
     </p>
     <p>
          Combining data across different studies is a challenge.
          Investigators are usually faced with different psychiatric assessments, multiple scanners, and discrepant processing pipelines.
          RBC overcomes these obstacles by harmonizing mental health symptoms in a framework that capture major axes of psychiatric symptoms.
          Similarly, imaging data is carefully curated, undergoes the same quality assurance protocol, and is processed using the same pipeline.
          This allows scientists to skip such time-consuming steps and make discoveries faster.
     </p>
     <br>
     <p style="display:flex; align-items:left;">
          <b>
               Reproducible and open science
          </b>
     </p>
     <p>
          Every element of RBC is open and reproducible – including image curation, image processing, and all analyses.
          Each step is tracked using DataLad, which provides version control for data just like Git provides version control for code.
          RBC thus combines open data and open code to maximize reproducibility and enhance confidence.
     </p>
     <br>
</p>

### TODO: Replace BHRC logo
<div style="text-align: center;">
     <h2>Contributing Institutions</h2>
     <br/>

     <div style="display: flex; justify-content: space-between; width: 100%; margin: auto;">
          <img src="{{ site.baseurl}}/assets/images/logos/university_of_pennsylvania.png" style="width: 60 px;height: 150px;" />
          <img src="{{ site.baseurl}}/assets/images/logos/child_mind_institute.png" style="width: 60 px;height: 150px;" />
          <img src="{{ site.baseurl}}/assets/images/logos/NKI.png" style="width: 60 px;height: 150px;" />
          <img src="{{ site.baseurl}}/assets/images/logos/CHOP.png" style="width: 60 px;height: 150px;" />
          <img src="{{ site.baseurl}}/assets/images/logos/beijing_normal_university.png" style="width: 80 px;height: 150px;" />
          <img src="{{ site.baseurl}}/assets/images/logos/columbia_university.png" style="width: 100 px; height: 150px;" />
          <img src="{{ site.baseurl}}/assets/images/logos/BHRC.png" style="width: 100 px; height: 150px;" />
          <img src="{{ site.baseurl}}/assets/images/team/placeholder-user.png" style="width: 100 px; height: 150px;" />
     </div>

</div>

<br/>
<br/>

<div style="text-align: center;">
     <h2>RBC Downloads</h2>
     <br/>

     <iframe src="{{ site.baseurl}}/assets/dashboard.html" width="100%" height="550px" style="border: none;"></iframe>
</div>
