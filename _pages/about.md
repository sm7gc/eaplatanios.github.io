---
layout: page
permalink: /
title: about
nav: about
---

<div class="text-center mt-5">
  <img class="profile-img" src="{{ 'personal_headshot.jpg' | prepend: '/assets/img/' | prepend: site.baseurl | prepend: site.url }}">
</div>

<div class="col mt-4">
  <h1 class="title text-center font-weight-bold">Sanjana Mendu</h1>
  <div class="row mt-3 mb-3">
    <div class="col-sm-6">
      <h6 class="mt-1 text-left text-sm-right" style="font-stretch: ultra-condensed;">
        <a style="color: rgb(60, 72, 88);" href="https://engineering.virginia.edu/departments/engineering-systems-and-environment/academics/systems-engineering" target="_blank">Systems Engineering</a><br/>
        <a style="color: rgb(60, 72, 88);" href="https://engineering.virginia.edu/" target="_blank">School of Engineering and Applied Sciences</a><br/>
        <a style="color: rgb(60, 72, 88);" href="https://www.virginia.edu/" target="_blank">University of Virginia</a>
      </h6>
    </div>
    <div class="col-sm-6">
      <h6 class="mt-1 text-left text-sm-left" style="font-stretch: ultra-condensed;">
        Olsson Hall<br/>
        151 Engineer's Way<br/>
        Charlottesville, VA 22904 
      </h6>
    </div>
  </div>
</div>

<!-- Introduction -->

<div class="col text-justify p-0">
  I am a Master's student studying <a href="https://engineering.virginia.edu/departments/engineering-systems-and-environment/academics/systems-engineering" target="_blank">Systems Engineering</a> in the <a href="https://engineering.virginia.edu/departments/engineering-systems-and-environment" target="_blank">Engineering Systems and Environment Department</a> of the <a href="https://engineering.virginia.edu/" target="_blank">School of Engineering and Applied Science</a> at the <a href="https://www.virginia.edu/" target="_blank">University of Virginia</a>. My advisor is <a href="https://engineering.virginia.edu/faculty/laura-barnes" target="_blank">Dr. Laura Barnes</a> and I work on using digital data streams from mobile sensors to model behavioral health outcomes and inform just-in-time adaptive health interventions.
  <!-- My current research is motivated by the fact that real-world problems require integrating multiple, distinct modalities of information (e.g., image, audio, language, etc.) in ways that machine learning models cannot currently handle well. Most deep learning approaches are not able to utilize information learned from solving one problem to directly help in solving another. They are also not capable of <span class="font-weight-bold">never-ending learning</span>, failing on problems that are dynamic, ever-changing, and not fixed a priori, which is true of problems in the real world due to the dynamicity of nature. With my research, I aim to bridge the gap between UTCs, deep learning, and never-ending learning, by proposing <span class="font-weight-bold">neural cognitive architectures (NCAs)</span> that are inspired by human cognition and that can learn to continuously solve multiple problems that can grow in number over time, across multiple distinct perception and action modalities, and from multiple noisy sources of supervision combined with self-supervision. Their experience from learning to solve past problems can also be leveraged to learn to solve future ones. If you are interested to read more about NCAs, my <a href="{{ '/assets/pdf/thesis/proposal.pdf' | prepend: site.baseurl | prepend: site.url }}" target="_blank">thesis proposal</a> would be a good place to start. Throughout my PhD I have also worked on <a href="{{ '/projects/' | prepend: site.url }}">multiple other projects</a> related to artificial intelligence and machine learning.
  <br/><br/>
  Before I joined CMU, I graduated with an M.Eng. in <a href="http://www.imperial.ac.uk/electrical-engineering" target="_blank">Electrical and Electronic Engineering</a> from <a href="https://www.imperial.ac.uk/" target="_blank">Imperial College London</a>. For my Master's thesis I proposed a way to use topic modelling methods in order to perform human motion classification. -->
</div>

<!-- News -->
<!-- <div class="news mt-3 p-0">
  <h1 class="title mb-4 p-0">news</h1>
  {% assign news = site.news | reverse %}
  {% for item in news limit: site.news_limit %}
    <div class="row p-0">
      <div class="col-sm-2 p-0">
        <span class="badge danger-color-dark font-weight-bold text-uppercase align-middle date ml-3">
          {{ item.date | date: "%b %-d, %Y" }}
        </span>
      </div>
      <div class="col-sm-10 mt-2 mt-sm-0 ml-3 ml-md-0 p-0 font-weight-light text">
        <p>{{ item.content | remove: '<p>' | remove: '</p>' | emojify }}</p>
      </div>
    </div>
  {% endfor %}
</div> -->
