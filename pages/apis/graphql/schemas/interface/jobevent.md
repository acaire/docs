---
toc: false
---
<!--
  _____   ____    _   _  ____ _______   ______ _____ _____ _______
  |  __  / __   |  | |/ __ __   __| |  ____|  __ _   _|__   __|
  | |  | | |  | | |  | | |  | | | |    | |__  | |  | || |    | |
  | |  | | |  | | | . ` | |  | | | |    |  __| | |  | || |    | |
  | |__| | |__| | | |  | |__| | | |    | |____| |__| || |_   | |
  |_____/ ____/  |_| _|____/  |_|    |______|_____/_____|  |_|
  This file is auto-generated by script/generate_graphql_api_content.sh,
  please build the schema.json by running `rails api:graph:export`
  with https://github.com/buildkite/buildkite/,
  replace the content in data/graphql_data_schema.json
  and run the generation script `./scripts/generate-graphql-api-content.sh`.
-->
<!-- vale off -->
<h1 class="has-pills" data-algolia-exclude>
  JobEvent
  <span class="pill pill--interface pill--normal-case pill--large"><code>INTERFACE</code></span>
</h1>
<!-- vale on -->




<table class="responsive-table responsive-table--single-column-rows">
  <thead>
    <th>
      <h2 data-algolia-exclude>Fields</h2>
    </th>
  </thead>
  <tbody>
    <tr><td><h3 class="is-small has-pills"><code>actor</code><a href="/docs/apis/graphql/schemas/object/jobeventactor" class="pill pill--object pill--normal-case pill--medium" title="Go to OBJECT JobEventActor"><code>JobEventActor</code></a></h3><p>The actor that caused this event to occur</p></td></tr><tr><td><h3 class="is-small has-pills"><code>id</code><a href="/docs/apis/graphql/schemas/scalar/id" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR ID"><code>ID</code></a></h3></td></tr><tr><td><h3 class="is-small has-pills"><code>job</code><a href="/docs/apis/graphql/schemas/object/jobtypecommand" class="pill pill--object pill--normal-case pill--medium" title="Go to OBJECT JobTypeCommand"><code>JobTypeCommand</code></a></h3><p>The job that this event belongs to</p></td></tr><tr><td><h3 class="is-small has-pills"><code>timestamp</code><a href="/docs/apis/graphql/schemas/scalar/datetime" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR DateTime"><code>DateTime</code></a></h3><p>The time when the event occurred</p></td></tr><tr><td><h3 class="is-small has-pills"><code>type</code><a href="/docs/apis/graphql/schemas/enum/jobeventtype" class="pill pill--enum pill--normal-case pill--medium" title="Go to ENUM JobEventType"><code>JobEventType</code></a></h3><p>The type of event</p></td></tr><tr><td><h3 class="is-small has-pills"><code>uuid</code><a href="/docs/apis/graphql/schemas/scalar/id" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR ID"><code>ID</code></a></h3><p>The public UUID for this job event</p></td></tr>
  </tbody>
</table>






<h2 data-algolia-exclude>Possible types</h2>
<a href="/docs/apis/graphql/schemas/object/jobeventassigned" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT JobEventAssigned"><code>JobEventAssigned</code></a>
<a href="/docs/apis/graphql/schemas/object/jobeventbuildstepuploadcreated" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT JobEventBuildStepUploadCreated"><code>JobEventBuildStepUploadCreated</code></a>
<a href="/docs/apis/graphql/schemas/object/jobeventcanceled" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT JobEventCanceled"><code>JobEventCanceled</code></a>
<a href="/docs/apis/graphql/schemas/object/jobeventfinished" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT JobEventFinished"><code>JobEventFinished</code></a>
<a href="/docs/apis/graphql/schemas/object/jobeventgeneric" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT JobEventGeneric"><code>JobEventGeneric</code></a>
<a href="/docs/apis/graphql/schemas/object/jobeventretried" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT JobEventRetried"><code>JobEventRetried</code></a>
<a href="/docs/apis/graphql/schemas/object/jobeventtimedout" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT JobEventTimedOut"><code>JobEventTimedOut</code></a>