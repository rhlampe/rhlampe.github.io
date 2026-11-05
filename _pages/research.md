---
layout: page
permalink: /research/
title: Research
nav: true
nav_order: 1
_styles: |
  .post-header {
    text-align: center;
  }
  div.container.mt-5 {
    max-width: 870px;
  }
  #field-sample-map {
    max-width: 450px;
  }
  @media (max-width: 575px) {
    #field-sample-map {
      max-width: 300px;
    }
  }
---

<style>
  .figure-row { display: flow-root; }
  .float-figure { float: right; width: 38%; margin: 0.25rem 0 1rem 1.5rem; }
  .float-figure.portrait { width: 28%; }
  .float-figure.narrow { width: 20%; }
  @media (max-width: 576px) {
    .figure-row { display: flex; flex-direction: column; }
    .float-figure { order: 1; float: none; width: 100% !important; margin: 0 0 1rem 0; }
    .float-figure.narrow { max-width: 220px; align-self: center; }
  }
</style>

<div class="figure-row" markdown="1">

<div class="float-figure narrow">
  <img src="{{ '/assets/img/california_chlorophyll.jpg' | relative_url }}" alt="Satellite image of chlorophyll concentration along the California coast, highest near shore" class="img-fluid rounded" />
  <div class="caption">Satellite-derived chlorophyll in the California Current. Credit: NASA</div>
</div>

### Patterns in phytoplankton abundances, community structure, and function

As phytoplankton are the base of the marine food web and are responsible for ~50% of primary production on Earth, differences in their abundance, community composition, and physiology influence fisheries and carbon sequestration. Uncovering patterns that answer fundamental questions (who is there, when are they there, and what are they doing?) and connecting those answers to food web dynamics and biogeochemical cycling helps us understand, model, and predict processes occurring in ecosystems. Coupling large omics datasets with biogeochemical and ecological data (environmental conditions, rate processes, abundances of higher trophic levels) allows these connections and patterns to be discerned. In particular, I have been focused on phytoplankton communities in the California Current Ecosystem, a highly productive coastal upwelling system. By generating an omics-based time series within an existing oceanographic monitoring program (CalCOFI), we are addressing some of these questions. Recently, I published a [paper](https://doi.org/10.5194/bg-22-6787-2025) connecting omics measurements to phytoplankton pigments, which not only supports the development of new remote sensing algorithms but also offers insight into the relationship between phytoplankton productivity and diversity. Ongoing research is focused on identifying patterns with respect to diatoms, one of the most ecologically important groups in the region.

</div>

### Molecular mechanisms for nutrient use and responses to nutrient limitation

<div class="figure-row" markdown="1">

<div class="float-figure">
  <img src="{{ '/assets/img/incubators.jpg' | relative_url }}" alt="Clear incubators filled with seawater on the deck of a research vessel" class="img-fluid rounded" />
  <div class="caption">On-deck incubators for nutrient addition experiments.</div>
</div>

Phytoplankton growth in the ocean is limited by a variety of nutrients, including nitrogen, iron, and vitamins. On a cellular level, demand for nutrients and membrane space available for uptake form the basis for nutrient limitation. As a result, I investigate nutrient acquisition, use, and limitation both in natural communities and in individual cells. Previous and current research has examined responses to nitrogen and iron availability among diverse phytoplankton lineages. Recently, I published a [review](https://doi.org/10.1146/annurev-micro-041222-023252) describing iron acquisition, use, and responses to limitation in phytoplankton. I have also been using full-factorial, trace metal clean incubation experiments in the California Current, Indian Ocean, and Southern Ocean to evaluate the order of limiting nutrients in natural communities.

</div>

### Responses to natural disturbances, long-term environmental change, and anthropogenic influences

<div class="figure-row" markdown="1">

<div class="float-figure portrait">
  <img src="{{ '/assets/img/oa_incubation.jpg' | relative_url }}" alt="Seawater carboys with gas lines in an incubator for a trace metal clean ocean acidification experiment" class="img-fluid rounded" />
  <div class="caption">Trace metal clean ocean acidification incubations.</div>
</div>

Phytoplankton experience a variety of ecological disturbances and environmental changes over short to long time scales, such as upwelling and El Niño. On top of natural variability, anthropogenic influences and climate change alter the marine environment. Both natural and anthropogenic change need to be understood to forecast changes in phytoplankton communities. With observations that span different environmental conditions and experiments that simulate future change, I aim to understand how phytoplankton respond to changes in their environment. Previous research has explored phytoplankton responses to [upwelling](https://doi.org/10.1111/1462-2920.14361) and [ocean acidification](https://doi.org/10.1038/s41467-023-42949-1). With long-term and large-scale observations, I am also examining temperature ranges for diverse phytoplankton and potential changes from marine heatwaves or El Niño.

</div>

### Development and optimization of methods for high-throughput omics

<div class="figure-row" markdown="1">

<div class="float-figure">
  <img src="{{ '/assets/img/kingfisher.jpg' | relative_url }}" alt="Thermo Fisher Scientific KingFisher loaded with 96-well plates for automated nucleic acid purification" class="img-fluid rounded" />
  <div class="caption">Automated nucleic acid purification with a Thermo Fisher Scientific KingFisher.</div>
</div>

Continual advances in sequencing and mass spectrometry are increasing both the number of samples that can feasibly be analyzed and the amount of data generated from each sample. Taking advantage of these developments to produce larger, more detailed datasets requires improvements at every step, from sample collection through extraction, purification, and bioinformatics. By developing wet-lab protocols that leverage automation platforms (e.g., Eppendorf epMotion, Thermo Fisher Scientific KingFisher) alongside bioinformatic workflows, we can generate the large datasets needed to address ecological questions. Some of these methods are available on my [protocols](/protocols/) page.

</div>

<h3 style="text-align: center;">Field Sample Locations</h3>

<div style="text-align: center;">
  <img id="field-sample-map" src="{{ '/assets/img/field_work_map.png' | relative_url }}" alt="Map of field sample locations overlaid on global surface nitrate concentrations" class="img-fluid" />
</div>
