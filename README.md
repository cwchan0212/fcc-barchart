  <body>
    <h1>[FreeCodeCamp] Data Visualization Projects</h1>
    <h2>Visualize Data with a Bar Chart</h2>
    <p align="justify"> Objective: Build an app that is functionally similar to
      this: <a href="https://codepen.io/freeCodeCamp/full/GrZVaM">https://codepen.io/freeCodeCamp/full/GrZVaM</a>.</p>
    <p align="justify">Fulfill the below user stories and get all of the tests
      to pass. Use whichever libraries or APIs you need. Give it your own
      personal style.</p>
    <p align="justify">You can use HTML, JavaScript, CSS, and the D3 svg-based
      visualization library. The tests require axes to be generated using the D3
      axis property, which automatically generates ticks along the axis. These
      ticks are required for passing the D3 tests because their positions are
      used to determine alignment of graphed elements. You will find information
      about generating axes at <a href="https://github.com/d3/d3/blob/master/API.md#axes-d3-axis">https://github.com/d3/d3/blob/master/API.md#axes-d3-axis</a>.
      Required (non-virtual) DOM elements are queried on the moment of each
      test. If you use a frontend framework (like Vue for example), the test
      results may be inaccurate for dynamic content. We hope to accommodate them
      eventually, but these frameworks are not currently supported for D3
      projects.</p>
    <p align="justify"><strong>User Story #1</strong>: My chart should have a
      title with a corresponding <strong>id="title"</strong>.</p>
    <p align="justify"><strong>User Story #2</strong>: My chart should have a g
      element x-axis with a corresponding <strong>id="x-axis"</strong>.</p>
    <p align="justify"><strong>User Story #3</strong>: My chart should have a g
      element y-axis with a corresponding<strong> id="y-axis"</strong>.</p>
    <p align="justify"><strong>User Story #4</strong>: Both axes should contain
      multiple tick labels, each with a corresponding<strong> class="tick"</strong>.</p>
    <p align="justify"><strong>User Story #5</strong>: My chart should have a <strong>rect
        </strong>element for each data point with a corresponding <strong>class="bar"
        </strong>displaying the data.</p>
    <p align="justify"><strong>User Story #6</strong>: Each bar should have the
      properties <strong>data-date</strong> and <strong>data-gdp </strong>containing
      date and GDP values.</p>
    <p align="justify"><strong>User Story #7</strong>: The bar elements'<strong>
        data-date</strong> properties should match the order of the provided
      data.</p>
    <p align="justify"><strong>User Story #8</strong>: The bar elements' <strong>data-gdp</strong>
      properties should match the order of the provided data.<br>
      <br>
      <strong>User Story #9</strong>: Each bar element's height should
      accurately represent the data's corresponding <strong>GDP</strong>.</p>
    <p align="justify"><strong>User Story #10</strong>: The <strong>data-date </strong>attribute
      and its corresponding bar element should align with the corresponding
      value on the x-axis.</p>
    <p align="justify"><strong>User Story #11</strong>: The <strong>data-gdp </strong>attribute
      and its corresponding bar element should align with the corresponding
      value on the y-axis.</p>
    <p align="justify"><strong>User Story #12</strong>: I can mouse over an area
      and see a tooltip with a corresponding<strong> id="tooltip"</strong> which
      displays more information about the area.</p>
    <p align="justify"><strong>User Story #13</strong>: My tooltip should have a
      <strong>data-date</strong> property that corresponds to the <strong>data-date</strong>
      of the active area.</p>
    <p align="justify">Here is the dataset you will need to complete this
      project: <a href="https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json">https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json</a></p>
    <p align="justify">You can build your project by using this CodePen template
      and clicking <strong>Save </strong>to create your own pen. Or you can
      use this CDN link to run the tests in any environment you like:<a href="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js">
        https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js</a>.</p>
    <p align="justify">Once you're done, submit the URL to your working project
      with all its tests passing.</p>
    <p align="justify">Solution: <a href="https://github.com/cwchan0212/fcc-barchart">Source
        </a>| <a href="https://codepen.io/cwchan0212/pen/eYMdvez">demo@codepen</a></p>
    
  </body>
