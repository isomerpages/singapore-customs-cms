---
title: Test accordion
permalink: /test-accordion
accordion:
  - title: Simple
    content: This is a simple one line item
  - title: Multi-line Block
    content: |
      This is line 1

      This is line 2<br/>
      This is line 3
  - title: Multi-line Folded
    content: |
      This is all going
      to become just one line\n even though there are multiple lines
  - title: Ordered List
    content: |
      1. Item 1
      2. Item 2
      3. Item 3
  - title: Unordered List
    content: |
      * Item 1
      * Item 2
      * Item 3
---
# Accordion Sample

This is the line before original accordion

{% include accordion.html %}

This is the line after original accordion

==============================================

Line before html accordion

<ul class="jekyllcodex_accordion">
    
        <li><input id="accordion1" type="checkbox"><label for="accordion1">Simple</label><div><p>This is a simple one line item</p>
</div></li>
    
        <li><input id="accordion2" type="checkbox"><label for="accordion2">Multi-line Block</label><div><p>This is line 1</p>

<p>This is line 2<br>
This is line 3</p>
</div></li>
    
        <li><input id="accordion3" type="checkbox"><label for="accordion3">Multi-line Folded</label><div><p>This is all going
to become just one line\n even though there are multiple lines</p>
</div></li>
    
        <li><input id="accordion4" type="checkbox"><label for="accordion4">Ordered List</label><div><ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>
</div></li>
    
        <li><input id="accordion5" type="checkbox"><label for="accordion5">Unordered List</label><div><ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
</div></li>
    
</ul>

Line after html accordion