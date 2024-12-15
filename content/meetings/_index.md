---
title: "meetings"
linkTitle: "meetings"
description: "information about meetings"
images: ["images/elug-logo-v3-dark-bg.png"]

---

<div class="hero -mt-5 pb-0" style="min-height: 80vh" dir="rtl">
<div class="container push-down mb-5">
  <div class="row mb-2">
    <div class="col-12">
      <h1 class="font-weight-bold">جلسات برگزار شده</h1>
    </div>
  </div>
  <div class="row">
    <div class="col">
      <div class="form-group">
        <h5><label class="d-block" for="search">Search</label></h5>
        <input type="search" placeholder="Search query" class="form-control" 
          id="search" oninput="updateEnvItems()">
      </div>
    </div>
    <div class="col">
      <div class="form-group">
        <h5><label class="d-block" for="filter-lang">Filter by language</label></h5>
        <select class="form-control" id="filter-lang" onchange="updateEnvItems()">
          <option value="" selected disabled>Loading...</option>
        </select>
      </div>
    </div>
  </div>

  <div class="row" id="env-list"></div>
</div>










---
</div>



