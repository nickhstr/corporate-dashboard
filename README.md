# Corporate Dashboard

A corporate dashboard built with a front-end framework. [Check it out!](https://nickhstr-corporate-dashboard.firebaseapp.com)

## Front-End Framework

This app leverages the power of the front-end framework Polymer to create a single-page corporate dashboard web app.
The app fetches both CSV and JSON data at a real-time frequency, maintains separation of data and views, and utlizes data-binding to share data from a single source to many views.

## Dashboard

Serving as a corporate dashboard, this app allows users to get a high-level view of company information, including employee count and locations, number of customers over a period of time, and all reported issues, digested through a sortable and filterable table.

## Build Process

Using the framework, this app is built with Polymer's build command.

To build this app locally:

- Clone this repo `git clone https://github.com/nickhstr/corporate-dashboard.git`
- `cd` into `dashboard`
- Install dependencies `bower install`
- Install polymer-cli `npm install -g polymer-cli`
- Run `polymer build`
- Serve the app with `polymer serve build/unbundled`