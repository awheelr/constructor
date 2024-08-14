![Constructor](/assets/icon.png)
> Constructor is an automated tool for calculating roofing and siding estimates. It integrates with Hover which provides housing measurements, using this data to automatically compute the total material and labor costs for the job.

## About

Constructor was developed for a construction company using Microsoft Excel and Visual Basic. Excel was chosen due to its widespread use and familiarity among office staff, making distribution easy and ensuring a smooth user experience. The tool is designed to be intuitive and user-friendly, catering to both new and experienced employees.

The tool features an interface tailored to each step of the estimating process. Users can select a job, import measurements, calculate costs, and generate detailed proposals ready for print or electronic delivery to customers.

In testing, Constructor demonstrated 95% accuracy when compared to manual estimates by employees.

## Features

### Importing Measurements

This tool is built around the fact that house measurements can be obtained by simply by taking photos of the house on your phone and letting a website like Hover do the rest of the work. Constructor connects to our construction companies account and utilizes the Hover API to get all the necessary data.

Users can either upload measurement files manually or utilize the custom interface, displaying available scanned houses with ready-to-export measurements.

![Measurement Upload](/assets/import-dropdown.gif)
![Measurement Interface](/assets/import-interface.png)

### Adjustments

Each imported job comes with default settings, but adjustments are easy to make using the main interface Formulas and pricing that handle calculating the quantity of materials needed have been abstracted away from the user so that they are only ever dealing with the smaller details that change depending on job.

![Main Interface](/assets/homepage.png)

### Proposal 

You can generate a proposal whenever a estimate has been completed. The layout of the proposal can be adjusted by the user and the file will export as a pdf. 

This is feature is a work in progress. Expected features will be included name and address of customer,contract terms, and signature field.

<p float="left" align="middle">
  <img src="/assets/printmenu.gif" width="250" />
  <img src="/assets/proposal.png" width="300" /> 
</p>


