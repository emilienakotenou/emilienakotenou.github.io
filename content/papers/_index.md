---
title: ""
aliases: /papers/
description: "Research Papers"
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
button.accordion {
font:14px/1.5 Lato, "Helvetica Neue", Helvetica, Arial, sans-serif;
cursor: pointer;
padding: 0px;
border: none;
text-align: left;
outline: none;
font-size: 100%;
transition: 0.3s;
background-color: #f8f8f8;
}
button.accordion.active, button.accordion:hover {
background-color: #f8f8f8;
}
button.accordion:after {
content: " [+] ";
font-size: 90%;
color:#777;
float: left;
margin-left: 1px;
}
button.accordion.active:after {
content: " [\2212] ";
}
div.panel {
padding: 0 20px;
margin-top: 5px;
display: none;
background-color: white;
font-size: 100%;
}
div.panel.show {
display: block !important;
}
</style>

<h2><a id="working-papers" class="anchor" href="#workingpapers" aria-hidden="true"><span class="octicon octicon-link"></span></a><i class="fas fa-file-alt" style="color: #1976d2; margin-right: 8px;"></i>Working Papers</h2>

<p style="margin:0"> <a style="margin:0; font-size:100%; font-weight:bold">Does Internet Expansion Improve Employment and Health Outcomes? Evidence from Broadband Rollout in Kenya</a> <br> Emilien Akotenou <br><button class="accordion">Abstract</button><div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;"><p>High fertility rates remain a binding constraint on women's labor market participation in sub-Saharan Africa. This paper asks whether digital infrastructure can reduce this constraint. Exploiting the staggered rollout of fiber optic backbone nodes following Kenya's 2009 submarine cable arrival, I construct a woman-by-year panel from Demographic and Health Survey birth histories and define treatment as residing within 10 kilometers of an active node. Two-way fixed effects and Callaway-Sant'Anna (2021) estimates show that broadband exposure reduces the likelihood of giving birth by 0.7–1.0 percentage points and widens birth spacing. Node arrival shifts women into non-agricultural employment, raising the opportunity cost of childbearing through both the labor market and information channels. Instrumental variable estimates using road network proximity confirm robustness to endogenous placement. Digital infrastructure reduces barriers to women's economic participation.</p></div><p style="margin:0"><button class="accordion">Download</button><div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;"><p><a href="/job_market_paper.pdf">Paper</a></p></div><p style="margin:0"><button class="accordion">BibTeX citation</button><div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;"><p><pre><code>@unpublished{akotenou2025internet,
  author = {Emilien Akotenou},
  title  = {Does Internet Expansion Improve Employment and Health Outcomes? Evidence from Broadband Rollout in Kenya},
  year   = {2025},
  note   = {Working Paper}
}</code></pre></p></div><br>

<p style="margin:0"> <a style="margin:0; font-size:100%; font-weight:bold">Beyond Effort: Inequality of Opportunity in Adolescent Development</a> <br> with Berk Olzer, Sarah Baird, Joan Hamory, and Nicola Jones &nbsp;&bull;&nbsp; <i>Under Review</i> <br><button class="accordion">Abstract</button><div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;"><p>This paper analyzes inequality of opportunity in adolescent outcomes in Ethiopia, focusing on how circumstances beyond individual control shape early life trajectories. Using the inequality of opportunity framework developed by Roemer (1998), we quantify the share of inequality attributable to the birth lottery. We draw on longitudinal data from the Gender and Adolescence: Global Evidence (GAGE) study and examine outcomes observed in early-to-mid adolescence, including schooling, NEET status, and cognitive achievement measured by Raven's Progressive Matrices. We extend the literature by incorporating disability and its intersection with gender alongside traditional family background variables such as parental education and region of birth. Using parametric and non-parametric decomposition methods, we find that while disability and gender are negatively associated with outcomes, parental education and birth region account for the majority of inequality of opportunity. Parental secondary education is highly protective across multiple dimensions.</p></div><p style="margin:0"><button class="accordion">BibTeX citation</button><div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;"><p><pre><code>@unpublished{olzer_et_al2025inequality,
  author = {Berk Olzer and Emilien Akotenou and Sarah Baird and Joan Hamory and Nicola Jones},
  title  = {Beyond Effort: Inequality of Opportunity in Adolescent Development},
  year   = {2025},
  note   = {Under Review}
}</code></pre></p></div><br>

<hr>

<h2><a id="works-in-progress" class="anchor" href="#workinprogress" aria-hidden="true"><span class="octicon octicon-link"></span></a><i class="fas fa-clipboard-list" style="color: #1976d2; margin-right: 8px;"></i>Works in Progress</h2>

<p style="margin:0"> <b>Growing Up in Conflict: Conflict and Youth Human Capital Trajectory</b> <br> with Joan Hamory <br><button class="accordion">Abstract</button><div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;"><p>Armed conflict can disrupt schooling, work, health, and psychosocial well-being, yet credible evidence on youth impacts remains limited in many settings. This study links Ethiopian household–youth panel data from 2017–2023 with geocoded conflict event data to examine how changes in local conflict exposure affect youth outcomes. Conflict is measured at the local level using events, fatal events, and fatalities, with specifications that capture both the onset of conflict after 2018 and year-to-year variation in intensity. Simple averages suggest substantial differences between conflict-exposed and non-exposed locations, motivating a research design based on location and year fixed effects and dynamic models that track outcomes around conflict timing. The paper evaluates impacts on education, labor participation, food insecurity, health, resilience, social support, and aspirations, aiming to inform youth-focused policies in conflict-affected areas.</p></div><br>

<script> 
var acc = document.getElementsByClassName("accordion");
var i;
for (i = 0; i < acc.length; i++) {
    acc[i].onclick = function(){
        this.classList.toggle("active");
        this.parentNode.nextElementSibling.classList.toggle("show");
  }
}
</script>
