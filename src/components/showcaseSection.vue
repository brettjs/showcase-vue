<template>

  <section id={{sectionId}}>

    <h2>
      {{sectionContent.title}}
      <span class="subtitle">
        {{sectionContent.subtitle}}
      </span>
    </h2>

    <div class="row">
      <div class="col-md-6">
        <div class="row">
          {{! one flex-grid per 3 items}}
          <div class="flex-grid">
            {{#each items as |item|}}
              {{showcase-item
                name=item.name
              }}
            {{/each}}
          </div>
        </div>
      {{! Repeat if there are more than 3 items }}

      </div> {{! end col-md-6 #1 }}
      <div class="col-md-6">
        {{sectionContent.desc}}
      </div>  {{! end col-md-6 #2 }}
    </div> {{! end row }}
  </section>

</template>
