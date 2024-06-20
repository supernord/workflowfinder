---
description: Add a plain text description here.
sidebar: false
datatable: true
---

The interactive table below allows you to search for workflows [registered by Australian BioCommons partners on WorkflowHub](https://workflowhub.eu/programmes/8).

If you would like to add your bioinformatics workflows to [WorkflowHub](https://workflowhub.eu/), please see this [getting started guide](https://about.workflowhub.eu/docs/getting-started/).


<div class="d-flex flex-column">
  <div class="mb-2">
    <button
      class="btn btn-secondary text-light"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#collapse1"
      aria-expanded="false"
      aria-controls="collapseExample"
    >
      Can’t find the workflows you need? Click here to see other options for
      finding computational workflows.
      <i class="fa-solid fa-circle-chevron-down ms-1"></i>
    </button>
    <div class="collapse" id="collapse1">
      <div class="card card-body">
        <ul>
          <li>
            {% tool "workflowhub" %}
          </li>
          <li>
            {% tool "dockstore" %}
          </li>
          <li>
            {% tool "nf-core" %}
          </li>
          <li>
            {% tool "snakemake-registry" %}
          </li>
        </ul>
      </div>
    </div>
  </div>
</div>

<div markdown="0"> 
{% include table.html %}
</div>

