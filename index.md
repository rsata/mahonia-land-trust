---
layout: default
rules:
  - text: 'Notify one or more residents prior to your visit, so as not to surprise anyone or intrude.'
  - text: 'When driving, stay on graveled surfaces. Yield to oncoming traffic by backing up to reach a graveled surface suitable for passing (see map).'
  - text: 'Children should be supervised by an adult.'
  - text: 'No dogs without permission.'
  - text: 'Securely close any gates you go through.'
  - text: 'Ask a resident for permission before picking any fruits or vegetables.'
  - text: 'A public privy is available via a trail from the New Cabin (see map) or use the woods discretely.'
  - text: 'Respect our environment: if you pack it in, pack it out.'
  - text: 'No guns allowed.'
  - text: 'Visitors walking the land do so at their own risk.  Know your limits!'
---

<img src="/assets/img/branch.png" class="logo"/>

<h1 class="page-heading">Welcome to Mahonia!</h1>

Mahonia Land Trust Conservancy (MLTC) is a 67 acre property in unincorporated Oregon City, Oregon.  Over 50 acres are forested in various stages of second growth, and the remainder of the property is agricultural lands: pasture, orchards, and row crops.

The property is held in perpetuity as greenspace, serving to promote ecological diversity, preserve the common heritage of earth, and act as a living classroom for visitors and residents.

The land supports two houses, the residents of which serve as land stewards, utilizing the agricultural lands to produce organic produce for themselves and their larger community.

Want to engage deepter with MLTC?  Walk the trails regularly, birdwatch, or observe native plants in the woods.  Come volunteer at our workparties, help out on the farms, join in at a meeting and potluck, and share your skills by participating in our community!

<div class="buffer2">
  <div class="map-main">
    <img src="/assets/img/map-png.png" alt="Map of Mahonia">
  </div>  
  <div class="rules">
    <h1 class="page-heading">Rules for visiting</h1>
    <ol>
      {% for rule in page.rules %}
      <li>{{ rule.text }}</li>
      {% endfor %}
    </ol>    
  </div>
</div>