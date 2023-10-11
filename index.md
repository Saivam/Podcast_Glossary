---
layout: base
title: Podcast Glossary Terms
---
  <dl class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-2 mt-4 ">
    {% for term in dataset %}
      <div class="bg-white p-4 rounded shadow hover:bg-gray-300">
        <dt class="text-lg font-semibold mb-2">{{ term.term }} : </dt>
        <dd class="text-justify" >{{ term.definition }}</dd>
      </div>
    {% endfor %}
  </dl>

