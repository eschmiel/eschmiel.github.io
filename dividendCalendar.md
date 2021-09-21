![Demonstration of the Dividend Calendar](https://eschmiel.github.io/dividend-calendar-demo.gif)

## A web app built with React and Typescript

---
[Web App](https://ibo-financials.com/dividenduidemo/) | [Github Repo](https://github.com/eschmiel/dividend-calendar)
<br/>
Username: test Password: test

## What is it?

The Dividend Calendar is a collaboration with my father. He recently transferred a lot of his investments into high-yield dividend stocks and wanted a way to visualize their payments throughout
the year. The Dividend Calendar allows users to set tracked stock positions (a symbol and share quantity) and then populates a calendar with the days dividend payments will fall on with their confirmed
or estimated payments.

To do this, I built a custom calendar component from scratch that generates the appropriate number of days and weeks, aligned with the appropriate days of the week, based on the month and year.
I created a form component that creates tracked stock position components that the user can modify or delete, which the application uses to populate the calendar. I also rounded things off with a monthly
and yearly summary component at the bottom.

For this project, I was building a frontend for a backend application my father built. I rely on his backend to retrieve the data necessary to populate the calendar.