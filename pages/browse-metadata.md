---
title: Browse the Collection
layout: page
permalink: /browse-metadata/
---

<ul class="nav nav-tabs" role="tablist">
  <li class="nav-item">
    <button class="nav-link active" data-bs-toggle="tab" data-bs-target="#creators" type="button">
      Creators
    </button>
  </li>
  <li class="nav-item">
    <button class="nav-link" data-bs-toggle="tab" data-bs-target="#publishers" type="button">
      Publishers
    </button>
  </li>
  <li class="nav-item">
    <button class="nav-link" data-bs-toggle="tab" data-bs-target="#series" type="button">
      Series
    </button>
  </li>
</ul>

<div class="tab-content mt-3">

  <!-- CREATORS -->
  <div class="tab-pane fade show active" id="creators">
    {% include subjects-list.html field="creator" %}
  </div>

  <!-- PUBLISHERS -->
  <div class="tab-pane fade" id="publishers">
    {% include subjects-list.html field="publisher;publisher2;" %}
  </div>

  <!-- SERIES -->
  <div class="tab-pane fade" id="series">
    {% include subjects-list.html field="series" %}
  </div>

</div>
