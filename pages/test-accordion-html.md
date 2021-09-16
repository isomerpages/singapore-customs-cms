---
title: Test accordion html
permalink: /test-accordion-html
---
<ul class="jekyllcodex_accordion">
  <li>
    <input type="checkbox" id="accordion1">
    <label for="accordion1">Simple</label>
    <div>
      <p>This is a simple one line item</p>
    </div>
	</li>
    
  <li>
    <input type="checkbox" id="accordion2">
    <label for="accordion2">Multi-line Block</label>
    <div>
      <p>This is line 1</p>
      <p>This is line 2<br>
        This is line 3</p>
    </div>
  </li>
  
  <li>
    <input type="checkbox" id="accordion3">
    <label for="accordion3">Multi-line Folded</label>
    <div>
      <p>
        This is all going
        to become just one line\n even though there are multiple lines
      </p>
    </div>
  </li>
    
  <li>
    <input type="checkbox" id="accordion4">
    <label for="accordion4">Ordered List</label>
    <div>
      <ol>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
      </ol>
    </div>
  </li>
    
  <li>
    <input type="checkbox" id="accordion5">
    <label for="accordion5">Unordered List</label>
    <div>
      <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
      </ul>
    </div>
  </li>
</ul>