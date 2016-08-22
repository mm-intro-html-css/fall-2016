---
title: "Foundational HTML Skills"
published: true
morea_id: asm-html-min
morea_type: assessment
morea_sort_order: 3
morea_outcomes_assessed:
  - out-html-min
---
Student Directory: Assessed knowledge of basic shell, git and GitHub skills.

<link rel="stylesheet" href="http://cdn.oesmith.co.uk/morris-0.4.3.min.css">
<script src="//cdnjs.cloudflare.com/ajax/libs/raphael/2.1.0/raphael-min.js"></script>
<script src="http://cdn.oesmith.co.uk/morris-0.4.3.min.js"></script>

<div class="well">
  <div id="asm-html-min" style="height: 250px;"></div>
</div>

<script>
Morris.Bar({
  element: 'asm-html-min',
  hideHover: false,
  data: [
        { y: 'Very satisfactory (%)', num: 0 },
        { y: 'Satisfactory (%)', num: 0 },
        { y: 'Unsatisfactory (%)', num: 0 },
        { y: 'Absent (%)', num: 0 },
        ],
  xkey: 'y',
  ykeys: ['num'],
  resize: true,
  labels: ['Students']
});
</script>